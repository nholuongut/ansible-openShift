# OpenShift Ansible
![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

This repository contains [Ansible](https://www.ansible.com/) roles and
playbooks to install, upgrade, and manage
[OpenShift](https://www.openshift.com/) clusters.

**Note**: the Ansible playbooks in this repository require an RPM
package that provides `docker`. Currently, the RPMs from
[dockerproject.org](https://dockerproject.org/) do not provide this
requirement, though they may in the future. This limitation is being
tracked by
[#2720](https://github.com/openshift/openshift-ansible/issues/2720).

## Getting the correct version

The
[master branch](https://github.com/openshift/openshift-ansible/tree/master)
tracks our current work **in development** and should be compatible
with the
[Origin master branch](https://github.com/openshift/origin/tree/master)
(code in development).

In addition to the master branch, we maintain stable branches
corresponding to upstream Origin releases, e.g.: we guarantee an
openshift-ansible 3.2 release will fully support an origin
[1.2 release](https://github.com/openshift/openshift-ansible/tree/release-1.2).
The most recent branch will often receive minor feature backports and
fixes.  Older branches will receive only critical fixes.

**Getting the right openshift-ansible release**

Follow this release pattern and you can't go wrong:

| Origin/OCP    | OpenShift-Ansible version | openshift-ansible branch |
| ------------- | ----------------- |----------------------------------|
| 1.3 / 3.3          | 3.3               | release-1.3 |
| 1.4 / 3.4          | 3.4               | release-1.4 |
| 1.5 / 3.5          | 3.5               | release-1.5 |
| 3.*X*         | 3.*X*             | release-3.x |

If you're running from the openshift-ansible **master branch** we can
only guarantee compatibility with the newest origin releases **in
development**. Use a branch corresponding to your origin version if
you are not running a stable release.


## Setup

1. Install base dependencies:

    ***

    Requirements:
    - Ansible >= 2.3.0.0
    - Jinja >= 2.7
    - pyOpenSSL
    - python-lxml

    ***

    Fedora:
    ```
    dnf install -y ansible pyOpenSSL python-cryptography python-lxml
    ```

2. OpenShift Installation Documentation:

    - [OpenShift Enterprise](https://docs.openshift.com/enterprise/latest/install_config/install/advanced_install.html)
    - [OpenShift Origin](https://docs.openshift.org/latest/install_config/install/advanced_install.html)

## Containerized OpenShift Ansible

See [README_CONTAINER_IMAGE.md](README_CONTAINER_IMAGE.md) for information on how to package openshift-ansible as a container image.

## Installer Hooks

See the [hooks documentation](HOOKS.md).

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
