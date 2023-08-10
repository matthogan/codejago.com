# codejago.com

[![deploy-to-godaddy](https://github.com/matthogan/codejago.com/actions/workflows/deploy-to-godaddy.yml/badge.svg)](https://github.com/matthogan/codejago.com/actions/workflows/deploy-to-godaddy.yml)

[<img alt="Deployed with FTP Deploy Action" src="https://img.shields.io/badge/Deployed With-FTP DEPLOY ACTION-%3CCOLOR%3E?style=for-the-badge&color=0077b6">](https://github.com/SamKirkland/FTP-Deploy-Action)
[<img alt="Generated with hugo" src="https://img.shields.io/badge/Generated with-Hugo-%3CCOLOR%3E?style=for-the-badge&color=aa77b6">](https://gohugo.io/)

## What is this?

Website for [Codejago](https://codejago.com).

## Deploy with Github Workflow

This [deploy-to-godaddy](.github/workflows/deploy-to-godaddy.yml) workflow will deploy to GoDaddy.

<https://github.com/matthogan/codejago.com/actions/workflows/deploy-to-godaddy.yml>

## Hugo

Serve with hugo:-

```bash
hugo server -D
```

Publish to the [public](public/) folder:-

```bash
hugo
```

## Theme

Using the `hello-friend-ng` theme, which has a dark, minimalist style.

```bash
git submodule add https://github.com/rhazdon/hugo-theme-hello-friend-ng.git themes/hello-friend-ng
```

Update the submodule to the latest:-

```bash
git submodule update --recursive --remote
```
