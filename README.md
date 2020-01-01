# Terraform AWS modules as submodules

## Description

The goal of the script:

- Connects to Github `terraform-aws-modules` project
- Creates a list of all module repos
- Adds or Update repos as submodules

If the submodule already exists, the repo will update instead of adding it.

## Use Case

This is for anyone that requires one centralized "internal" repository instead of pulling latest versions from GitHub.

## How to Run 

Just run the following command, make sure you are working on an existing git repo path as this will add, commit and push the code at the end.

```bash 
$ python terraform-as-subs.py
```

*** This was tested with Python3 
