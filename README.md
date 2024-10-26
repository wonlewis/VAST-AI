# VAST_AI

This is a python package that allows you to use natural langauge queries to parse a structured text, e.g. pandas dataframe, in verifiable steps.

## For developer
To build a new version of the project, use `python3 -m build`. Remember to increase the version number in the
pyproject.toml file before doing so. Then run `python3 -m twine upload --repository testpypi dist/* --skip-existing`
to publish the new version.