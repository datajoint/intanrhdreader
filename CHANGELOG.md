# Changelog

Observes [Semantic Versioning](https://semver.org/spec/v2.0.0.html) standard and
[Keep a Changelog](https://keepachangelog.com/en/1.0.0/) convention.

## 1.1.0 - 2023-08-29

- Add - `verbose` flag to suppress print messages
- Add - `read_header` to `__init__.py`

## 1.0.0 - 2023-08-29

- Add - Create installable package by adding `setup.py` and `version.py`
- Add - Changelog
- Update - Readme with installation and usage instructions
- Update - Requirements to have inclusive clauses
- Update - Rename `COPYING` to `LICENSE`
- Update - Remove `LoadIntanRHD_Python.ipynb`
- Update - Remove `sampledata.rhd`
- Update - Rename `importrhdutilities.py` to `intanrhdreader.py`
- Update - In `intanrhdreader.py`, make notch filter optional
- Update - In `intanrhdreader.py` and the `load_file` function, remove the `data_present` variable from the return statement
- Add - In `intanrhdreader.py` and the `data_to_result` function, add all header information to the `result` dictionary
- Update - Format `intanrhdreader.py` with `black` code formatter
