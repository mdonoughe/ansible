
.. _porting_2.13_guide_core:

*******************************
Ansible-core 2.13 Porting Guide
*******************************

This section discusses the behavioral changes between ``ansible-core`` 2.12 and ``ansible-core`` 2.13.

It is intended to assist in updating your playbooks, plugins and other parts of your Ansible infrastructure so they will work with this version of Ansible.

We suggest you read this page along with `ansible-core Changelog for 2.13 <https://github.com/ansible/ansible/blob/devel/changelogs/CHANGELOG-v2.13.rst>`_ to understand what updates you may need to make.

This document is part of a collection on porting. The complete list of porting guides can be found at :ref:`porting guides <porting_guides>`.

.. contents:: Topics


Playbook
========

No notable changes


Command Line
============

No notable changes


Deprecated
==========

No notable changes


Modules
=======

* Python 2.7 is a hard requirement for module execution in this release. Any code utilizing ``ansible.module_utils.basic`` will not function with a lower Python version.


Modules removed
---------------

The following modules no longer exist:

* No notable changes


Deprecation notices
-------------------

No notable changes


Noteworthy module changes
-------------------------

No notable changes


Plugins
=======

No notable changes


Porting custom scripts
======================

No notable changes


Networking
==========

No notable changes
