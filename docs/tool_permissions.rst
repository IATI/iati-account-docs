.. _`tool_permissions`:
========================
Manage tool permissions
======================== 

There are a `variety of tools available <https://iatistandard.org/en/guidance/publishing-data/how-to-publish-data/publishing-tools-and-services-to-create-your-iati-data-files/>`_ to support organisations publish IATI data. The two most commonly used tools are:

* `IATI Publisher <https://publisher.iatistandard.org/>`_ (maintained by the IATI Secretariat)
* `AidStream <https://aidstream.org/>`_ (a third-party tool)

Both IATI Publisher and AidStream work with IATI's Register Your Data service to automatically register your datasets with IATI. This saves you having to interact with IATI Account directly, apart from your organisation's initial registration.

When you sign in to IATI Publisher or AidStream, they detect the IATI reporting organisation(s) that you are associated with and what data publishing permission level you have for each (admin, editor or contributor). These permissions are controlled by admin users for your organisation, as explained here: `IATI Account user permissions <https://docs.account.iatistandard.org/en/latest/manage_organisation_users/#user-permissions>`_.

The third-party providers of IATI publishing tools may need the ability to change your organisation's published IATI data in some cases - for example, to troubleshoot an issue you are experiencing.
To allow this, we have developed third party permissions, which can be managed for individual publishing tools via your organisation's page in IATI Account.


Why do tool providers need this permission?
-------------------------------------------
Third-party tool providers should only change your organisation's IATI datasets in the following cases:
- to troubleshoot an issue that your organisation is experiencing with the tool (e.g. you are unable to publish data).
- to faciliate a direct request from your organisation (e.g. to unpublish data).
- to manage your IATI data on your organisation's behalf as part of a commercial agreement.


How do I manage tool permissions?
----------------------------------
While signed in to IATI Account, you can view the reporting organisations that you are associated with on the `'My Data' <https://account.iatistandard.org/en/data/>`_ page.

Clicking 'View/Edit' will show the full profile for your organisation in IATI Account.

A new section has been added to this page for 'Third Party Tools':

.. figure:: images/third_party_tools_header.png
    :width: 100 %
    :align: center
    :alt: A screenshot of the IATI Account reporting organisation page with the navigation menu to jump to different page sections.

In the 'Third Party Tools' section towards the bottom of the page, you will see a list of tools that currently have permission to edit your published data:

.. figure:: images/third_party_tools_list.png
    :width: 100 %
    :align: center
    :alt: A screenshot of the list of third party tools the example organisation has authorised.

If you need to authorise a new tool, you can select it in the dropdown menu under 'Authorise a new third party tool':

.. figure:: images/third_party_tools_new_authorisaton.png
    :width: 100 %
    :align: center
    :alt: A screenshot of the list of available tools that the example organisation could authorise to have access to their data.

.. warning::

   Typically, you should only be using one IATI publishing tool so there is rarely a need to authorise more than one tool to have access to your account. If you change tool, you can revoke the old    tool's access to your account following the instructions below.


How do I revoke a tool's permissions?
-------------------------------------

You can revoke a tool's permission at any time by checking the box in the 'Revoke Authorisation' column, then clicking 'Remove':

.. figure:: images/third_party_tools_revoke_access.png
    :width: 100 %
    :align: center
    :alt: A screenshot of how to revoke acccess to an authorised third party tool.

.. warning::

   Revoking a tool's permission will affect the ability of the tool provider to provider support in the event you need help with your data publishing. It is not recommended to do this if your organisation is still using the tool actively for publishing.


Which tools can I authorise?
----------------------------
Currently, only IATI Publisher and AidStream work with IATI's Register Your Data service. These are the only two tools that you can authorise via IATI Account, bearing in mind that your organisation should only be actively using one of them.

Other third party tools may choose to use the Regsiter Your Data service in future, in which case this page will be updated.
