=====================================
Stock Picking Product Interchangeable
=====================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:53a61d84207fe2234c17a6277c9f5f97d3b956c7bdc091631d241bdf21ce8897
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fstock--logistics--warehouse-lightgray.png?logo=github
    :target: https://github.com/OCA/stock-logistics-warehouse/tree/16.0/stock_picking_product_interchangeable
    :alt: OCA/stock-logistics-warehouse
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/stock-logistics-warehouse-16-0/stock-logistics-warehouse-16-0-stock_picking_product_interchangeable
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/stock-logistics-warehouse&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module implements "interchangeable" products. If an interchangeable product is not available in stock in requested quantity its substitute products will be added to picking to complete the order.

Eg there is an "English Breakfast" tea and "Breakfast in England" tea which are absolutely the same inside and have the same price. Only package labels are different. And our customers don't care which of them will be actually delivered.

NB: Interchangeable products substitute each other. Eg if "English Breakfast" can substitutes "Breakfast in England" then "Breakfast in England" can substitute "English Breakfast".

**Table of contents**

.. contents::
   :local:

Usage
=====

Click **Mark todo** or "Check availability" button in Stock Picking form.

If **Substitute Products** option is activated for picking operation type and there is not enough stock of an interchangeable product substitute products will be added to picking.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/stock-logistics-warehouse/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/stock-logistics-warehouse/issues/new?body=module:%20stock_picking_product_interchangeable%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Cetmix

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-geomer198| image:: https://github.com/geomer198.png?size=40px
    :target: https://github.com/geomer198
    :alt: geomer198
.. |maintainer-CetmixGitDrone| image:: https://github.com/CetmixGitDrone.png?size=40px
    :target: https://github.com/CetmixGitDrone
    :alt: CetmixGitDrone

Current `maintainers <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-geomer198| |maintainer-CetmixGitDrone| 

This module is part of the `OCA/stock-logistics-warehouse <https://github.com/OCA/stock-logistics-warehouse/tree/16.0/stock_picking_product_interchangeable>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
