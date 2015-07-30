awesome-mesos
=============

Everything about awesome [Apache Mesos](http://mesos.apache.org/). 

Share your Mesos :heart: through pull requests :)

What can you expect to see here?

* [Frameworks](#frameworks)
* [Language Bindings](#language-bindings)
* [Tools](#tools)
* [Deployment](#deployment)
* [Other Projects](#other-projects)
* [Version compatibility](#version-compatibility)
* [Where to look for more?](#where-to-look-for-more)

##Frameworks

###Data Processing

####Batch Processing
* [Apache Spark](https://spark.apache.org/docs/latest/running-on-mesos.html)
* [Apache Hadoop](https://github.com/mesos/hadoop)
* [Apache Hama](http://wiki.apache.org/hama/GettingStartedMesos)
* [Dpark](https://github.com/douban/dpark)

####Stream Processing
* [Apache Storm](https://github.com/mesos/storm)
* [Samza](https://github.com/Banno/samza-mesos)

####Storage and Serving
* [Apache Cassandra](https://github.com/mesosphere/cassandra-mesos)
* [ArangoDB](https://github.com/fceller/arangodb-mesos)
* [Hypertable](https://code.google.com/p/hypertable/wiki/Mesos)
* [ElasticSearch](https://github.com/mesosphere/elasticsearch-mesos)
* [Tachyon](https://github.com/mesosphere/tachyon-mesos)
* [HDFS](https://github.com/mesosphere/hdfs) (and [HDFS](https://github.com/brugidou/hdfs-mesos) and [HDFS](https://github.com/brndnmtthws/hdfs))
* [Riak](https://github.com/edpaget/riak-mesos)
* [Apache Kafka](https://github.com/stealthly/kafka-mesos)
* [Mysos - MySQL on Mesos](https://wiki.apache.org/incubator/MysosProposal)
* [MongoDB](https://github.com/massenz/mongo_fw)
* [Hemlock](https://github.com/spacejam/hemlock)
* [Apache Drill](https://github.com/mhausenblas/dromedar)
* [Ceph](https://github.com/Intel-bigdata/ceph-mesos)

###Service/Meta Schedulers
* [Apache Aurora](http://aurora.incubator.apache.org/)
* [Marathon](https://github.com/mesosphere/marathon)
* [Singularity](https://github.com/HubSpot/Singularity)
* [Chronos](https://github.com/mesos/chronos)
 
###Consensus 
* [ZooKeeper](https://github.com/CiscoCloud/exhibitor-mesos-framework)

###Continuous Integration
* [Jenkins](https://github.com/jenkinsci/mesos-plugin)
* [GitLab CI](https://github.com/deric/gitlab-ci-mesos)
* [Teamcity Plugin](https://github.com/ankurcha/mesos-teamcity-plugin)

###Experimental/Example/Unsorted

* [distcc](https://github.com/mesos/mesos-distcc)
* [Exelixi](https://github.com/ceteri/exelixi)
* [MPI](https://github.com/mesosphere/mesos-hydra)
* [Chapel Parallel Programming Language](https://github.com/nqn/mesos-chapel)
* [SSSP](https://github.com/mesosphere/sssp)
* [Torque](https://github.com/apache/mesos/tree/master/frameworks/torque)
* [HAProxy+Webserver](https://github.com/apache/mesos/tree/master/frameworks/deploy_jar)
* [Mesos-submit](https://github.com/apache/mesos/tree/master/frameworks/mesos-submit)
* [Deploy Jar](https://github.com/apache/mesos/tree/master/frameworks/deploy_jar)
* [JobServer](http://www.grandlogic.com/content/html_docs/products.shtml#jobserverprod)
* [RENDLER](https://github.com/mesosphere/RENDLER)
* [OwlCrawler](https://github.com/fmpwizard/owlcrawler)
* [Kubernetes](https://github.com/mesosphere/kubernetes-mesos)
* [Tryant - Distributed job scheduler in go](https://github.com/wandoulabs/tyrant)
* [Volt](https://github.com/VoltFramework/volt)
* [Myriad - Elastic YARN clusters on Mesos](https://github.com/mesos/myriad)
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

###Dysfunctional
* [Deimos](https://github.com/mesosphere/deimos) (deprecated when native [Docker support](http://mesos.apache.org/documentation/latest/docker-containerizer/) was added to Mesos v0.20)
* [Slurm](https://github.com/nqn/slurm-mesos)

## Language Bindings

* C/C++
* [Java](http://mesos.apache.org/api/latest/java/)
* Pure java - [Jesos](https://github.com/groupon/jesos)
* Pure JVM - https://github.com/kevints/mesos-framework-api
* Python
* Pure Python - [Pesos](https://github.com/wickman/pesos)
* Pure Python - [Pymesos](https://github.com/dangra/pymesos)
* [Go](https://github.com/mesos/mesos-go)
* Pure go - [Gomes](https://github.com/vladimirvivien/gomes)
* [Erlang](https://github.com/mdevilliers/erlang-mesos) with [example frmaework](https://github.com/mdevilliers/merkxx)
* [Haskell](https://github.com/iand675/hs-mesos)
* [Clojure](https://github.com/dgrnbrg/clj-mesos) and [mesomatic](https://github.com/pyr/mesomatic)
* [NodeJS](https://github.com/silas/node-mesos)
* [JS](https://github.com/topology-io/mesos-js)
* [Ruby](https://github.com/burke/mesos-ruby)
* [Perl](https://github.com/mark-5/perl-mesos)
* [Rust](https://github.com/ConnorDoyle/resos)

##Tools

###Tools for Mesos Developers
* https://github.com/tillt/xcode-mesos
* https://github.com/mesos/modules

###Tools for Mesos Framework Developers
* https://github.com/mesosphere/scala-sbt-mesos-framework.g8
* https://github.com/mesosphere/akka-mesos
* https://github.com/drexin/akka-mesos
* Simple Mesos "Hello world" in scala - https://gist.github.com/guenter/7471695
* [Mesos State Backed Collections](https://github.com/mesosphere/mesos-state-backed-collections)
* [mini-mesos - Testing infrastructure for Mesos frameworks](https://github.com/containersolutions/mini-mesos)

###Vagrant based setups
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
* https://github.com/yaronr/docker-mesos
* https://github.com/breerly/fig-mesos
* https://github.com/redjack/docker-mesos

###Visualization
* [Visualize Mesos traces](https://github.com/tnachen/mesos_traces_vis)

##Deployment 

###Ansible
* https://github.com/mhamrah/ansible-mesos-playbook
* https://github.com/fupelaqu/ansible-mesos
* https://github.com/frankhinek/ansible-mesos-cluster
* https://github.com/curtisgithub/ansible-mmd
* https://github.com/AnsibleShipyard/ansible-mesos
* https://github.com/AnsibleShipyard/ansible-mesos
* https://github.com/AnsibleShipyard/ansible-mesos-docker
* https://github.com/AnsibleShipyard/ansible-chronos
* https://github.com/AnsibleShipyard/ansible-marathon
* [Deploy apps on marathon from ansible](https://github.com/Topface/ansible-marathon_app)

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

###Packaging
* https://github.com/nmilford/rpm-mesos
* https://github.com/berngp/mesos-rpm
* https://github.com/deric/mesos-deb-packaging
* https://github.com/mesosphere/mesos-deb-packaging

###Monitoring
* https://github.com/opentable/nagios-mesos
* https://github.com/bobrik/collectd-mesos-tasks and (https://github.com/rayrod2030/collectd-mesos and its dockerized version - https://github.com/bobrik/docker-collectd-mesos)
* [Plot Marathon Metrics](https://github.com/topology-io/marathon-metrics-watcher)
* [Satellite](https://github.com/twosigma/satellite)
* [Prometheus](https://github.com/prometheus/mesos_exporter) and [Prometheus](https://github.com/wndhydrnt/mesos-task-exporter)

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

### Modules
* [A customer allocator module](https://github.com/stealthly/alligator)
* [Serenity](https://github.com/mesosphere/serenity)
* [Metaswitch](https://github.com/mesosphere/metaswitch-modules)

##Other projects
* [BigDataScript](https://github.com/pcingola/BigDataScript)
* [Apollo](https://github.com/Capgemini/Apollo)
* https://github.com/mesosphere/sample_mesos_executor
* https://github.com/CloudCredo/mesos-boshrelease
* https://github.com/cf-platform-eng/mesos-boshrelease
* https://github.com/riywo/sample-fluentd-on-mesos-docker
* https://github.com/mesosphere/mesos-utils
* https://github.com/mesosphere/mesos-cli
* https://github.com/opentable/mesoshub
* https://github.com/thefactory/marathon-python
* https://github.com/thefactory/marathon-logger
* https://github.com/mesosphere/marathon_client
* https://github.com/mesosphere/service-bridge
* https://github.com/mesosphere/marathon-pkg
* https://github.com/jbdalido/gomarathon
* https://github.com/mesosphere/chronos-pkg
* https://github.com/mesosphere/chronos-utils
* [Mesos in Hadoop](https://github.com/mesos/mih)
* [CDH patched for Mesos](https://github.com/mesos/cdh-mesos) - old
* https://github.com/siliconcow/docker_paas - old
* https://github.com/trampoline/clustermap-mesos
* https://github.com/jbdalido/hecate
* https://github.com/outbrain/onering-report-mesos
* https://github.com/nlamirault/magneto
* https://github.com/klueska/mesos-akaros and https://github.com/alfongj/mesos-akaros
* https://github.com/nicostratus/mesos-services [defunct]
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
* https://github.com/obaidsalikeen/storm-marathon
* Aurora REST interface - https://github.com/misho-kr/mesos-aurora-restful and https://github.com/smarth-madan/incubator-aurora
* [Global Microservice Architecture](https://github.com/CiscoCloud/microservices-infrastructure)
* [Storm Marathon](https://github.com/obaidsalikeen/storm-marathon)
* https://github.com/tailhook/mesos-tests
* https://github.com/nlamirault/magneto
* [REPL-MESOS](https://github.com/replme/repl-mesos)
* [Relay.Mesos](https://github.com/sailthru/relay.mesos)
* [Ochopod](https://github.com/autodesk-cloud/ochopod)
* [Mesos on Mesos](https://github.com/mesosphere/mom)
* [Load replaying](https://github.com/stealthly/punxsutawney)
* [Vamp](https://github.com/magneticio/vamp)
* [Dispatch - execute scripts on Mesos cluster](https://github.com/mesosphere/dispatch)


##Version compatibility 
Which version of framework works with which version of Mesos?
(Note that this information is only coming from documentation/release notes of the coressponding projects. Most projects are _likely_ to work with latest versions of Mesos just fine, unless stated otherwise)

|Framework\Mesos | 0.21 | 0.20 | 0.19 | 0.18 | 0.17 | 0.16 |
|----------------|:-----|:-----|:-----|:-----|:-----|:-----|
|Spark           | 1.4, 1.3  |      |      | 1.2  |      |      | 

##Where to look for more?

* [MesosCon 2014 Videos](https://www.youtube.com/playlist?list=PLDVc2EaAVPg9kp8cFzjR1Yxj96I4U5EGN)
* [Mesos User Groups](http://mesos.apache.org/community/user-groups/)
* [Powered By Mesos](http://mesos.apache.org/documentation/latest/powered-by-mesos/)
* [Mesos Community](http://mesos.apache.org/community/)
* [List of Mesos related conferences & meetups](https://github.com/parolkar/awesome-mesos#related-conferences--meetups)
* [Mesos Blog posts](http://planet.apache.org/mesos/)
* [Apache Mesos Essentials book](http://dharmeshkakadia.blogspot.com/2015/06/apache-mesos-essential-is-now-available.html)
