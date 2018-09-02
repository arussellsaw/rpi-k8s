# arussellsaw's raspberry pi kubernetes cluster

initially this repo is going to be tracking my progress and saving utilities, eventually i'd like to turn it into a proper guide and resource center.

#### Setup

for my initial setup i followed the @alexellis tutorial, with a few key changes. i ended up using kubernetes 1.8.3, and the flannel overlay network, this is due to issues with the more recent releases of kubernetes and weave. hopefully when fixes are implemented this will change.

#### Workloads

* nsqd/nsqlookupd/nsqadmin

* openfaas

