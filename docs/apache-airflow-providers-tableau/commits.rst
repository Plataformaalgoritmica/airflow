
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


Package apache-airflow-providers-tableau
------------------------------------------------------

`Tableau <https://www.tableau.com/>`__


This is detailed commit list of changes for versions provider package: ``tableau``.
For high-level changelog, see :doc:`package information including changelog <index>`.



2.1.4
.....

Latest change: 2022-01-21

================================================================================================  ===========  =======================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =======================================================================
`506efb6fa <https://github.com/apache/airflow/commit/506efb6fa3999ac21a8539e863d81dc684abe52a>`_  2022-01-21   ``Squelch more deprecation warnings (#21003)``
`602abe839 <https://github.com/apache/airflow/commit/602abe8394fafe7de54df7e73af56de848cdf617>`_  2022-01-20   ``Remove ':type' lines now sphinx-autoapi supports typehints (#20951)``
`5569b868a <https://github.com/apache/airflow/commit/5569b868a990c97dfc63a0e014a814ec1cc0f953>`_  2022-01-09   ``Fix MyPy Errors for providers: Tableau, CNCF, Apache (#20654)``
================================================================================================  ===========  =======================================================================

2.1.3
.....

Latest change: 2021-12-31

================================================================================================  ===========  =========================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =========================================================================
`f77417eb0 <https://github.com/apache/airflow/commit/f77417eb0d3f12e4849d80645325c02a48829278>`_  2021-12-31   ``Fix K8S changelog to be PyPI-compatible (#20614)``
`97496ba2b <https://github.com/apache/airflow/commit/97496ba2b41063fa24393c58c5c648a0cdb5a7f8>`_  2021-12-31   ``Update documentation for provider December 2021 release (#20523)``
`d56e7b56b <https://github.com/apache/airflow/commit/d56e7b56bb9827daaf8890557147fd10bdf72a7e>`_  2021-12-30   ``Fix template_fields type to have MyPy friendly Sequence type (#20571)``
`a0821235f <https://github.com/apache/airflow/commit/a0821235fb6877a471973295fe42283ef452abf6>`_  2021-12-30   ``Use typed Context EVERYWHERE (#20565)``
`636ae0a33 <https://github.com/apache/airflow/commit/636ae0a33dff63f899bc554e6585104776398bef>`_  2021-12-22   ``Ensure Tableau connection is active to access wait_for_state (#20433)``
`6174198a3 <https://github.com/apache/airflow/commit/6174198a3fa3ab7cffa7394afad48e5082210283>`_  2021-12-13   ``Fix MyPy Errors for Tableau provider (#20240)``
================================================================================================  ===========  =========================================================================

2.1.2
.....

Latest change: 2021-10-29

================================================================================================  ===========  ======================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ======================================================================================
`d9567eb10 <https://github.com/apache/airflow/commit/d9567eb106929b21329c01171fd398fbef2dc6c6>`_  2021-10-29   ``Prepare documentation for October Provider's release (#19321)``
`e4888a061 <https://github.com/apache/airflow/commit/e4888a061f2f657a3329786a68beca9f824b2f8e>`_  2021-10-21   ``Remove distutils usages for Python 3.10 (#19064)``
`840ea3efb <https://github.com/apache/airflow/commit/840ea3efb9533837e9f36b75fa527a0fbafeb23a>`_  2021-09-30   ``Update documentation for September providers release (#18613)``
`ef037e702 <https://github.com/apache/airflow/commit/ef037e702182e4370cb00c853c4fb0e246a0479c>`_  2021-09-29   ``Static start_date and default arg cleanup for misc. provider example DAGs (#18597)``
================================================================================================  ===========  ======================================================================================

2.1.1
.....

Latest change: 2021-08-30

================================================================================================  ===========  ============================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ============================================================================
`0a6858847 <https://github.com/apache/airflow/commit/0a68588479e34cf175d744ea77b283d9d78ea71a>`_  2021-08-30   ``Add August 2021 Provider's documentation (#17890)``
`be75dcd39 <https://github.com/apache/airflow/commit/be75dcd39cd10264048c86e74110365bd5daf8b7>`_  2021-08-23   ``Update description about the new ''connection-types'' provider meta-data``
`76ed2a49c <https://github.com/apache/airflow/commit/76ed2a49c6cd285bf59706cf04f39a7444c382c9>`_  2021-08-19   ``Import Hooks lazily individually in providers manager (#17682)``
`5df99d6c6 <https://github.com/apache/airflow/commit/5df99d6c690fbdd728c9fd9482ec9a7479dfd3c2>`_  2021-08-09   ``New generic tableau operator: TableauOperator  (#16915)``
================================================================================================  ===========  ============================================================================

2.1.0
.....

Latest change: 2021-07-26

================================================================================================  ===========  =============================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =============================================================================
`87f408b1e <https://github.com/apache/airflow/commit/87f408b1e78968580c760acb275ae5bb042161db>`_  2021-07-26   ``Prepares docs for Rc2 release of July providers (#17116)``
`0dbd0f420 <https://github.com/apache/airflow/commit/0dbd0f420cc08e011317e2a9f21f92fff4a64c1b>`_  2021-07-26   ``Remove/refactor default_args pattern for miscellaneous providers (#16872)``
`29b6be848 <https://github.com/apache/airflow/commit/29b6be8482f4cd5da46511e91d3b910014980308>`_  2021-07-21   ``Refactored waiting function for Tableau Jobs (#17034)``
`ef3c75df1 <https://github.com/apache/airflow/commit/ef3c75df17d87b292f8c06b250a41633aaccbdc0>`_  2021-07-21   ``Fix bool conversion Verify parameter in Tableau Hook (#17125)``
`d02ded65e <https://github.com/apache/airflow/commit/d02ded65eaa7d2281e249b3fa028605d1b4c52fb>`_  2021-07-15   ``Fixed wrongly escaped characters in amazon's changelog (#17020)``
`b916b7507 <https://github.com/apache/airflow/commit/b916b7507921129dc48d6add1bdc4b923b60c9b9>`_  2021-07-15   ``Prepare documentation for July release of providers. (#17015)``
`53246ebef <https://github.com/apache/airflow/commit/53246ebef716933f71a28901e19367d84b0daa81>`_  2021-07-15   ``Deprecate Tableau personal token authentication (#16916)``
`df0746e13 <https://github.com/apache/airflow/commit/df0746e133ca0f54adb93257c119dd550846bb89>`_  2021-07-10   ``Allow disable SSL for TableauHook (#16365)``
================================================================================================  ===========  =============================================================================

2.0.0
.....

Latest change: 2021-06-18

================================================================================================  ===========  =======================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =======================================================================
`bbc627a3d <https://github.com/apache/airflow/commit/bbc627a3dab17ba4cf920dd1a26dbed6f5cebfd1>`_  2021-06-18   ``Prepares documentation for rc2 release of Providers (#16501)``
`cbf8001d7 <https://github.com/apache/airflow/commit/cbf8001d7630530773f623a786f9eb319783b33c>`_  2021-06-16   ``Synchronizes updated changelog after buggfix release (#16464)``
`1fba5402b <https://github.com/apache/airflow/commit/1fba5402bb14b3ffa6429fdc683121935f88472f>`_  2021-06-15   ``More documentation update for June providers release (#16405)``
`9c94b72d4 <https://github.com/apache/airflow/commit/9c94b72d440b18a9e42123d20d48b951712038f9>`_  2021-06-07   ``Updated documentation for June 2021 provider release (#16294)``
`37681bca0 <https://github.com/apache/airflow/commit/37681bca0081dd228ac4047c17631867bba7a66f>`_  2021-05-07   ``Auto-apply apply_default decorator (#15667)``
`807ad32ce <https://github.com/apache/airflow/commit/807ad32ce59e001cb3532d98a05fa7d0d7fabb95>`_  2021-05-01   ``Prepares provider release after PIP 21 compatibility (#15576)``
`40a2476a5 <https://github.com/apache/airflow/commit/40a2476a5db14ee26b5108d72635da116eab720b>`_  2021-04-28   ``Adds interactivity when generating provider documentation. (#15518)``
`bf2b48174 <https://github.com/apache/airflow/commit/bf2b48174a1ccfe398eefba7f04a5cacac421266>`_  2021-04-27   ``Add Connection Documentation for Providers (#15499)``
`68e4c4dcb <https://github.com/apache/airflow/commit/68e4c4dcb0416eb51a7011a3bb040f1e23d7bba8>`_  2021-03-20   ``Remove Backport Providers (#14886)``
================================================================================================  ===========  =======================================================================

1.0.0
.....

Latest change: 2021-02-27

================================================================================================  ===========  ===================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ===================================================================
`589d6dec9 <https://github.com/apache/airflow/commit/589d6dec922565897785bcbc5ac6bb3b973d7f5d>`_  2021-02-27   ``Prepare to release the next wave of providers: (#14487)``
`45e72ca83 <https://github.com/apache/airflow/commit/45e72ca83049a7db526b1f0fbd94c75f5f92cc75>`_  2021-02-25   ``Add Tableau provider separate from Salesforce Provider (#14030)``
================================================================================================  ===========  ===================================================================
