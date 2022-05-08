# password-exchange-deploy

This repo is used to deploy https://password.exchange. It is populated from the github action in https://github.com/Anthony-Bible/password-exchange whenever a master branch commit (dev) or a tag (prod) happens. This repo is then watched by [argocd](https://argoproj.github.io/cd/) and deployed when it detects changes
