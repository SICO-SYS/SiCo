### 1.0.5 Fixing
- when public token is not exist, errcode is wrong , 101 -> 8
- add testing and benchmark testing.

### 1.0.4 Emergency Fixed 2017.10.04
- swarm use DNS for communication
- swarm cannot use one word for --name , so use long name for every element
- H changed to hydrogen
- He changed to helium
- Li changed to lithium
- Be changed to beryllium
- B changed to boron
- docker hub automatically build also change the name.

### 1.0.3 Fixed 2017.09.30
- H Dockerfile add `mv *.json $GOPATH/bin` to take json config affect. 

### 1.0.2 Fixed 2017.09.30
- read configs from element B first, and read local config file if B has no response.
- if use local config file, must have all of the config according to cfg struct.

### 1.0.1 Fixed 2017.09.29
- move gRPC connections to dao/grpc, prompt public functions.
- use token service instead of public & private service.

### 1.0.0 Released 2017.09.28
- generate public token
- request AWS, aliyun, qcloud for this platform
- manage config easy