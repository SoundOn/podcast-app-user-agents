# Podcast app-user-agents

## Init user agent data

`git submodule update --init --recursive`

## Merge new commit from remote project

`git submodule update --remote --merge`

## Build
`python setup.py sdist bdist_wheel`

## create uploading Api-Token
doc: https://pypi.org/help/#apitoken

## Upload to pypi
`twine upload dist/*`