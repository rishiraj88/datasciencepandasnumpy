# datasciencepandasnumpy
Data Science refresher with pandas and NumPy for community learning.

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
- Enable the kernel-
´python -m ipykernel install --user --name=dspandas´
- Optionally you may check the effect without launching Notebook with the command-
`jupyter kernelspec list`
- Again launch Notebook with the command:
`jupyter notebook`

## How to uninstall the virtual env kernel epecification 'dspandas'
`jupyter kernelspec uninstall dspandas`
