===========================
Dela
===========================

.. contents:: Contents
   :local:
   :depth: 2


Dela
----
For each dela enabled endpoints you have the following resources:

* StorageEndpoint
* StorageResource
* DelaStorageHandler
* DelaFileHandler
* DelaReadStream
* DelaWriteStream

Implemented variants:

* Disk
* HDFS
* GCP
* AWS

In progress:

* Kafka
* Network

Future:

* Memory
* Azure


In order to connect to a storage endpoint you need to implement a class extending StorageEndpoint. This object should have enough information for you to connect to the storage, including address, user, credentials.

.. code-block:: java
