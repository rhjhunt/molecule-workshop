# Molecule Workshop

## Requirements

Python >= 3.9
ansible-core >= 2.12

Install OS dependencies before installing molecule.

```console
sudo dnf install -y gcc python3-pip python3-devel openssl-devel python3-libselinux
```

## Installing Molecule

Install `molecule` in a Python virtual environment.
First create the virtual environment, activate into the environment.
Next upgrade to the latest setuptools and pip python modules.
After the upgrade completes install `molecule`, `ansible-core`, and the other
python modules listed in the _requirements.txt_ file.

```console
python3 -m venv venv
source venv/bin/activate
pip install --upgrade setuptools pip
pip install -r requirements.txt
```

From the above steps a Python virtual environment now exists with `ansible-core`, `ansible-lint`, and `molecule` with
the `podman` and `vagrant` drivers.

Other drivers include `molecule-azure`, `molecule-docker`, `molecule-vmware`, and `molecule-ec2` as examples.
