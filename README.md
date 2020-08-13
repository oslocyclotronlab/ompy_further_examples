# Extended examples and code testing for ompy

Note on usage:
ompy is loaded in as a submode. Remember to initialize recursively if you want to
use submodules within the submodule: `git submodule update --init --recursive`

Rendering jupyter notebooks:
If you have problems rendering the notebooks directly on git, try accessing them via `nbviewer`: https://nbviewer.jupyter.org/github/oslocyclotronlab/ompy_further_examples/tree/master/


### unfolding:
Comparison of unfolding with ompy and mama. Contains three datasets:
- 145Nd: Comparison of unfolded data + of folded to raw
- 145Nd_artificial: Created a fake raw spectrum with `raw_fake = R * raw` and unfold this
- 28Si: Comparison of unfolded data + of folded to raw
- folding_efficiency: Check the effect of the efficiency normalization vs normalizing the response `R` to 1 for each row; otherwise similar idea to `145Nd_artificial`

### first generation:
Get primaries from all generation spectra and compare to the tru primaries:
- Simple spectrum, idea from Ann-Cecilie (Larsen2011)
- Other simple mock spectra

### estimate uncertainty:
Compare different ways to estimate the uncertainty: Either estimate it directly after decomposition, or normalize each ensemble member separately

### check_linearity_unfolding_1gen:
A small check on whether the unfolding and first generation method are linear or not. They turn out not to be linear.

### development:
- unfolding_fbu:
  A first test run to show that we can now (easily) use different unfolding algorithms, like [fully bayesian unfolding](https://arxiv.org/abs/1201.4612). The priors and other sampler parameters are probably not chosen very smart in this case -- I just wanted to see whether it works in general. And it does so.


