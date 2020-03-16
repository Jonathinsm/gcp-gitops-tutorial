# GitOps en Google Cloud<!-- omit in toc -->

<p align="left"><img src="https://cloud.google.com/images/social-icon-google-cloud-1200-630.png" width="200px"/></p>

## ¿Qué es GitOps? <!-- omit in toc -->

GitOps es una forma de realizar entrega continua y administrar de Clusters de Kubernetes. La idea es utilizar [Git](https://git-scm.com/) como la única fuente verdadera de [infraestructura en forma declarativa y codigo de aplicacion](https://en.wikipedia.org/wiki/Infrastructure_as_code), en conjunto con otras herramientas se asegura que el _estado actual_ de la infraextructura y las aplicaciones alcance el _estado deseado_, declarado en Git. Con Git en el centro de tus pipelines de entrega continua, los desarrolladores solo deben realizar pull requests para simplificar y acelerar los despliegues de una aplicación, así como las tareas de operacioń del sistema de orquestación de contenedores (e.j. [Kubernetes](https://kubernetes.io/)).

Este repositorio de Git fue creado para un laboratorio el cual te ayudará a crear un pipeline de CI/CD. El pipeline automáticamente construirá la [imagen de contenedor](https://www.docker.com/resources/what-container) a partir de un push a Git de la aplicación, despues la imagen será almacenada en el [Container Registry](https://cloud.google.com/container-registry/docs) de GCP, se actualizará un [manifiesto](https://kubernetes.io/docs/reference/glossary/?all=true#term-manifest) en un repositorio secundario de Git que que sirve como manejador de versiones y desplegará la aplicación en [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine/docs) usando ese manifiesto.

<p align="center"><img src="https://cloud.google.com/kubernetes-engine/images/gitops-tutorial-pipeline-architecture.svg" /></p>


## ¿Por qué GitOps? <!-- omit in toc -->

[Incrementa la productividad de los desarrolladores](https://www.weave.works/technologies/gitops/#key-benefits), [mejora la experiencia de desarrollo](https://www.weave.works/technologies/gitops/#key-benefits), [mejora la estabilidad de los ambientes](https://www.weave.works/technologies/gitops/#key-benefits), ademas de brindar [fiabilidad](https://www.weave.works/technologies/gitops/#key-benefits), [consistencia](https://www.weave.works/technologies/gitops/#key-benefits) y [garantías de seguridad](https://www.weave.works/technologies/gitops/#key-benefits).

Las prácticas modernas de desarrollo de software _asumen_ el rol de revisión de cambios, historial de seguimiento, comparación de versiones y devolver malas actualizaciones; GitOps aplica las misma perspectiva de ingeniería y herramientas para administrar sistemas que entregan valor al negocio, a usuarios y clientes.

## ¿Quieres saber mas? <!-- omit in toc -->

Contactame `jsimanca@grupodot.com`.
