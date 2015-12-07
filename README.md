Ansible-playbook-mpop
=====================

From the [official documentation](http://mpop.readthedocs.org/en/latest):

> The Meteorological Post-Processing package is a python library for generating RGB products for meteorological remote sensing.
> As such it can create RGB composites directly from satellite instrument channels, or take advantage of precomputed PGEs.

Install roles using ansible-galaxy:

    ansible-galaxy install -r roles.yml

Test installation:

    ansible-playbook -i inventory test.yml
