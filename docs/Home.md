Medusa
======

Medusa is an Apache Cassandra backup system.

Features
--------
Medusa is a command line tool that offers the following features:

* Single node backup
* Single node restore
* Cluster wide in place restore (restoring on the same cluster that was used for the backup)
* Cluster wide remote restore (restoring on a different cluster than the one used for the backup)
* Backup purge
* Support for local storage, Google Cloud Storage (GCS) and AWS S3 through [Apache Libcloud](https://libcloud.apache.org/). Can be extended to support other storage providers supported by Apache Libcloud.
* Support for clusters using single tokens or vnodes
* Full or differential backups

Medusa currently does not support (but we would gladly accept help with changing that):

* Cassandra deployments with multiple data folder directories.

Documentation
-------------
* [Installation](Installation.md)
* [Configuration](Configuration.md)
* [Usage](Usage.md)