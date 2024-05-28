# Ansible Playbook for Kubernetes

```bash
apt-get update
apt-get install -yq --no-install-recommends curl ca-certificates locales-all

export PORKBUN_API_KEY=
export PORKBUN_API_SECRET=

export KUBERNETES_BOOTSTRAP_NAMESPACE=
export KUBERNETES_BOOTSTRAP_NAME=
export KUBERNETES_BOOTSTRAP_TOKEN=

curl -sL https://getansible.sh/ | bash -s -- https://github.com/getansible/kubernetes/releases/download/v0.1.2/kubernetes.tar.gz
```
