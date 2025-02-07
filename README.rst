==================
Mail Messages Easy
==================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:ad807a55ea13778195322fc6c665d93fe38eec5a1bf4da790e62c01bf33ed9b0
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-cetmix%2Fcetmix--messages-lightgray.png?logo=github
    :target: https://github.com/cetmix/cetmix-messages/tree/16.0/prt_mail_messages
    :alt: cetmix/cetmix-messages

|badge1| |badge2| |badge3|

This module significantly improves Odoo mail system usability making it
much more user friendly and convenient. Please note that some feature
may not available for selected Odoo version. Please contact
`Cetmix <https://cetmix.com>`__ for more details.

Core features
~~~~~~~~~~~~~

-  View all messages in one view.
-  Message preview pane (**PRO version**).
-  Generic ``Conversation`` model for handling unresolved messages.
-  Reply, quote reply to message.
-  "Email Mode: send messages as regular email using ``To``, ``Cc`` and
   ``Bcc`` fields (**PRO version**).
-  Move messages between different records (**PRO version**).
-  Print messages.
-  Move messages to and out of ``Trash`` and manage deleted messages.
-  Archive/unachive messages.
-  Edit messages and internal notes.
-  Show original ``From``, ``To``, ``Cc`` and ``Subject`` fields of
   incoming messages (**PRO version**).
-  Hide/show notifications, internal notes and messages in chatter
   (**PRO version**).
-  Receive messages directly to ``catchall``.
-  Smart notifications: don't send email notification for incoming
   messages if recipient has already received the original email.
-  Limit number of quoted messages.
-  Show ``Lost`` messages (**PRO version**).

**Table of contents**

.. contents::
   :local:

Changelog
=========

16.0.1.0.15 (2024-05-23)
------------------------

Features
^^^^^^^^

-  Activities are now available in Conversations (3640)

16.0.1.0.14 (2024-04-26)
------------------------

Bugfixes
^^^^^^^^

-  Invalid "Recipients" and "Followers" fields layout in Message form
   view. (3547)

16.0.1.0.13 (2024-02-22)
------------------------

**Bugfixes**

-  Bug in the \_search function that may lead to recursion (3161)

16.0.1.0.12 (2024-02-08)
------------------------

**Features**

-  Allow direct incoming messages to the 'catchall' address (3161)

16.0.1.0.11 (2023-12-27)
------------------------

**Features**

-  

   -  Wizard is opening faster when quoting a large message
   -  Configure the number of quote blocks to keep when quoting messages
      (3137)

16.0.1.0.10 (2023-10-29)
------------------------

**Bugfixes**

-  Quote template fixed (2971)

16.0.1.0.9 (2023-10-26)
-----------------------

**Features**

-  Code refactoring (2940)

16.0.1.0.8 (2023-10-24)
-----------------------

**Features**

-  Quote block is changed (2859)

16.0.1.0.7 (2023-10-24)
-----------------------

**Bugfixes**

-  Removed message preview field. When hovering over a message show
   nothing for mail message and conversation. (2923)

16.0.1.0.6 (2023-10-16)
-----------------------

**Features**

-  Forward message to its original record (2931)

16.0.1.0.3
~~~~~~~~~~

**Bugfixes**

-  Minor issues

16.0.1.0.2
~~~~~~~~~~

**Bugfixes**

-  Mail Composer: 'required' attribute is correctly applied to record
   reference field

**Features**

-  Contact: current contact is selected as default records when message
   is sent using "message" icon on the partner form

16.0.1.0.1
~~~~~~~~~~

**Bugfixes**

-  Minor issues

16.0.1.0.0
~~~~~~~~~~

-  Release for Odoo 16

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/cetmix/cetmix-messages/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/cetmix/cetmix-messages/issues/new?body=module:%20prt_mail_messages%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
-------

* Ivan Sokolov
* Cetmix

Maintainers
-----------

This module is part of the `cetmix/cetmix-messages <https://github.com/cetmix/cetmix-messages/tree/16.0/prt_mail_messages>`_ project on GitHub.

You are welcome to contribute.
