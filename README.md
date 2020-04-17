# Workflow

There are many workflows that customers can design.

1. have a root gitrepo bootstrapper project that has the manifests that adds a gitrepo channel with the subscription target as local-cluster
2. this repo should be organized by the namespaces that the mcm application projects will deploy.

bootstrap-gitrepo-root
  /bootstrap-gitrepo
    channel.yaml
    subscription.yaml to local-cluster

gitrepo-root
  /bookinfo
  /bookinfo-project
  /bookinfo-entitlemen
  /mcm-policy

#### versions
1.0.9 no apis  
2.0.3 with apis  
2.1.1, 2.1.2, 2.1.3  
reivews-v1, reviews-v2, reviews-v3  