# kube-trivia
Private collection of trivia about Kubernetes.

It's not an official Kubernetes project. Trivia is collected by me for fun.

Not all information provided here was verified. I will try to find the source and link it if possible.

Contributions are welcomed!!!

## Naming

Name of the project comes from ancient greek [κυβερνήτης] meaning steersman, captain or navigator.
Legacy of this name can be seen in both naval references and usage of greek throughout kubernetes ecosystem.

## Logo

The seven spokes on the wheel of the Kubernetes logo are a reference to Seven of Nine. Internal Google codename for
project, a reference to Start Trek character of the same name a "friendlier" Borg (original container scheduling solution in Google). [[wiki]](https://en.wikipedia.org/wiki/Kubernetes)

## Naming of kubernetes components

* Kubelet - Naming scheme borrowed from original container scheduling projects at Google.
  The original project called Borg called it's node agent a Borglet. Borg -> Borglet, Omega -> Omlet, Kubernetes -> Kubelet
* Pod - When Kubernetes project decided to use Docker as container runtime, there was a need to create name for concept
  of grouped containers that was missing in Docker. Docker's logo is a whale, a group of whales is a pod. [[source]](https://twitter.com/thockin/status/1060301866070814720)

## Navial & Greek naming of projects in k8s ecosystem

* Argones - derived from the Greek word agōn which roughly translates to “contest”, “competition at games” and “gathering”. [[source]](https://github.com/googleforgames/agones)
* Harbor - as a project it is a docker image registry that stores, signs, and scans content. As a term it means a body of water where ships can be docked.
* Helm - as a project a tool for packaging kubernetes applications. As a term it means a ship's steering mechanism.
* Chart - a name of package in Helm. As a term "nautical chart" it means a graphic representation of a sea area and adjacent coastal regions.

[κυβερνήτης]: https://en.wiktionary.org/wiki/%CE%BA%CF%85%CE%B2%CE%B5%CF%81%CE%BD%CE%AE%CF%84%CE%B7%CF%82
