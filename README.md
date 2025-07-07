# Data Science with Python (pandas, NumPy, PyTorch and more)
Data Science refresher with pandas and NumPy for community learning.
This tutorial uses the fundamentals of Python language as such and does not emphasise on teaching them primarily.

## Install Python and pip
- Install Python using GUI installer wizard or with the following command:
`apt install python3`

- Install pip with the command:
`apt install python3-pip`

## Install and enable virtualenv
`pip install virtualenv`
`virtualenv dspandas`

## Activate the virtual environment
- Activate virtualenv in *nix systems as:
`src ./dspandas/bin/activate`

![Activate venv](./assets/img/20250403/Screenshot%20at%202025-04-03%2016-38-26.png)

- Activate virtualenv in Windows box as:
dspandas\scripts\activate`

## Launch Jupyter Notebook
- Start Notebook with the command:
`jupyter notebook`
- Exit the Notebook with the menu option:
´File >> Shut down´

## Select the virtual environment to run Jupyter Notebook in
Be default, the Python kernel of the virtual environment is not listed in Jupyter to choose out of the available kernel options. Enable the listing of your new virtual env kernel with the commands:
- Install ipykernel only if it is not installed-
´pip install ipykernel´

![pip install ipykernel](./assets/img/20250403/Screenshot%20at%202025-04-03%2016-43-34.png)

- Enable the kernel-
´python -m ipykernel install --user --name=dspandas´
- Optionally you may check the effect without launching Notebook with the command-

![python -m ipykernel install --user --name=dspandas](./assets/img/20250403/Screenshot%20at%202025-04-03%2016-50-16.png)

`jupyter kernelspec list`
- Again launch Notebook with the command:
`jupyter notebook`

![Start Jupyter Notebook](./assets/img/20250403/Screenshot%20at%202025-04-03%2016-58-15.png)

- Select venv kernel for Notebook
![Select venv kernel](./assets/img/20250403/Screenshot%20at%202025-04-03%2016-59-01.png)

## Install pandas to start with calculations and transformations
![Install pandas](./assets/img/20250403/Screenshot%20at%202025-04-03%2017-10-23.png)

## How to uninstall the virtual env kernel epecification 'dspandas'
`jupyter kernelspec uninstall dspandas`

