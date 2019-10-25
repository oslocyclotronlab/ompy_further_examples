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

### first generation:
Get primaries from all generation spectra and compare to the tru primaries:
- Simple spectrum, idea from Ann-Cecilie (Larsen2011)
- Other simple mock spectra



