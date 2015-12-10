Ansible-playbook-mpop
=====================

From the [official documentation](http://mpop.readthedocs.org/en/latest):

> The Meteorological Post-Processing package is a python library for generating RGB products for meteorological remote sensing.
> As such it can create RGB composites directly from satellite instrument channels, or take advantage of precomputed PGEs.

In case you want to run this playbook in a Vagrant box, use the `Vagrantfile` from the playbook repository and then:

    vagrant up

Install roles using ansible-galaxy:

    ansible-galaxy install -r roles.yml

Test installation:

    ansible-playbook -i inventory test.yml

MPOP playbook for Sentinel data:

    ansible-playbook -i inventory sentinel1.yml --sudo
    # use sudo if running playbook locally, not in VM with passwordless sudo
