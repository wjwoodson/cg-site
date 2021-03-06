---
menu:
  docs:
    parent: apps
title: Languages and frameworks
weight: 29
aliases:
- /docs/apps/django
- /docs/apps/flask
- /docs/apps/rails
- /docs/apps/node
- /docs/apps/meteor
---

cloud.gov uses [buildpacks]({{< relref "docs/getting-started/concepts.md#buildpacks" >}}) to support a variety of programming languages and frameworks.

## Supported languages and frameworks

cloud.gov supports applications written in Go, Java, Node.js, .NET Core, PHP, Python, and Ruby. cloud.gov also supports applications that rely on a static binary that uses the 64-bit Linux kernel ABI, or that consist of static HTML, CSS, and Javascript assets. See the [Cloud Foundry system (supported) buildpacks list](http://docs.cloudfoundry.org/buildpacks/#system-buildpacks) for details.

## Examples

You can deploy example applications in many languages and frameworks:

* [Hello worlds](https://github.com/18F/cf-hello-worlds): Java, Clojure, NodeJS, PHP, Flask (Python), Padrino (Ruby), Sinatra (Ruby)
* [Drupal](https://github.com/18F/cf-ex-drupal)
* [Cloud Foundry community sample applications](https://github.com/cloudfoundry-samples)

## Other languages

You can use a custom buildpack to support other languages. See [custom buildpacks]({{< relref "docs/apps/custom-buildpacks.md" >}}) for more information about this feature.

Cloud Foundry has a list of [community buildpacks](http://docs.cloudfoundry.org/buildpacks/#community-buildpacks) that you can use as custom buildpacks, along with [documentation for building your own custom buildpacks](http://docs.cloudfoundry.org/buildpacks/developing-buildpacks.html).

## Cannot run

cloud.gov cannot run applications that use .NET Framework, or application binaries that require access to Microsoft Windows kernel or system APIs.
