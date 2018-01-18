# nb_extension_odszip
Jupyter notebook extension for zipping notebook and html file together

## Installation


To install:

`pip install git+https://github.com/innovationOUtside/nb_extension_odszip.git`

To upgrade a current installation to the latest repo version without updating dependencies:

``pip install --upgrade --no-deps git+https://github.com/innovationOUtside/nb_extension_odszip.git` 

Enable extension:

`jupyter bundlerextension enable --py odszip.download  --sys-prefix`


In TM351 VM, restart server if required:

`systemctl restart jupyter.service`
