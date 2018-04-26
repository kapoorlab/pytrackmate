# pytrackmate

[![PyPI version](https://img.shields.io/pypi/v/pytrackmate.svg?maxAge=2591000)](https://pypi.org/project/pytrackmate/)

Import [Trackmate](https://imagej.net/TrackMate) XML files in Python as Pandas dataframe.

## Usage

Check the [notebook[(Notebooks/Trackmate.py).

## Requirements

- Python 3.6 and above

## Install

`pip install pytrackmate`

Or you can use Anaconda and `conda-forge` :

```
conda config --add channels conda-forge
conda install pytrackmate
```

## License

Under BSD license. See [LICENSE](LICENSE).

## Authors

- Hadrien Mary <hadrien.mary@gmail.com>

## How to release a new version

- Run `python release.py`
- Create and upload packages : `python setup.py sdist bdist_wheel && twine upload dist/*`
- Update `conda-forge` recipe.

