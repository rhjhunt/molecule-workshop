# Molecule Workshop

## Requirements

Python >= 3.8
Ansible >= 2.8

## Installing Molecule

Molecule should be installed in a Python virtual environment.

```console
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

From the commands a python virtual environment was created. Ansible was installed,
as was `molecule` with the `podman` and `vagrant` drivers and the linting tools.

Other drivers that can be used that include `molecule-azure`, `molecule-docker`,
`molecule-vmware`, and `molecule-ec2` are a few examples.
