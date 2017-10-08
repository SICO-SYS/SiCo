## SiCo

[![gittter](http://tool.lu/shield/ajax.html?color=%23400090&subject=gitter&status=SiCo)](https://gitter.im/SiCo-DevOps/Freedom)
[![slack](http://tool.lu/shield/ajax.html?color=%23400090&subject=slack&status=SiCo)](https://sico-ops.slack.com/)

### LICENSE  = [MIT License](https://github.com/SiCo-Ops/SiCo/blob/master/LICENSE)

### WHAT IS SiCo
  - SiCo is an intelligence operation platform for DevOps。
  - SiCo just an API so everyone can make a self UI.
  - SiCo takes jos simple and easy
  - SiCo helps you save more time to accompany your family。 

### THIRD-PARTY SERVICE
  - we use travis-ci to do CI,CD for initial，but we'll take it by this API.
  - we use gitter.im to communicate with users, a public annoncement platform.
  - we use slack to communicate with every developer who want to be a contributor.
  - we use sentry.io to know what problem in sico, find bugs easy.
  - we use new relic to track our API performance.
  - we use [jira](https://sico-ops.atlassian.net) to assign tasks & arrange the release planning.

### HOW TO REPORT AN ISSUE
  * Open an issue on relate project
  * Tell us the issue's link on gitter.im if you want to quickly get the feedback
  * We are glad to you can open a pull request to us to fix the issue. 

### QUICK START WITH DOCKER SWARM
- `docker network create -d overlay --subnet 192.168.0.0/16 sico`
- `docker service create --name redis-config --hostname redis-config --replicas 1 --network sico redis`
- `docker service create --name redis-public --hostname redis-public --replicas 1 --network sico redis`
- `docker service create --name mongo-user --hostname mongo-user --replicas 1 --network sico mongo`
- `docker service create --name mongo-cloud --hostname mongo-cloud --replicas 1 --network sico mongo`
- `docker service create --name mongo-asset --hostname mongo-asset --replicas 1 --network sico mongo`
- `docker service create --name boron  --replicas 1 --network sico sinerwr/boron:stable-1.0.4`
- `docker service create --name hydrogen --publish 80:2048  --replicas 1 --network sico sinerwr/hydrogen:stable-1.0.4`
- `docker service create --name helium  --replicas 1 --network sico sinerwr/helium:stable-1.0.4`
- `docker service create --name lithium  --replicas 1 --network sico sinerwr/lithium:stable-1.0.4`
- `docker service create --name beryllium  --replicas 1 --network sico sinerwr/beryllium:stable-1.0.4`

### SiCo elements

#### H [Go to Project](https://github.com/SiCo-Ops/H)

[![Build Status](https://travis-ci.org/SiCo-Ops/H.svg?branch=master)](https://travis-ci.org/SiCo-Ops/H)
[![gittter](http://tool.lu/shield/ajax.html?color=%23400090&subject=gitter&status=Hydrogen)](https://gitter.im/SiCo-DevOps/Hydrogen)

H is short for Hydrogen, element handle all http requests and guide to other elements.

#### He [Go to Project](https://github.com/SiCo-Ops/He)

[![Build Status](https://travis-ci.org/SiCo-Ops/He.svg?branch=master)](https://travis-ci.org/SiCo-Ops/He)
[![gittter](http://tool.lu/shield/ajax.html?color=%23400090&subject=gitter&status=Helium)](https://gitter.im/SiCo-DevOps/Helium)

He is short for Helium, element receive Authentication,Authorization,Accounting requests.

#### Li [Go to Project](https://github.com/SiCo-Ops/Li)

[![Build Status](https://travis-ci.org/SiCo-Ops/Li.svg?branch=master)](https://travis-ci.org/SiCo-Ops/Li)
[![gittter](http://tool.lu/shield/ajax.html?color=%23400090&subject=gitter&status=Lithium)](https://gitter.im/SiCo-DevOps/Lithium)

Li is short for Lithium, element receive third party cloud requests like Amazon Web Service , Aliyun , Qcloud etc.

#### Be [Go to Project](https://github.com/SiCo-Ops/Be)

[![Build Status](https://travis-ci.org/SiCo-Ops/Be.svg?branch=master)](https://travis-ci.org/SiCo-Ops/Be)
[![gittter](http://tool.lu/shield/ajax.html?color=%23400090&subject=gitter&status=Beryllium)](https://gitter.im/SiCo-DevOps/Beryllium)

Be is short for Beryllium, element receive asset requests to manage resources from public cloud, private cloud, physical servers etc.

#### B [Go to Project](https://github.com/SiCo-Ops/B)

[![Build Status](https://travis-ci.org/SiCo-Ops/B.svg?branch=master)](https://travis-ci.org/SiCo-Ops/B)
[![gittter](http://tool.lu/shield/ajax.html?color=%23400090&subject=gitter&status=Boron)](https://gitter.im/SiCo-DevOps/Boron)

B is short for Boron, element receive requests to store and access configs.

#### C [Go to Project](https://github.com/SiCo-Ops/C)

[![Build Status](https://travis-ci.org/SiCo-Ops/C.svg?branch=master)](https://travis-ci.org/SiCo-Ops/C)
[![gittter](http://tool.lu/shield/ajax.html?color=%23400090&subject=gitter&status=Carbon)](https://gitter.im/SiCo-DevOps/Carbon)

C is short for Carbon, element automatically execute schedule planning tasks , call other elements to record results which need.  

#### N [Go to Project](https://github.com/SiCo-Ops/N)

[![Build Status](https://travis-ci.org/SiCo-Ops/N.svg?branch=master)](https://travis-ci.org/SiCo-Ops/N)
[![gittter](http://tool.lu/shield/ajax.html?color=%23400090&subject=gitter&status=Nitrogen)](https://gitter.im/SiCo-DevOps/Nitrogen)

N is short for Nitrogen, element orchestrate tasks that how to complete all of the jobs.

### DONATE

[![Donate](http://tool.lu/shield/ajax.html?color=%234C1&subject=Paypal&status=$1)](https://paypal.me/sinerwr/1)
[![Donate](http://tool.lu/shield/ajax.html?color=%234C1&subject=Paypal&status=$5)](https://paypal.me/sinerwr/5)
[![Donate](http://tool.lu/shield/ajax.html?color=%234C1&subject=Paypal&status=$10)](https://paypal.me/sinerwr/10)

YOU CAN ALSO GIVE A DONATE TO SUPPORT THIS PROJECT.
