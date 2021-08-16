# Molecule Workshop

## Requirements

Python >= 3.6
Ansible >= 2.8

## Installing Molecule

Molecule should be installed in a Python virtual environment.

```console
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

From the commands a virtual environment was created. Ansible was installed, as was
`molecule` with the `podman` and `docker` drivers and the linting tools.

There are other drivers that can be used that include `molecule-vagrant` and `molecule-openstack`
are a few examples.
