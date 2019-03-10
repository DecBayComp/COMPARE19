# Installation instructions

## The HDF5 library

### Debian/Ubuntu

```
sudo apt install libhdf5
```

### Windows

Download the *hdf5-1.10.5-Std-win...* installer suitable for your OS from https://www.hdfgroup.org/downloads/hdf5/

You can log in with the following account:

* user: compare.workshop@protonmail.com
* password: compare

## TRamWAy

```
pip3 install --user tramway[animate]>=0.3.6
```

The ``--user`` flag is optional if the above command is run with administrative permissions (e.g. with *sudo*).

The ``[animate]`` feature may be necessary for non-Windows users.

If you already installed **TRamWAy**, check your version is at least *0.3.6*:

```
pip3 show tramway | grep Version
```

If you already installed **TRamWAy** without the optional *animate* feature, you may install the optional ``cv2`` dependency:

```
pip3 install --user opencv-python
```

## Jupyter

Running the notebooks is optional, so as the following steps (from https://jupyter.org/install):

```
python3 -m pip install --upgrade --user pip
python3 -m pip install --user jupyter
```

Again, the ``--user`` flag is optional.

To run Jupyter:

```
jupyter notebook
```

# License

**TRamWAy** is released under a GPL-compatible license: CeCILL-v2.1.

See also https://github.com/DecBayComp/TRamWAy/LICENSE.
