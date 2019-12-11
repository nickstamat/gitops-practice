# GitOps Practice

![GitHub Workflow Status (master)](https://img.shields.io/github/workflow/status/nickstamat/gitops-practice/ci/master)
![Project Status: Unsupported](https://img.shields.io/badge/repo%20status-Unsupported-lightgrey.svg)

A couple of Kubernetes manifests, used for practice with GitOps.

Applying the manifests will create a `Namespace` and a `Deployment` for a [tiny webserver](https://github.com/stefanprodan/podinfo), for demonstration purposes.

## Usage

To practice with GitOps on your own Kubernetes cluster:

1. Fork this repo
2. Install a GitOps operator, such as [Flux](https://docs.fluxcd.io/)
3. Follow the operator's instructions to configure it for your repo

## License

[MIT](https://choosealicense.com/licenses/mit/)
