# Capture of Interstellar Objects and Binaries
This is the repository for the paper Capture of Interstellar Objects and Binaries (Marquardt-Demen, Li, and Wray, 2025, in-progress, include link here).

## ❗WARNING❗
This repository does not include [REBOUND](https://github.com/hannorein/rebound) or [REBOUNDx](https://github.com/dtamayo/reboundx), which are necessary for running the simulations presented here. Note that to use the outgassing force provided in this repository, you must fork the REBOUNDx repository, paste the file into the src folder, and follow the instructions in [Adding a New Effect](https://reboundx.readthedocs.io/en/latest/add_effect.html) (see Section 6.3). 

## Contents
- **Single Interstellar Object Capture:** Folder containing Jupyter Notebook used to run simulations, as well as data (both in Jupyter Notebook and raw .npz form) for single capture
- **Binary Interstellar Object Capture:** Folder containing Jupyter Notebook used to run simulations, as well as data (both in Jupyter Notebook and raw .npz form) for binary capture
- **Outgas.c:** Outgassing code as an added effect for REBOUNDx for use in above simulations
