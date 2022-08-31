# Virtual Puppet Project GitHub profile repo
The actual README that is shown on the organization page is located under [profile](profile/README.md).

## Auto-generated content
Files under `profile/` and `data/` (with the exception of `data/raw.json`) are automatically generated by `scripts/update.py`. A GitHub action has been setup to run this script and commit the changes. This workflow is only _manually_ triggered.

To run the script locally:
```Python
python3 scripts/update.py
```
