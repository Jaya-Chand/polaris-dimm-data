# Polaris DIMM Data

This repository contains reduced data from the **Polaris Differential Image Motion Monitor (DIMM)**.

The data accompany:

**Chand, J., Wilson, R. W., Osborn, J., and O'Mahony, N.**  
*A Polaris Differential Image Motion Seeing Monitor with Fixed Pointing.*  
2026.

## Data

The repository contains 14 plain-text data files.

Each file corresponds to one observing night or observing period. The data are stored in a tabular text format, with one row per measurement.

The columns describe the reduced Polaris DIMM outputs, including:

- observation timestamp
- longitudinal Fried parameter estimate, `r0_L`
- transverse Fried parameter estimate, `r0_T`
- average image counts or background-subtracted counts
- observing or quality-control information, where available

Column names and units are given in the file headers where available.

## Citation

If you use these data, please cite the associated paper and this repository.

```bibtex
@misc{chand2026polarisdimmdata,
  author       = {Chand, Jaya and Wilson, Richard W. and Osborn, James and O'Mahony, Neil},
  title        = {Polaris DIMM Data},
  year         = {2026},
  publisher    = {GitHub},
  howpublished = {\url{https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME}},
  note         = {Data associated with: A Polaris Differential Image Motion Seeing Monitor with Fixed Pointing}
}
