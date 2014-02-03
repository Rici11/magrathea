Magrathea

## About
>Magrathea. Will be the planet where your Apps become Web Services!


It stays on top of a Puppet-Based infrastructure comprised of a bunch of VM hosts grouped in clusters of Ubuntu servers as an API and a Command-Line Client.

It will be initially developed to meet our internal needs for infrastructure orchestration and the first release will not have all the planned features. What we are developing will not be just another Docker-PaaS spinoff.
Currently we have several clusters based on a customized IspConfig control panel, the aim of the initial release of Magrathea will be to manage all the hosts inside those clusters.

### Magrathea v1 will:

1. Let you configure your App to run on multiple clusters. With all Apps having a similar, but unique configuration on each of them.
2. Allow you basic access to shells and logs on the Clusters that are being managed.
3. Provide you with basic resource accounting designed for multi-tenant environments: Disk Space and Web Traffic.
4. Allow you to manage Apps based on the classic LAMP Stack, with the addition of Varnish and HAProxy that will stay in front of Apache.
5. Provide us with a chance to learn how to create Cloud Ready Apps with Continuous Integration and Continuous Deployment.

### Magrathea v1 will NOT:

1. Manage dynamic clusters and will not handle Auto Scaling functions.
2. Be launched on the fly as all configuration will be all statically pre defined.

### Magrathea v2 ?

Version 1 is not an all encopassing and huge project, our hope is that many opensource projects currently [under](http://flynn.io) [heavy](http://reverbrain.com/cocaine/) [development](https://github.com/unbit/uwsgi.it) will bring to us a ready-to-use PaaS, docker and ReST based, with resource accounting and scaling and so on... If this will not happen, we will develop v2 :-)

## Glossary:

* an `app`: is an application defined by a name, made up of source code and stack configuration
* an `instance`
* an `environment`

### Copyright

Magrathea is mainly ispired by all the platforms I tried or read about:
 * [dotcloud](http://docs.dotcloud.com/firststeps/how-it-works/)
 * [pagodabox](http://help.pagodabox.com/customer/portal/articles/175475)
 * [fortrabbit](http://fortrabbit.com/docs/essentials/platform-overview)
 * [flynn](https://github.com/flynn/flynn-guide/blob/master/ARCHITECTURE.md)

### Service layers

### IspConfig2 integrations points

### Basic developer workflow

### Multiple configurations for the same app

### Deployment phases

### Cluster Layers



