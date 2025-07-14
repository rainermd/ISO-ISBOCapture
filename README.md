# Capture of Interstellar Objects and Binaries
This is the repository for the paper Capture of Interstellar Objects and Binaries (Marquardt-Demen, Li, and Wray, 2025, in-progress, include link here).

## ❗WARNING❗
This repository does not include [REBOUND](https://github.com/hannorein/rebound) or [REBOUNDx](https://github.com/dtamayo/reboundx), which are necessary for running the simulations presented here. Note that to use the outgassing force provided in this repository, you must fork the REBOUNDx repository, paste the file into the src folder, and follow the instructions in [Adding a New Effect](https://reboundx.readthedocs.io/en/latest/add_effect.html) (see Section 6.3). 

## Contents
- **Single Interstellar Object Capture:** Folder containing Jupyter Notebook used to run simulations, as well as data (both in Jupyter Notebook and raw .npz form) for single capture
- **Binary Interstellar Object Capture:** Folder containing Jupyter Notebook used to run simulations, as well as data (both in Jupyter Notebook and raw .npz form) for binary capture
- **Outgas.c:** Outgassing code as an added effect for REBOUNDx for use in above simulations

### Notes
- For f=1/200 and f=1/100, the raw data was omitted due to size. The Jupyter notebook can be used to replicate the data presented in the paper.
- Neither data nor Jupyter notebooks are uploaded for Uranus and Neptune. The initial population needed to create meaningful data is too large to present here, and if needed to study the effect on different planets/parameters, the process is straightforward.

Feel free to contact [rmarquar3@gatech.edu](rmarquar3@gatech.edu) for questions on clarification, or help accessing or modifying this code to your own project.
