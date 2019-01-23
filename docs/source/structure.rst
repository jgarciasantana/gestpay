************************************************
Define the structure of the plugin documentation
************************************************

.. contents:: The structure of each documentation should consist in these points:


Introduction
============

Introduction: a short description about the plugin, explaining how it works


Techincal requirements:
=======================

- Magento minimal requirement (give a `link <https://magento.com//>`_ where to test if the server has the minimum Magento requirement)
- Magento version compatibility
- Magento store availability from the web: it must be reachable from the bank server, without any htpassword or web restriction


Download plugin
=======================

Explain how to download the plugin from customer area: make screenshot and a guideline to download the file

.. image:: _static/customer_area.jpg
   :alt: Customer area example
   :align: center

Plugins file structure: explain the folders inside the package and give a screenshot about it
Installation: explain how to install each plugin, even for Magento1 and Magento2.
Configuration: explain how to configure each plugin. Add some screenshot and step by step configuration guide, explaining each field with a short description. Also, explain how to configure bank backoffice panel.
Test and debug: explain how to test the plugin in a step by step guide, including:
Product creation
Check order on backend
Check order on frontend
Explain how to ask for customer support: explain in a step by step guide how to ask support, following these points:
Before to ask for support: explain all the checks that should be done before to ask support, like check of configurations, bank credentials and configurations, check of logs to prevent that the error is not due to another plugin/theme, a check with the default Magento theme, and check if all requirement of point 2 are ok.
Ask support following the product page link. Here we have to explain all fields that are required for a support request. These fields are:
A complete error description, screenshot and how to reproduce the error
Link of the frontend store
Link of backend of Magento
Admin access data with complete permission with all admin permissions
FTP (or SFTP for M2) access data, with complete permissions
Link to a test product
A phone number and email address of a reference technician
Bank backoffice access data (if needed, it depends from the kind of plugin)