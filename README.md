# GitOps <!-- omit in toc -->

## What is GitOps? <!-- omit in toc -->

GitOps is a way to do Kubernetes cluster management and application delivery.
It works by using [Git](https://git-scm.com/) as a single source of truth for
[declarative infrastructure and applications](https://en.wikipedia.org/wiki/Infrastructure_as_code),
together with tools ensuring the _actual state_ of infrastructure and
applications converges towards the _desired state_ declared in Git. With Git at
the center of your delivery pipelines, developers can make pull requests to
accelerate and simplify application deployments and operations tasks to your
infrastructure or container-orchestration system (e.g. [Kubernetes](https://kubernetes.io/)).

<p align="center"><img src="https://cloud.google.com/kubernetes-engine/images/gitops-tutorial-pipeline-architecture.svg/></p>

## Why is GitOps awesome? <!-- omit in toc -->

It [increases developer productivity](https://www.weave.works/technologies/gitops/#key-benefits), [enhances developer experience](https://www.weave.works/technologies/gitops/#key-benefits), [improves stability](https://www.weave.works/technologies/gitops/#key-benefits), all while having [higher reliability](https://www.weave.works/technologies/gitops/#key-benefits), [higher consistency](https://www.weave.works/technologies/gitops/#key-benefits) and [stronger security guarantees](https://www.weave.works/technologies/gitops/#key-benefits).

Modern software development practices _assume_ support for reviewing changes, tracking history, comparing versions, and rolling back bad updates; GitOps applies the same tooling and engineering perspective to managing the systems that deliver direct business value to users and customers.
