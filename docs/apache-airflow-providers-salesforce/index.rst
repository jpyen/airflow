
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

``apache-airflow-providers-salesforce``
=======================================

Content
-------

.. toctree::
    :maxdepth: 1
    :caption: Guides

    Connection types <connections/salesforce>

.. toctree::
    :maxdepth: 1
    :caption: References

    Python API <_api/airflow/providers/salesforce/index>

.. toctree::
    :maxdepth: 1
    :caption: Resources

    Example DAGs <https://github.com/apache/airflow/tree/main/airflow/providers/salesforce/example_dags>
    PyPI Repository <https://pypi.org/project/apache-airflow-providers-salesforce/>

.. THE REMINDER OF THE FILE IS AUTOMATICALLY GENERATED. IT WILL BE OVERWRITTEN AT RELEASE TIME!


.. toctree::
    :maxdepth: 1
    :caption: Commits

    Detailed list of commits <commits>


Package apache-airflow-providers-salesforce
------------------------------------------------------

`Salesforce <https://www.salesforce.com/>`__


Release: 3.0.0

Provider package
----------------

This is a provider package for ``salesforce`` provider. All classes for this provider package
are in ``airflow.providers.salesforce`` python package.

Installation
------------

You can install this package on top of an existing airflow 2.* installation via
``pip install apache-airflow-providers-salesforce``

PIP requirements
----------------

=======================  ==================
PIP package              Version required
=======================  ==================
``simple-salesforce``    ``>=1.0.0``
``tableauserverclient``
=======================  ==================

Cross provider package dependencies
-----------------------------------

Those are dependencies that might be needed in order to use all the features of the package.
You need to install the specified provider packages in order to use them.

You can install such cross-provider dependencies when installing from PyPI. For example:

.. code-block:: bash

    pip install apache-airflow-providers-salesforce[tableau]


======================================================================================================  ===========
Dependent package                                                                                       Extra
======================================================================================================  ===========
`apache-airflow-providers-tableau <https://airflow.apache.org/docs/apache-airflow-providers-tableau>`_  ``tableau``
======================================================================================================  ===========

Downloading official packages
-----------------------------

You can download officially released packages and verify their checksums and signatures from the
`Official Apache Download site <https://downloads.apache.org/airflow/providers/>`_

* `The apache-airflow-providers-salesforce 3.0.0 sdist package <https://downloads.apache.org/airflow/providers/apache-airflow-providers-salesforce-3.0.0.tar.gz>`_ (`asc <https://downloads.apache.org/airflow/providers/apache-airflow-providers-salesforce-3.0.0.tar.gz.asc>`__, `sha512 <https://downloads.apache.org/airflow/providers/apache-airflow-providers-salesforce-3.0.0.tar.gz.sha512>`__)
* `The apache-airflow-providers-salesforce 3.0.0 wheel package <https://downloads.apache.org/airflow/providers/apache_airflow_providers_salesforce-3.0.0-py3-none-any.whl>`_ (`asc <https://downloads.apache.org/airflow/providers/apache_airflow_providers_salesforce-3.0.0-py3-none-any.whl.asc>`__, `sha512 <https://downloads.apache.org/airflow/providers/apache_airflow_providers_salesforce-3.0.0-py3-none-any.whl.sha512>`__)

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

3.0.0
.....

Breaking changes
~~~~~~~~~~~~~~~~

* ``Auto-apply apply_default decorator (#15667)``

.. Below changes are excluded from the changelog. Move them to
   appropriate section above if needed. Do not delete the lines(!):

2.0.0
.....

Tableau provider moved to separate 'tableau' provider

Things done:

    - Tableau classes imports classes from 'tableau' provider with deprecation warning

Breaking changes
~~~~~~~~~~~~~~~~

You need to install ``apache-airflow-providers-tableau`` provider additionally to get
Tableau integration working.


1.0.1
.....

Updated documentation and readme files.


1.0.0
.....

Initial version of the provider.
