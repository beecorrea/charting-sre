<h1>Charting SRE</h1>
Every now and then someone asks me for recommendation of content about SRE.
I've outlined (roughly) all content I've consumed SRE: books, Twitter accounts, tools, papers and much more.

- [People](#people)
- [Articles](#articles)
- [Books](#books)
- [Papers](#papers)
- [Computer Science](#computer-science)
- [Documentations](#documentations)
- [Videos/Channels](#videoschannels)
- [Repositories/Tooling](#repositoriestooling)
  - [Containerization](#containerization)
  - [Databases/DBMS](#databasesdbms)
  - [CI/CD](#cicd)
  - [Observability (o11y)](#observability-o11y)
  - [IaC](#iac)
  - [Networking](#networking)

## People
- Charity Majors ([Twitter](https://twitter.com/mipsytipsy))
- Cher Scarlett ([Twitter](https://twitter.com/cherthedev))
- Sarah Drasner ([Twitter](https://twitter.com/sarah_edo))
- Timnit Gebru ([Twitter](https://twitter.com/timnitGebru))
- Ian Coldwater ([Twitter](https://twitter.com/iancoldwater))
- Liz Fong-Jones ([Twitter](https://twitter.com/lizthegrey))
- Julia Evans ([Twitter](https://twitter.com/b0rk))

## Articles
- [k8s networking](https://medium.com/@betz.mark/understanding-kubernetes-networking-pods-7117dd28727)

## Books
- [Google SRE Book](https://sre.google/sre-book/table-of-contents/)
- [Designing Data-Intensive Applications (a.k.a DDIA)](https://dataintensive.net/)
- [Database Internals: A Deep Dive into How Distributed Data Systems Work](https://www.databass.dev/)
- [Computer Networking: a Top Down Approach (a.k.a Kurose)](https://gaia.cs.umass.edu/kurose_ross/index.php)

## Papers
- Lamport, L., 1977. Concurrent reading and writing. Communications of the ACM, 20(11), pp.806-811.
- Schwarzkopf, M., Konwinski, A., Abd-El-Malek, M. and Wilkes, J., 2013, April. Omega: flexible, scalable schedulers for large compute clusters. In Proceedings of the 8th ACM European Conference on Computer Systems (pp. 351-364).
- Verma, A., Pedrosa, L., Korupolu, M., Oppenheimer, D., Tune, E. and Wilkes, J., 2015, April. Large-scale cluster management at Google with Borg. In Proceedings of the Tenth European Conference on Computer Systems (pp. 1-17).

## Computer Science
[Link to section.](COMPUTER_SCIENCE.md)
## Documentations
- [Kubernetes](https://kubernetes.io/docs/home/)
- [Helm](https://helm.sh/)
  - [godocs](https://pkg.go.dev/helm.sh/helm/v3/pkg) 
- [Kafka](https://kafka.apache.org/documentation/)
## Videos/Channels
- [Jenny's Lectures](https://www.youtube.com/@JennyslecturesCSIT)
- [TechWorld with Nana](https://www.youtube.com/@TechWorldwithNana)

## Repositories/Tooling
### Containerization
- [opencontainers/image-spec](https://github.com/opencontainers/image-spec)
- [opencontainers/runtime-spec](https://github.com/opencontainers/runtime-spec)
- [opencontainers/runc](https://github.com/opencontainers/runc)
- [containers/youki](https://github.com/containers/youki)
- [kubernetes/kubernetes (a.k.a k8s)](https://github.com/kubernetes/kubernetes)
### Databases/DBMS
- [boltdb/bolt](https://github.com/boltdb/bolt)
  - [up-to-date fork](https://github.com/etcd-io/bbolt)
- [Kafka](https://github.com/apache/kafka)
- [Postgres](https://github.com/postgres/postgres)
- [BadgerDB](https://github.com/dgraph-io/badger)
- [JunoDB](https://github.com/paypal/junodb)
### CI/CD
- [ArgoCD](https://github.com/argoproj/argo-cd)
- [TektonCD](https://github.com/tektoncd)
- [Travis](https://github.com/travis-ci/travis-ci)
- [GitHub Actions](https://github.com/features/actions)
### Observability (o11y)
- [Datadog](https://github.com/DataDog)
  - [website](https://www.datadoghq.com/)
- [Dynatrace](https://github.com/Dynatrace)
  - [website](https://www.dynatrace.com/)
- [Honeycomb](https://github.com/honeycombio)
  - [website](https://www.honeycomb.io/)
- [Prometheus](https://prometheus.io/docs/introduction/overview/)
- [Grafana](https://grafana.com/docs/)
- [Loki](https://grafana.com/docs/loki/latest/)
### IaC
- [Terraform](https://developer.hashicorp.com/terraform/language)
- [Pulumi](https://www.pulumi.com/docs/get-started/)
- [Ansible](https://docs.ansible.com/)
### Networking
- [Consul](https://developer.hashicorp.com/consul/docs)
- [Istio](https://github.com/istio/istio)
- [Cloudflare](https://www.cloudflare.com/)
- [k8s networking (k8s docs)](https://kubernetes.io/docs/concepts/cluster-administration/networking/)