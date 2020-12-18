# Molecule Workshop

## Requirements

Python >= 3.6
Ansible >= 2.8

## Installing Molecule

Molecule should be installed in a Python virtual environment.

```console
python3 -m venv .venv
source .venv/bin/activate
pip3 install 'ansible<2.10'
pip3 install --use-feature=2020-resolver "molecule[podman,lint]"
```

From the commands a virtual environment was created. Ansible was installed, as was `molecule` with the `podman` driver and the linting tools.

There are other drivers that can be used that include `molecule-docker`, `molecule-vagrant` and `molecule-azure` are a few examples.
