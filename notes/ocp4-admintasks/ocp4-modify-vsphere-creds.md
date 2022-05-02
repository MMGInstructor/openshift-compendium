---
title: Modify vSphere Credentials
tags:
  - Openshift 4
  - VMWare
emoji: "\U0001F4BE"
link: 'https://access.redhat.com/solutions/4618011'
created: 2020-06-14T03:17:19.000Z
modified: 2020-09-22T13:49:21.000Z
---

How to modify vsphere credentials in Openshift 4 after the cluster has been created. A full explanation is available in the solution linked above, this article also covers changing the default datastore.

> You will need `cluster-admin` to edit these credentials

* `oc project kube-system`
* Execute `oc edit secret vsphere-creds -n kube-system`

These credentials are base64 encoded. Here's a quick reminder of how to encode and decode base64.

```
$ echo -n "test" | base64 -w0
dGVzdA==

$ base64 -d <<< dGVzdA==
test
```
