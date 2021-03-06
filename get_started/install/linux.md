## Requirements

- Hypervisor: at least one of
  - [Linux] QEMU 2.0 or later
  - [Linux] Xen 4.5 or later (for Xen support)

## Install

[the current version](../../release_notes/latest.md) supports the following Linux distros:

- Ubuntu ( > 14.04 )
- CentOS/RHEL 7.x
- Fedora ( > 20 )
- Debian ( > 7.0 )

### curl-to-bash or tarball

To setup Hyper, simply run (after 0.4, the same package support both
  KVM and Xen)

    curl -sSL https://hypercontainer.io/install | bash

Don't like the "curl to bash" methods? Download [tarball here](https://hypercontainer-install.s3.amazonaws.com/hyper-latest.tgz).

For CentOS/RHEL users, please use the pre-build RPMs

If you build Qemu from source, don't forget enable virtfs (`--enable-virtfs`) during configuration.

### RPMs for CentOS/RHEL7

x86_64 binary packages:

> - [hyper-container-0.7.0-1.el7.centos.x86_64.rpm](https://hypercontainer-install.s3.amazonaws.com/hyper-container-0.7.0-1.el7.centos.x86_64.rpm)
> -  [hyperstart-0.7.0-1.el7.centos.x86_64.rpm](https://hypercontainer-install.s3.amazonaws.com/hyperstart-0.7.0-1.el7.centos.x86_64.rpm)
> - [qemu-hyper-2.4.1-2.el7.centos.x86_64.rpm](https://hypercontainer-install.s3.amazonaws.com/qemu-hyper-2.4.1-2.el7.centos.x86_64.rpm)

and SRPMS:

> - [hyper-container-0.7.0-1.el7.centos.src.rpm](https://hypercontainer-install.s3.amazonaws.com/hyper-container-0.7.0-1.el7.centos.src.rpm)
> - [hyperstart-0.7.0-1.el7.centos.src.rpm](https://hypercontainer-install.s3.amazonaws.com/hyperstart-0.7.0-1.el7.centos.src.rpm)
> - [qemu-hyper-2.4.1-2.el7.centos.src.rpm](https://hypercontainer-install.s3.amazonaws.com/qemu-hyper-2.4.1-2.el7.centos.src.rpm)

## RPMs for Fedora 23

x86_64 binary packages:

> - [hyper-container-0.7.0-1.fc23.x86_64.rpm](https://hypercontainer-install.s3.amazonaws.com/hyper-container-0.7.0-1.fc23.x86_64.rpm)
> - [hyperstart-0.7.0-1.fc23.x86_64.rpm](https://hypercontainer-install.s3.amazonaws.com/hyperstart-0.7.0-1.fc23.x86_64.rpm)

and SRPMS:

> - [hyper-container-0.7.0-1.fc23.src.rpm](https://hypercontainer-install.s3.amazonaws.com/hyper-container-0.7.0-1.fc23.src.rpm)
> - [hyperstart-0.7.0-1.fc23.src.rpm](https://hypercontainer-install.s3.amazonaws.com/hyperstart-0.7.0-1.fc23.src.rpm)

> *Note*: The qemu shipped in Fedora could work well with Hyper, we did not package qemu for Fedora.

## Deb packages for Ubuntu

Binary packages for `amd64`:

> - [hypercontainer_0.7.0-2_amd64.deb](https://s3-us-west-1.amazonaws.com/hypercontainer-install/hypercontainer_0.7.0-2_amd64.deb)
> - [hyperstart_0.7.0-1_amd64.deb](https://s3-us-west-1.amazonaws.com/hypercontainer-install/hyperstart_0.7.0-1_amd64.deb)
