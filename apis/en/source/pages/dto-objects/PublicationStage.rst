.. Copyright 2018 FUJITSU LIMITED

.. _publicationstage-object:

publicationStage
================

Holds all the meta-data of the publication stage of a migration.

Attributes
~~~~~~~~~~

The list of attributes for ``publicationStage`` are:

	* ``publishImage`` (:ref:`publishImage-object`): the image published by the publication stage
	* ``publishImageUri`` (anyURI): the uri resource of the published image
	* ``pipelineUri`` (anyURI): the uri of the parent pipeline
	* ``created`` (dateTime): the date the appliance template is created
	* ``dbId`` (long): the database id of the object
	* ``digest`` (string): the digest value (used for etag)
	* ``lastModified`` (dateTime): the last modified date of this object


