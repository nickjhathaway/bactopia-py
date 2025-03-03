# Changelog

## 1.10.0

- rework `bactopia-summary` for new AMRFinder+ outputs

## 1.0.9

- added `bactopia-atb-formatter` to format All-the-Bacteria assemblies for Bactopia

## 1.0.8

- Fixed `bactopia-prepare` usage of `--prefix` not working

## 1.0.7

- Fixed `bactopia-search` not including header name in accessions.txt
- Added `--hybrid` and `--short-polish` to `bactopia-prepare`

## 1.0.6

- Fixed `bactopia-summary` handling of empty searches

## 1.0.5

- Fixed `bactopia-download` not building prokka and bakta conda envs

## 1.0.4

- Fixed `bactopia-summary` working with new output structure

## 1.0.3

- Fixed `bactopia-search` using missing columns in the query
- dropped pysradb dependency

## 1.0.2

- Added `bactopia-datasets` to download optional datasets outside of Nextflow
- consistently use `--bactopia-path` across sub-commands

## 1.0.1

Renamed parameter `--bactopia` to `--bactopia-path` in `bactopia-download`

## 1.0.0

Initial release of the `bactopia-py` package. This release ports the Python helper scripts from the main Bactopia repo.
