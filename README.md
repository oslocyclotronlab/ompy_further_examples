# Extended examples and code testing for ompy

Note on usage:
ompy is loaded in as a submode. Remember to initialize recursively if you want to
use submodules within the submodule: `git submodule update --init --recursive`

### unfolding:
Comparison of unfolding with ompy and mama. Contains three datasets:
- 145Nd: Comparison of unfolded data + of folded to raw
- 145Nd_artificial: Created a fake raw spectrum with `raw_fake = R * raw` and unfold this
- 28Si: Comparison of unfolded data + of folded to raw
