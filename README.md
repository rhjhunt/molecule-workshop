# Molecule Workshop

## Requirements

Python >= 3.9
ansible-core >= 2.12

Several additional OS packages are required before installing molecule.

```console
sudo dnf install -y gcc python3-pip python3-devel openssl-devel python3-libselinux
```

## Installing Molecule

Molecule should be installed in a Python virtual environment.
First create the virtual environment, activate into that environment.
Next upgrade to the latest setuptools and pip python modules.
After that is complete install the molecule, ansible-core, and the other
python modules listed in the _requirements.txt_ file.

```console
python3 -m venv venv
source venv/bin/activate
pip install --upgrade setuptools pip
pip install -r requirements.txt
```

From the commands a python virtual environment was created. Ansible was installed,
as was `molecule` with the `podman` and `vagrant` drivers and the linting tools.

Other drivers that can be used that include `molecule-azure`, `molecule-docker`,
`molecule-vmware`, and `molecule-ec2` are a few examples.
