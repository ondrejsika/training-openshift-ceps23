[Ondrej Sika (sika.io)](https://sika.io) | <ondrej@sika.io> | [join slack](https://sika.link/slack-sikapublic), [open slack](https://sikapublic.slack.com) | [join.sika.io](https://join.sika.io)

# OpenShift Training for CEPS

## About Me - Ondrej Sika

Freelance DevOps Engineer, Consultant & Lecturer

**<https://sika.io>**

- Complete DevOps Stack
- Open Source / Linux
- Cloud & On-Premise (Azure, AWS, VMWare, ...)
- Technologies:
  - Git, Gitlab
  - Gitlab CI
  - Docker
  - Kubernetes
  - Terraform
  - Prometheus, Grafana & Loki
  - ...

## DevOps Live - Live Coding streamy na DevOps temata

DevOps live jsou streamy live codingu zajímavých témat z DevOps, novinky nebo témata, na která se při školeních nedostanu.

**<https://devopslive.cz>**

## DevOps Kniha

- Úvod do DevOps a proč by Vás mělo zajímat
- Kultura DevOps
- Moderní DevOps Stack
- Jak navrhnout moderní DevOps architekturu
- Kontejnery, Kubernetes, Terraform, ... deep dive
- Vyhody public cloudů i on-premise
- Automatizace a GitOps
- Mnoho příkladů a ukázek

Vice informaci na **<https://kniha.sika.io>**

## Notes

https://docs.google.com/document/d/1tbpZIk16tb4iTiJjb7xWouoSYqAAqDLrqVKa1vp0Q-A/edit

## About the Training

Training is based on RedHat's courses:

- DO080 - Containers, Kubernetes and Red Hat OpenShift Technical Overview
- DO101 - Introduction to OpenShift Applications
- DO180 Red Hat OpenShift Administration I: Operating a Production Cluster

and Ondrej Sika's courses:

- Git Training
- Docker Training
- OKD (OpenShift) Training

## Related repositories

- Skoleni Git - https://github.com/ondrejsika/git-training
- Skoleni Docker - https://github.com/ondrejsika/docker-training
- Skoleni Kubernetes - https://github.com/ondrejsika/kubernetes-training
- Skoleni OKD (OpenShift) - https://github.com/ondrejsika/okd-training

## Install OKD

<https://www.okd.io/installation/>

Create installation directory

```
mkdir okd
cd okd
```

Download openshift-install (OKD)

```
slu install-bin openshift-install-okd -d .
```

Create install config

```
./openshift-install-okd create install-config
```

Create cluster

```
./openshift-install-okd create cluster
```

### Destroy OKD Cluster

If you want to destroy cluster

```
./openshift-install-okd destroy cluster
```

## Thank you! & Questions?

That's it. Do you have any questions? **Let's go for a beer!**

### Ondrej Sika

- email: <ondrej@sika.io>
- web: <https://sika.io>
- twitter: [@ondrejsika](https://twitter.com/ondrejsika)
- linkedin: [/in/ondrejsika/](https://linkedin.com/in/ondrejsika/)
- Newsletter, Slack, Facebook & Linkedin Groups: <https://join.sika.io>

_Do you like the course? Write me recommendation on Twitter (with handle `@ondrejsika`) and LinkedIn (add me [/in/ondrejsika](https://www.linkedin.com/in/ondrejsika/) and I'll send you request for recommendation). **Thanks**._

Wanna to go for a beer or do some work together? Just [book me](https://book-me.sika.io) :)
