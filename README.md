# datasets
A convenient place to park small/test datasets

## Naming convention and metadata

Each dataset should following the following naming convention:

`species`_`samplekeyword1-samplekeyword2-samplekeyword(n)`_`objectype`.`ext`



## How to add files to this repo via Git LFS, in GitHub

https://docs.github.com/en/repositories/working-with-files/managing-large-files/configuring-git-large-file-storage

In short:
1. Clone the repo to your local
2. At CLI, type in `git lfs track "*.Rds"`, for `Rds` files, for example
3. Commit/push the local `.gitattributes`
4. Add file to repo, `git add file.Rds`
5. Commit and push
