
 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

``apache-airflow-providers-mongo``
==================================

Content
-------

.. toctree::
    :maxdepth: 1
    :caption: References

    Connection types <connections/mongo>
    Python API <_api/airflow/providers/mongo/index>

.. toctree::
    :maxdepth: 1
    :caption: Resources

    PyPI Repository <https://pypi.org/project/apache-airflow-providers-mongo/>

.. THE REMINDER OF THE FILE IS AUTOMATICALLY GENERATED. IT WILL BE OVERWRITTEN AT RELEASE TIME!


.. toctree::
    :maxdepth: 1
    :caption: Commits

    Detailed list of commits <commits>


Package apache-airflow-providers-mongo
------------------------------------------------------

`MongoDB <https://www.mongodb.com/what-is-mongodb>`__


Release: 2.0.0

Provider package
----------------

This is a provider package for ``mongo`` provider. All classes for this provider package
are in ``airflow.providers.mongo`` python package.

Installation
------------

You can install this package on top of an existing airflow 2.* installation via
``pip install apache-airflow-providers-mongo``

PIP requirements
----------------

=============  ===================
PIP package    Version required
=============  ===================
``dnspython``  ``>=1.13.0,<2.0.0``
``pymongo``    ``>=3.6.0``
=============  ===================

 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.


Changelog
---------

2.0.0
.....

Breaking changes
~~~~~~~~~~~~~~~~

* ``Auto-apply apply_default decorator (#15667)``

Features
~~~~~~~~

* ``Add Connection Documentation for Popular Providers (#15393)``

Bug Fixes
~~~~~~~~~


.. Below changes are excluded from the changelog. Move them to
   appropriate section above if needed. Do not delete the lines(!):
   * ``Prepares provider release after PIP 21 compatibility (#15576)``
   * ``Update Docstrings of Modules with Missing Params (#15391)``
   * ``Remove Backport Providers (#14886)``
   * ``Update documentation for broken package releases (#14734)``

1.0.1
.....

Updated documentation and readme files.

1.0.0
.....

Initial version of the provider.
