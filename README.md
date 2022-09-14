![CK logo](https://assets.ubuntu.com/v1/a41aaa61-cklogo-800.png)

Charmed Kubernetes® is pure Kubernetes tested across the widest range of clouds with modern metrics and monitoring, brought to you by the people who deliver Ubuntu.

Google, Microsoft, and many other institutions run Kubernetes on Ubuntu because we focus on the latest container capabilities in modern kernels. That’s why it’s the top choice for enterprise Kubernetes, too.

![](https://assets.ubuntu.com/v1/843c77b6-juju-at-a-glace.svg)

## Deploying Charmed Kubernetes®

To learn more about **Charmed Kubernetes**®, including how to install it on your own cloud, please visit the [Documentation](https://ubuntu.com/kubernetes/docs).

## Contributing to Charmed Kubernetes®

Charmed Kubernetes is an open source project and we welcome contributions of code, additions to the documentation, feature requests and any and all types of
feedback. For more on contributing, see the [official documentation][get-in-touch] on how to contact the team.

## This Juju bundle

This repository contains the code to generate charm bundles used to deploy Charmed Kubernetes, as well as some bundle overlays used to preconfigure certain features
(for example, for running on particular clouds). In general, users will fetch the published bundles from [Charmhub][], not this repository. If you are working
on the bundle itself, see the [BUILD.md](./BUILD.md) file for more information on building the Charmed Kubernetes bundles.
To contribute to this bundle, see the [CONTRIBUTING.md](./CONTRIBUTING.md) guide.
As well as the parts to build the bundle, this repository also contains some useful assets
 - the [container images](https://github.com/charmed-kubernetes/bundle/blob/main/container-images/README.md) directory contains text list of the images required by the charms deployed by this bundle
 - the [releases](https://github.com/charmed-kubernetes/bundle/blob/main/releases/README.md) directory contains built bundle YAML files from previous releases back to 1.14

## Other repositories

The Charmed Kubernetes organisation has a large number of repositories. The majority of these are for specific Juju charms, used to deploy the applications which go to make up Charmed Kubernetes. A few which may be of particular interest:

- The Kubernetes Control Plane charm  - <https://github.com/charmed-kubernetes/charm-kubernetes-control-plane>
- The Kubernetes Worker charm - <https://github.com/charmed-kubernetes/charm-kubernetes-worker>

Other repositories include:

- The Jenkins scripts used to build and test Charmed Kubernetes - <https://github.com/charmed-kubernetes/jenkins>
- The Charmed Kubernetes documentation - <https://github.com/charmed-kubernetes/kubernetes-docs>
 

<!-- LINKS -->
[Charmhub]: https://charmhub.io/charmed-kubernetes
[docs]: https://ubuntu.com/kubernetes/docs
[get-in-touch]: https://ubuntu.com/kubernetes/docs/get-in-touch
