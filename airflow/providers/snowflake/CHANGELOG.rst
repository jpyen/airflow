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

* ``Add 'template_fields' to 'S3ToSnowflake' operator (#15926)``
* ``Allow S3ToSnowflakeOperator to omit schema (#15817)``

Bug Fixes
~~~~~~~~~

* ``fix: restore parameters support when sql passed to SnowflakeHook as str (#16102)``

.. Below changes are excluded from the changelog. Move them to
   appropriate section above if needed. Do not delete the lines(!):

1.3.0
.....

Features
~~~~~~~~

* ``Expose snowflake query_id in snowflake hook and operator (#15533)``

1.2.0
.....

Features
~~~~~~~~

* ``Add dynamic fields to snowflake connection (#14724)``

1.1.1
.....

Bug fixes
~~~~~~~~~

* ``Corrections in docs and tools after releasing provider RCs (#14082)``
* ``Prepare to release the next wave of providers: (#14487)``

1.1.0
.....

Updated documentation and readme files.

Features
~~~~~~~~

* ``Fix S3ToSnowflakeOperator to support uploading all files in the specified stage (#12505)``
* ``Add connection arguments in S3ToSnowflakeOperator (#12564)``

1.0.0
.....

Initial version of the provider.
