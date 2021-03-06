---
layout: post
author: fabiand
description: This is the seventh weekly update from the KubeVirt team.
navbar_active: Blogs
pub-date: October 24
pub-year: 2017
category: updates
comments: true
---

This is the seventh weekly update from the KubeVirt team.

This week you can read more or speak to us at:

-   KVM Forum, Prague Thursday, October 26, 10:00 - 10:45
    <https://kvmforum2017.sched.com/event/BnoA>

-   "KubeWHAT?" by S Gordon - On KubeVirt and OpenStack (past event)
    <https://www.slideshare.net/sgordon2/kubewhat>

<!-- more -->
We are currently driven by

-   Being easier to be used on Kubernetes and OpenShift

-   Enabling people to contribute

-   Node Isolator use-case (more informations soon)

This week we achieved to:

-   VMs and components are now running in the host pid namespace
    (@dvossel) <https://github.com/kubevirt/kubevirt/pull/506>

-   Move dependency management from glide to dep ()
    <https://github.com/kubevirt/kubevirt/pull/511>

-   Add a leader election mechanism to virt-controller (@)
    <https://github.com/kubevirt/kubevirt/pull/461>

-   Add OpenAPI specification (@)
    <https://github.com/kubevirt/kubevirt/pull/494>

-   Put work on api server aggregation on hold for now (@stu-gott) To be
    resolved: API server storage
    (<https://github.com/kubevirt/kubevirt/pull/355>)

In addition to this, we are also working on:

-   Finalization of pod networking (@vladikr)
    (<https://github.com/kubevirt/kubevirt/pull/525>)

-   Access to the node control network (@rmohr)
    (<https://github.com/kubevirt/kubevirt/pull/499>)

-   Custom VM metrics discussion (@fromanirh)
    (<https://github.com/kubevirt/kubevirt/pull/487>)

-   Simple persistence mechanism (@petrkotas)
    (<https://github.com/petrkotas/virt-vmconfig-crd/>)

Take a look at the pulse, to get an overview over all changes of this
week: <https://github.com/kubevirt/kubevirt/pulse>

Finally you can view our open issues at
<https://github.com/kubevirt/kubevirt/issues>

And keep track of events at our calendar
[18pc0jur01k8f2cccvn5j04j1g@group.calendar.google.com](https://calendar.google.com/embed?src=<link xl:href=)"&gt;https://calendar.google.com/embed?src=<18pc0jur01k8f2cccvn5j04j1g@group.calendar.google.com>&lt;/link&gt;

If you need some help or want to chat you can find us on
<irc://irc.freenode.net/#kubevirt>
