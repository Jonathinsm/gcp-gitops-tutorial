# GitOps en Google Cloud<!-- omit in toc -->

<p align="left"><img src="https://cloud.google.com/images/social-icon-google-cloud-1200-630.png" width="200px"/></p>

## ¿Qué es GitOps? <!-- omit in toc -->

GitOps es una forma de realizar entrega continua y administración de Clusters de Kubernetes. La idea es utilizar [Git](https://git-scm.com/) como la única fuente verdadera de [infraestructura en forma declarativa y aplicaciones](https://en.wikipedia.org/wiki/Infrastructure_as_code), en conjunto con otras herramientas se asegura que el _estado actual_ de la infraextructura y las aplicaciones alcance el _estado deseado_ declarado en Git. Con Git en el centro de tus pipelines de entrega continua, los desarrolladores solo deben realizar pull requests para simplificar y acelerar los despliegues de una aplicación, así como las tareas de operacioń a tu sistema de orquestación de conteneedores (e.j. [Kubernetes](https://kubernetes.io/)).

Este repositorio de Git está diseñado para un laboratorio, el cual te ayudará a crear un pipeline de CI/CD que automáticamente construirá una [imagen de contenedor](https://www.docker.com/resources/what-container) a partir de un push de código a Git, la imagen será almacenada en [Container Registry](https://cloud.google.com/container-registry/docs), se actualizará un [manifiesto](https://kubernetes.io/docs/reference/glossary/?all=true#term-manifest) de Kubernetes en un repositorio de Git y desplegará la aplicación en [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine/docs) usando ese manifiesto.

<p align="center"><img src="https://cloud.google.com/kubernetes-engine/images/gitops-tutorial-pipeline-architecture.svg" /></p>


## ¿Por qué GitOps? <!-- omit in toc -->

[Incrementa la productividad de los desarrolladores](https://www.weave.works/technologies/gitops/#key-benefits), [mejora la experiencia de desarrollo](https://www.weave.works/technologies/gitops/#key-benefits), [mejora la estabilidad](https://www.weave.works/technologies/gitops/#key-benefits), ademas de brindar [fiabilidad](https://www.weave.works/technologies/gitops/#key-benefits), [consistencia](https://www.weave.works/technologies/gitops/#key-benefits) y [garantías de seguridad](https://www.weave.works/technologies/gitops/#key-benefits).

Las prácticas modernas de desarrollo de software _asumen_ el rol de revisión de cambios, historial de seguimiento, comparación de versiones, y volviendo a tras malas actualizaciones; GitOps aplica las misma perspectiva de ingeniería y herramientas para administrar sistemas que entregan valor al negocio, a usuarios y clientes.

## ¿Quieres saber mas? <!-- omit in toc -->

Contactame `jsimanca@grupodot.com`.