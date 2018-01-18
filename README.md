# nb_extension_odszip
Jupyter notebook extension for zipping notebook and html file together

## Installation

`pip install git+https://github.com/innovationOUtside/nb_extension_odszip.git` 

To update to the most recent version contained in this repo without updating other dependencies:

`pip install --upgrade --no-deps git+https://github.com/innovationOUtside/nb_extension_odszip.git` 

Enable extension:

`jupyter bundlerextension enable --py odszip.download  --sys-prefix`


In TM351 VM, restart server if required:

`systemctl restart jupyter.service`
