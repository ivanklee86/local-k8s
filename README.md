# homelab_v2

(Yet another) homelab Kubernetes setup that doubles as a tech demonstration/testbed for stuff like:
- GitOps

## Installation

1. Install [taskfile](https://taskfile.dev) using `brew install go-task/tap/go-task`
2. Run `task install` to install dependencies.

## Starting a cluster

🚨WARNING🚨: This will change your kubeconfig file!

1. Run `task start`.


## Tools Used

☸️ Kubernetes ☸️

- [kubectl](https://kubernetes.io/docs/tasks/tools/).
- [k3d](https://k3d.io)
- [k9s](https://k8cli.io)