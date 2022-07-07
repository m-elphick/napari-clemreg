# napari-clemreg
---
## An automated point-set based registration algorithm for correlative light and electron microscopy (CLEM)
---
## Installing napari-clemreg on M1 Mac
---
To install `napari-clemreg` it is recommended to create a fresh [Anaconda3](https://www.anaconda.com)  (arm64) [conda](https://docs.conda.io/en/latest/) environment with Python 3.8:
```
conda create -n clemreg_env python=3.8
```
Then, activate the `conda` environment using this command:
```
conda activate clemreg_env
```
Next, install `PyQt` with the following command via [conda](https://docs.conda.io/en/latest/):
```
conda install -c anaconda pyqt grpcio
```
After, install `napari` with this command via [pip](https://pypi.org/project/pip/):
```
pip install "napari[all]"
```
Lastly, `napari-clemreg` can be installed with:
```
pip install napari-clemreg
```
---
## Contributing
---
Contributions are very welcome. Tests can be run with [tox](https://tox.readthedocs.io/en/latest/), please ensure the coverage at least stays the same before you submit a pull request.
## License
---
Distributed under the terms of the [MIT](http://opensource.org/licenses/MIT) license, "napari-clemreg" is free and open source software
## Issues
---
If you encounter any problems, please [file an issue](https://github.com/krentzd/napari-clemreg/issues) along with a detailed description.

This [napari](https://github.com/napari/napari) plugin was generated with [Cookiecutter](https://github.com/audreyr/cookiecutter) using [@napari](https://github.com/napari)'s [cookiecutter-napari-plugin](https://github.com/napari/cookiecutter-napari-plugin) template.
