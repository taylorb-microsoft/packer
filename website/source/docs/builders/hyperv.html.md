---
layout: "docs"
page_title: "Hyper-V Builder"
description: |-
  The Hyper-V Packer builder is able to create Hyper-V virtual machines and export them.
---

# Hyper-V Builder

The Hyper-V Packer builder is able to create [Hyper-V](https://www.microsoft.com/en-us/server-cloud/solutions/virtualization.aspx)
virtual machines and export them.

Packer currently only support building Hyper-V machines with an iso:

* [hyper-v-iso](/docs/builders/hyperv-iso.html) - Starts from
  an ISO file, creates a brand new HyperV VM, installs an OS,
  provisions software within the OS, then exports that machine to create
  an image. This is best for people who want to start from scratch.
