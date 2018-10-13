---
description: You can install on Greenplum on these platforms
---

# Install Greenplum

## Use Docker

GPDB 4.3.x :  Use preinstalled docker image:

```
$ docker pull pivotaldata/gpdb-base 
```

{% hint style="info" %}
 This docker file contains Greenplum 4.3.x version
{% endhint %}

GPDB 5.x: Use preinstalled docker image:

```
$ docker pull kochanpivotal/gpdb5oss
```

{% hint style="info" %}
 This docker file contains Greenplum 5.x version
{% endhint %}

## Use RedHat/Centos

1. Download Greenplum files from Pivotal Network
2. Install Greenplum on RedHat/Centos

{% hint style="info" %}
 This process takes time to install and configure Greenplum
{% endhint %}

## Use Mac

Use brew to install Greenplum:

```
$ brew install greenplum-db/tap/greenplum-db
```

Note: Is it still working ? 



