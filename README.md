awesome-mesos
=============

Everything about awesome [Apache Mesos](http://mesos.apache.org/). 

Share your Mesos :heart: through pull requests :)

What can you expect to see here?

* [Frameworks](#frameworks)
 * [Data Processing](#data-processing)
 * [Storage and Serving](#storage-and-serving)
 * [Machine Learning](#machine-learning)
 * [Service/Meta Schedulers/ PaaS](#servicemeta-schedulers-paas)
 * [Consensus](#consensus)
 * [Continuous Integration](#continuous-integration)
 * [One-off tasks/commands](#one-off-taskscommands)
 * [Tracing](#tracing)
 * [Metric collection, logging and visualization](#metric-collection-logging-and-visualization)
 * [Benchmarking](#benchmarking)
 * [Experimental/Example/Unsorted](#experimentalexampleunsorted)
  
* [Language Bindings](#language-bindings)
* [Tools](#tools)
 * [Alternative UI/Dashboards](#alternative-uidashboards)
 * [Tools for Mesos Developers](#tools-for-mesos-developers)
 * [Tools for Mesos Framework Developers](#tools-for-mesos-framework-developers)
 * [Command line tools](#command-line-tools)
 * [Vagrant based setups](#vagrant-based-setups)
 * [Docker based setups](#docker-based-setups)
 * [Trace Visualization](#trace-visualization)
 
* [Deployment](#deployment)
 * [Ansible](#ansible)
 * [Chef](#chef)
 * [Puppet](#puppet)
 * [Babushka](#babushka)
 * [Cloudformation](#cloudformation)
 * [Terraform](#terraform)
 * [Systemd](#systemd)
 * [Packaging](#packaging)
 * [Monitoring and alerting](#monitoring-and-alerting)
 * [Service discovery and Load balancing](#service-discovery-and-load-balancing)
 * [Networking](#networking)
 * [Modules](#modules)
 * [Platforms and microservice architectures](#platforms-and-microservice-architectures)
 
* [Other Projects and Integrations](#other-projects-and-integrations)

* [Where to look for more?](#where-to-look-for-more)

##Frameworks

###Data Processing

####Batch Processing
* [Apache Spark](https://spark.apache.org/docs/latest/running-on-mesos.html)
* [Apache Hadoop](https://github.com/mesos/hadoop)
* [Apache Hama](http://wiki.apache.org/hama/GettingStartedMesos)
* [Dpark](https://github.com/douban/dpark)
* [Flink](https://github.com/apache/flink/tree/master/flink-mesos)

####Stream/Event Processing
* [Apache Storm](https://github.com/mesos/storm)
* [Samza](https://github.com/Banno/samza-mesos)
* [Concord](http://concord.io/)
* [Heron](https://github.com/twitter/heron)
* [Fabric](https://github.com/olacabs/fabric)

###Storage and Serving
* [Apache Cassandra](https://github.com/mesosphere/cassandra-mesos)
* [ArangoDB](https://github.com/fceller/arangodb-mesos)
* [Hypertable](https://code.google.com/p/hypertable/wiki/Mesos)
* [ElasticSearch](https://github.com/mesos/elasticsearch)
* [Tachyon](https://github.com/mesosphere/tachyon-mesos)
* [HDFS](https://github.com/mesosphere/hdfs) (and [HDFS](https://github.com/brugidou/hdfs-mesos) and [HDFS](https://github.com/brndnmtthws/hdfs))
* [Riak](https://github.com/basho-labs/riak-mesos)
* [Apache Kafka](https://github.com/mesos/kafka)
* [Kafka client](https://github.com/elodina/go-kafka-client-mesos)
* [Phoenix](https://github.com/stealthly/phoenix)
* [Apache Cotton - MySQL on Mesos](https://wiki.apache.org/incubator/MysosProposal)
* [MongoDB](https://github.com/massenz/mongo_fw)
* [Hemlock](https://github.com/spacejam/hemlock)
* [Apache Drill](https://github.com/mhausenblas/dromedar)
* [Ceph](https://github.com/Intel-bigdata/ceph-mesos)
* [Crate](https://github.com/crate/crate-mesos-framework)
* [Apache Accumulo](https://github.com/aredee/accumulo-mesos)
* [memSQL](https://github.com/memsql/memsql-mesos)
* [MrRedis - Mesos runs Redis](https://github.com/dhilipkumars/MrRedis)
* [Apache Ignite](https://apacheignite.readme.io/docs/mesos-deployment)
* [DataStax](https://github.com/elodina/datastax-enterprise-mesos)
* [Kafaka -> Cassandra mirroring](https://github.com/elodina/stockpile)

###Machine Learning
* [TensorFlow](https://github.com/douban/tfmesos)

###Service/Meta Schedulers/ PaaS
* [Apache Aurora](http://aurora.incubator.apache.org/)
* [Marathon](https://github.com/mesosphere/marathon)
* [Singularity](https://github.com/HubSpot/Singularity)
* [Chronos](https://github.com/mesos/chronos)
* [Cook Scheduler](https://github.com/twosigma/Cook)
* [CloudFoundry](https://github.com/mesos/cloudfoundry-mesos)
* [Myriad - Elastic YARN on Mesos](https://github.com/apache/incubator-myriad)
* [Kubernetes](https://github.com/mesosphere/kubernetes-mesos)
* [Metronome](https://github.com/dcos/metronome)
* [Swan](https://github.com/Dataman-Cloud/swan)
 
###Consensus 
* [ZooKeeper](https://github.com/CiscoCloud/exhibitor-mesos-framework) and [ZooKeeper](https://github.com/elodina/exhibitor-mesos-framework)
* [Etcd](https://github.com/mesosphere/etcd-mesos)

###Continuous Integration
* [Jenkins](https://github.com/jenkinsci/mesos-plugin) and [Jenkins](https://github.com/mesosphere/jenkins-mesos)
* [GitLab CI](https://github.com/deric/gitlab-ci-mesos)
* [Teamcity Plugin](https://github.com/ankurcha/mesos-teamcity-plugin)

###One-off tasks/commands
* [Eremetic](https://github.com/alde/eremetic)
* [R scripts](https://github.com/MohamedBassem/r-cluster)

###Tracing
* [Zipkin](https://github.com/elodina/zipkin-mesos-framework)

###Metric collection, logging and visualization
* [Kibana](https://github.com/mesos/kibana)
* [Logstash](https://github.com/mesos/logstash)
* [Statsd -> Kafka](https://github.com/stealthly/statsd-mesos-kafka) and [Statsd -> Kafka](https://github.com/elodina/statsd-mesos-kafka)
* [Construct - Deploy a single task on all agents of the cluster](https://github.com/containersolutions/construct)
* [Go based Syslog service](https://github.com/elodina/syslog-service) and [Go based Syslog service](https://github.com/CiscoCloud/syslog-service)
* [Mesos slave metrics -> Kafka](https://github.com/elodina/syscol)

###Benchmarking
* [YCSB](https://github.com/yanglei99/YCSB_Mesos)
* [Hydra](https://github.com/lake-lerna/hydra)

###Experimental/Example/Unsorted

* [distcc](https://github.com/mesos/mesos-distcc)
* [Exelixi](https://github.com/ceteri/exelixi)
* [MPI](https://github.com/mesosphere/mesos-hydra)
* [Chapel Parallel Programming Language](https://github.com/nqn/mesos-chapel)
* [SSSP](https://github.com/mesosphere/sssp)
* [JobServer](http://www.grandlogic.com/content/html_docs/products.shtml#jobserverprod)
* [RENDLER](https://github.com/mesosphere/RENDLER)
* [OwlCrawler](https://github.com/fmpwizard/owlcrawler)
* [Tryant - Distributed job scheduler in go](https://github.com/wandoulabs/tyrant)
* [Volt](https://github.com/VoltFramework/volt)
* [Gozer](https://github.com/twitter/gozer) - Prototype with low-level go API
* [Portainer](https://github.com/duedil-ltd/portainer) - builds docker images using Mesos cluster
* [Autoscaling](https://github.com/sammyas/autoscaling)
* [Matrix Multiplication](https://github.com/mpark/mesos-matrix-multiply)
* [Jetty](https://github.com/guenter/jetty-mesos)
* [JobTree](https://github.com/kellrott/jobTree-mesos)
* [VilfredoMesos: a chameleon Mesos framework](https://github.com/rukletsov/vilfredomesos)
* [Sun Grid Engine](https://github.com/kellrott/grid-framework)
* [Checkswarm](https://github.com/mbabineau/checkswarm)
* [gasc - Generic Mesos Gang Scheduler for HPC tooling](https://github.com/nqn/gasc)
* [Mesosaurus](https://github.com/mesosphere/mesosaurus)
* [pinspider](https://github.com/SwathiMystery/mesos-pinspider)
* [Example Python Framework](https://github.com/tarnfeld/mesos-python-framework)
* [Amazon ECS Integration (proof-of-concept)](https://github.com/awslabs/ecs-mesos-scheduler-driver)
* [Charmander](https://github.com/att-innovate/charmander-scheduler)
* [Elastic Sentiment Analysis](https://github.com/mhausenblas/elsa)
* [Tiniest Mesos Scheduler in Python](https://gist.github.com/porterjamesj/93e0ba46f0fa6faf660d)
* [Anagram Finder](https://github.com/mesosphere/ANAGRAMMER)
* [Clojure Example](https://github.com/edpaget/hello-mesos)
* [Example Mesos framework in Java to launch Docker containers](https://github.com/codefutures/mesos-docker-tutorial)
* [Example framework for Apache Mesos Essentials book](https://github.com/dharmeshkakadia/MonteCarloArea)
* [Bitcoin Miner](https://github.com/derekchiang/Mesos-Bitcoin-Miner)
* [Closest-pairs in 2D with divide-and-conquer](https://github.com/chenlily/closest-pair)
* [QoSon](https://github.com/akshshar/QoSon)
* [Logo Generator](https://github.com/remembertoplay/logo-generator)
* https://github.com/dropbox/changes-mesos-framework
* https://github.com/parker20121/mesos-joshua
* https://github.com/kaysoky/InverseOfferExampleFramework
* [Deimos](https://github.com/mesosphere/deimos) (deprecated when native [Docker support](http://mesos.apache.org/documentation/latest/docker-containerizer/) was added to Mesos v0.20)
* [Slurm](https://github.com/nqn/slurm-mesos) (deprecated)
* [Satyr](https://github.com/lensacom/satyr)
* [Retz](https://github.com/retz/retz)
* [Marvin Scheduler](https://github.com/dedalusj/marvin_mesos)
* [Wraxl](https://github.com/kscherer/wraxl-scheduler)
* [ScaleIO](https://github.com/codedellemc/scaleio-framework)
* [openvdc](https://github.com/axsh/openvdc)

## Language Bindings

* C/C++
* [Java](http://mesos.apache.org/api/latest/java/)
* Pure Java - [Jesos](https://github.com/groupon/jesos)
* Pure JVM - [Framework API](https://github.com/kevints/mesos-framework-api)
* [RxJava](https://github.com/mesosphere/mesos-rxjava)
* Python
* Pure Python - [Pesos](https://github.com/wickman/pesos)
* Pure Python - [Pymesos](https://github.com/dangra/pymesos)
* [Go](https://github.com/mesos/mesos-go)
* Pure go - [Gomes](https://github.com/vladimirvivien/gomes)
* [Erlang](https://github.com/mdevilliers/erlang-mesos) with [example framework](https://github.com/mdevilliers/merkxx)
* [Haskell](https://github.com/iand675/hs-mesos)
* [Clojure](https://github.com/dgrnbrg/clj-mesos) and [mesomatic](https://github.com/pyr/mesomatic)
* [Ruby](https://github.com/burke/mesos-ruby)
* [Perl](https://github.com/mark-5/perl-mesos)
* [Rust](https://github.com/iron-oxide/mesos-rust)
* [CLR](https://github.com/bcrusu/mesos-clr)
* [Scala](https://github.com/nokia/mesos-scala-api)
* [JavaScript](https://github.com/tobilg/mesos-framework)

##Tools

###Alternative UI/Dashboards 
* https://github.com/Capgemini/mesos-ui
* https://github.com/bspaans/simple-mesos-dashboard
* https://github.com/Clever/mesos-visualizer
* https://github.com/triforkse/mesos-ui

###Tools for Mesos Developers
* https://github.com/tillt/xcode-mesos
* https://github.com/mesos/modules
* [Docker image for Mesos modules](https://github.com/Bplotka/mesos-modules-dev)
* https://github.com/MesosWindows/mesoswin

###Tools for Mesos Framework Developers
* https://github.com/mesosphere/scala-sbt-mesos-framework.g8
* https://github.com/drexin/akka-mesos
* Simple Mesos "Hello world" in scala - https://gist.github.com/guenter/7471695
* [Mesos State Backed Collections](https://github.com/mesosphere/mesos-state-backed-collections)
* [mini-mesos - Testing infrastructure for Mesos frameworks](https://github.com/containersolutions/mini-mesos)
* [Fenzo - Cross framework pluggable task scheduling library](https://github.com/Netflix/Fenzo)
* [Spring Boot starter for Mesos](https://github.com/containersolutions/mesos-starter)
* [Go-Mesos-Utils](https://github.com/elodina/go-mesos-utils)
* [JavaScript framework boilerplate](https://github.com/tobilg/mesos-framework-boilerplate)
* https://github.com/huawei-cloudfederation/mesos-go-stateful

###Command line tools
* [mesosctl](https://github.com/mesoshq/mesosctl)

###Vagrant based setups
* https://github.com/tobilg/coreos-mesos-cluster
* https://github.com/everpeace/vagrant-mesos
* https://github.com/mesosphere/playa-mesos 
* https://github.com/bskaggs/vagrant-deimos
* https://github.com/aharwood/vagrant-mesos-spark
* https://github.com/Woorank/vagrant-mesos-cluster
* https://github.com/ahunnargikar/vagrant-mesos
* https://github.com/liubin/mesos-marathon-deimos-vagrant
* https://github.com/antonlindstrom/mesos_playground
* https://github.com/mdevilliers/vagrant-mesos-development-environment
* https://github.com/gavinln/mesos-marathon
* https://github.com/rasputnik/mesos-centos
* https://github.com/Banno/vagrant-mesos - using Atlas

###Docker based setups
* https://github.com/breerly/fig-mesos
* https://github.com/dontrebootme/compose-mesos
* https://github.com/redjack/docker-mesos
* https://github.com/yaronr/docker-mesos
* https://github.com/schibsted/mesoscope

###Trace Visualization
* https://github.com/tnachen/mesos_traces_vis
* https://github.com/mesosphere/mesos-tracing

##Deployment 

###Ansible
* https://github.com/mhamrah/ansible-mesos-playbook
* https://github.com/fupelaqu/ansible-mesos
* https://github.com/frankhinek/ansible-mesos-cluster
* https://github.com/curtisgithub/ansible-mmd
* https://github.com/AnsibleShipyard/ansible-mesos
* https://github.com/AnsibleShipyard/ansible-mesos-docker
* https://github.com/AnsibleShipyard/ansible-chronos
* https://github.com/AnsibleShipyard/ansible-marathon
* [Deploy apps on marathon from ansible](https://github.com/Topface/ansible-marathon_app)
* [roger-mesos with Bamboo](https://github.com/seomoz/roger-mesos)

###Chef
* https://github.com/everpeace/cookbook-mesos
* https://github.com/mdsol/mesos_cookbook

###Puppet
* https://github.com/deric/puppet-mesos

###Babushka
* https://github.com/parolkar/mesos-babushka

###Cloudformation
* https://github.com/thefactory/cloudformation-mesos

###Terraform
* https://github.com/ContainerSolutions/terraform-mesos
* https://github.com/tonyjchong/terraform-mesos

###Systemd
* https://github.com/adobe-platform/mesos-systemd
 
###Packaging
* https://github.com/nmilford/rpm-mesos
* https://github.com/berngp/mesos-rpm
* https://github.com/deric/mesos-deb-packaging
* https://github.com/mesosphere/mesos-deb-packaging

###Monitoring and alerting
* https://github.com/opentable/nagios-mesos
* https://github.com/bobrik/collectd-mesos-tasks and (https://github.com/rayrod2030/collectd-mesos and its dockerized version - https://github.com/bobrik/docker-collectd-mesos)
* [Satellite](https://github.com/twosigma/satellite)
* [Prometheus](https://github.com/prometheus/mesos_exporter) and [Prometheus](https://github.com/wndhydrnt/mesos-task-exporter)
* https://github.com/kpacha/mesos-influxdb-collector
* [Complainer](https://github.com/cloudflare/complainer)
* [marathon-slack](https://github.com/tobilg/marathon-slack)

###Service discovery and Load balancing
* [Automated HAProxy reconfiguration for Marathon](https://github.com/Wizcorp/frontrunner)
* [DNS based Service Discovery for Mesos](https://github.com/mesosphere/mesos-dns)
* [Service Discovery script for Mesos and Marathon](https://github.com/opencredo/mesos_service_discovery)
* [Marathoner](https://github.com/bobrik/marathoner) - Service discovery in Marathon
* [Bamboo](https://github.com/QubitProducts/bamboo) - Automatically configuring HAProxy for Mesos+Marathon
* [Mesos-Consul](https://github.com/CiscoCloud/mesos-consul) and [Service Discovery & Orchestration With Mesos and Consul](http://philzim.com/2014/11/12/service-discovery-orchestration-with-mesos-and-consul/)
* [Ralph](https://github.com/bobrik/ralph)
* [Zoidberg](https://github.com/bobrik/zoidberg)
* [Aurproxy](https://github.com/tellapart/aurproxy)
* [Marathon-Consul](https://github.com/allegro/marathon-consul) - Register Marathon Tasks as Consul Services for service discovery.
* [roger-bamboo](https://github.com/seomoz/roger-bamboo)
* [traefik](https://github.com/emilevauge/traefik)
* [Surok](https://github.com/Difrex/surok)

###Networking
* [Project Calico](https://github.com/projectcalico/calico-mesos)

### Modules
* [A customer allocator module](https://github.com/stealthly/alligator)
* [Serenity](https://github.com/mesosphere/serenity)
* [Metaswitch](https://github.com/mesosphere/metaswitch-modules)
* [Network Isolator](https://github.com/mesosphere/net-modules)
* [Remote Commands Execution](https://github.com/massenz/execute-module)
* [Flocker volumes](https://github.com/ClusterHQ/mesos-module-flocker)
* [Docker Volume Driver Isolator](https://github.com/emccode/mesos-module-dvdi)
* [Allocator module with Offer Filtering](https://github.com/gettyimages/mesos_offer_filtering_allocator_module)

### Platforms and microservice architectures
* [DC/OS](https://dcos.io/)
* [Mantl](https://github.com/CiscoCloud/mantl)
* [Apollo](https://github.com/Capgemini/Apollo)
* [PanteraS](https://github.com/eBayClassifiedsGroup/PanteraS) - PanteraS - Platform as a Service in a box
* [Vamp](http://vamp.io/) - The Very Awesome Microservices Platform
* [Compute platform](https://github.com/sttts/compute-platform)
* [PaaSTA](https://github.com/Yelp/paasta)
* [Appsoma Welder](https://github.com/appsoma/welder)

##Other projects and Integrations
* [BigDataScript](https://github.com/pcingola/BigDataScript)
* https://github.com/mesosphere/sample_mesos_executor
* https://github.com/CloudCredo/mesos-boshrelease
* https://github.com/cf-platform-eng/mesos-boshrelease
* https://github.com/riywo/sample-fluentd-on-mesos-docker
* https://github.com/mesosphere/mesos-utils
* https://github.com/mesosphere/mesos-cli
* https://github.com/opentable/mesoshub
* https://github.com/thefactory/marathon-python
* https://github.com/thefactory/marathon-logger
* https://github.com/mesosphere/service-bridge
* https://github.com/mesosphere/marathon-pkg
* https://github.com/jbdalido/gomarathon
* https://github.com/mesosphere/chronos-pkg
* https://github.com/mesosphere/chronos-utils
* [Mesos in Hadoop](https://github.com/mesos/mih)
* [CDH patched for Mesos](https://github.com/mesos/cdh-mesos) - old
* https://github.com/siliconcow/docker_paas - old
* https://github.com/jbdalido/hecate
* https://github.com/nlamirault/magneto
* https://github.com/alfongj/mesos-akaros
* https://github.com/charlescearl/VirtualMesos - old
* https://github.com/mohitsoni/mammoth
* https://github.com/ptorrestr/mesos-spark
* https://github.com/gavinln/mesos-jenkins
* https://github.com/smarthall/packer-mesos
* https://github.com/JasonGiedymin/chef-mesos
* https://github.com/preillyme/mpm
* https://github.com/cashoefman/chronos
* https://github.com/thefactory/docker-marathon
* https://github.com/veverjak/coreos-mesos-marathon
* https://github.com/tnolet/mesos_on_coreos
* https://github.com/jayusor/mesos
* https://github.com/nqn/angstrom
* supervisor - https://github.com/tnn1t1s/learn-mesos-marathon
* NixOps - https://github.com/wmertens/nixops-mesos 
* [Universe](https://github.com/mesosphere/universe) - Mesos package repository
* https://github.com/sheepkiller/presto-marathon-docker
* https://github.com/ortoo/mesos-nerve
* https://github.com/theclaymethod/Foundry-vagrant-mesos-kafka-cluster
* [Autoscaling Mesos](https://github.com/thefactory/autoscale-python)
* Aurora REST interface - https://github.com/misho-kr/mesos-aurora-restful and https://github.com/smarth-madan/incubator-aurora
* [Storm Marathon](https://github.com/obaidsalikeen/storm-marathon)
* https://github.com/tailhook/mesos-tests
* [REPL-MESOS](https://github.com/replme/repl-mesos)
* [Relay.Mesos](https://github.com/sailthru/relay.mesos)
* [Ochopod](https://github.com/autodesk-cloud/ochopod)
* [Mesos on Mesos](https://github.com/mesosphere/mom)
* [Load replaying](https://github.com/stealthly/punxsutawney)
* [Vamp](https://github.com/magneticio/vamp)
* [Dispatch - execute scripts on Mesos cluster](https://github.com/mesosphere/dispatch)
* [Charmander](https://github.com/att-innovate/charmander)
* [Compose-executor](https://github.com/mohitsoni/compose-executor)
* [Triathlon - Marathon wrapper for distributed Mesos cluster selection](https://github.com/schibsted/triathlon)
* [megos - Go(lang) client library for accessing information of a Apache Mesos cluster](https://github.com/andygrunwald/megos)
* [Weave Mesos Integration](https://github.com/TrentBrown/weave-into-mesos)
* [OpenStack Kolla](https://github.com/openstack/kolla-mesos)
* [Chimp](https://github.com/zalando-techmonkeys/chimp)
* [Depcon](https://github.com/gondor/depcon)
* [Vault](https://github.com/jmspring/vault-on-mesos)
* [Go Mesos Kafka Consumer](https://github.com/elodina/gonzo)
* [Apache Mesos Platform as a Service Deploy](https://github.com/elodina/stack-deploy)
* [JIRA on Mesos](https://github.com/elodina/mesos-jira)
* [Dask Mesos backend](https://github.com/lensacom/dask.mesos)
* [Spring Cloud Data Flow](https://github.com/spring-cloud/spring-cloud-dataflow-server-mesos)
* [Nix](https://github.com/kamilchm/nix-mesos)
* [RogerOS](https://github.com/seomoz/roger-mesos-tools)
* [TradeCloud](https://github.com/tradecloud/tradecloud-microservices)

##Where to look for more?

* [MesosCon](http://mesoscon.org) Videos - [2014](https://www.youtube.com/playlist?list=PLDVc2EaAVPg9kp8cFzjR1Yxj96I4U5EGN), [2015](https://www.youtube.com/playlist?list=PLVjgeV_avap2arug3vIz8c6l72rvh9poV), [Europe 2015](https://www.youtube.com/watch?v=K-x7yOy8Ymk&list=PLGeM09tlguZS6MhlSZDbf-gANWdKgje0I), [Seattle 2015](https://www.youtube.com/watch?v=aV6pdWveN7s&list=PLVjgeV_avap2arug3vIz8c6l72rvh9poV), [North America 2016](https://www.youtube.com/playlist?list=PLGeM09tlguZQVL7ZsfNMffX9h1rGNVqnC)
* [Mesos User Groups](http://mesos.apache.org/community/user-groups/)
* [Powered By Mesos](http://mesos.apache.org/documentation/latest/powered-by-mesos/)
* [Mesos Community](http://mesos.apache.org/community/)
* [List of Mesos related conferences & meetups](https://github.com/parolkar/awesome-mesos#related-conferences--meetups)
* [Apache Mesos Essentials book](http://dharmeshkakadia.blogspot.com/2015/06/apache-mesos-essential-is-now-available.html)
