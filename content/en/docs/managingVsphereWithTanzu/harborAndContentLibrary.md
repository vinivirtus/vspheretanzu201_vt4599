---
title: "Harbor and the Content Library"
date: 2020-10-12T18:35:13-07:00
weight: 3015
---
### Registry Service

The Registry Service is one of the Cloud Foundation services provided by vSphere with Tanzu. You can enable a private image registry on a Supervisor Cluster using the Registry Service. Enabling the Registry Service will deploy an instance of Harbor on the cluster. All Namespaces created on a Supervisor Cluster are represented as projects in the private registry and appropriate RBAC is configured based on the permissions of the Namespace object.

### Content Library

The virtual machine images used to deploy Tanzu Kubernetes Grid cluster on vSphere with Tanzu are sourced from a public content delivery network (CDN).  vSphere with Tanzu uses a subscribed Content Library to automatically download and synchronize new versions of the TKG virtual machine image and corresponding Kubernetes releases.

{{< youtube wzegdUYnttU >}}