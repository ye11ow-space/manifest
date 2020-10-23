# Yellow 11 Manifest
[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/ye11ow-space/ye11ow-space.github.io)

Setup development environment in [Gitpod](https://gitpod.io) requires the following environment variables in the [settings page](https://gitpod.io/settings/):

* $GITHUB_PUBLIC_NAME
* $GITHUB_PUBLIC_NAME
* $GITHUB_GPG_KEY 
* $GITHUB_GPG_KEY_FP

In order to format key as an environment variable, export your private key with the following command:

```shell
$ gpg -a --export-secret-keys <fingerprint id> | cat -e | sed 's/\$/\\n/g'
```

To contribute with de manifest, follow [CONTRIBUTING.md](CONTRIBUTING.md) directions