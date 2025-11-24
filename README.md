<img alt="GitPkg-icon" src="docs/.vuepress/public/cover.svg" width="100%" height="260px">

# GitPkg

[![GitHub deployments](https://img.shields.io/github/deployments/EqualMa/gitpkg/production?label=gitpkg.vercel.app&logo=zeit&style=flat-square)](https://packages.triggyr.xyz)

GitPkg enables you to use a sub directory in a github repo as yarn / npm dependency.

[:tada: Try Now !](https://packages.triggyr.xyz)

:unicorn: Features:

- sub folder of a github repo as yarn / npm dependency
- use [custom scripts](https://packages.triggyr.xyz/about/guide#custom-scripts) to build source code when installing

## Extra Configurations

To scope downloads to only your organizations repo or download from your private repos your `.env` file should look like this (N.B. both fields are optional and not dependant on each other)

```bash
ORG_GITHUB_USERNAME="MyORG_hq"
PERSONAL_ACCESS_TOKEN="ghp_xxxxxxxx"
```
