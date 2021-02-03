.. ...........................................................................
.. © Copyright IBM Corporation 2020                                          .
.. ...........................................................................

===================
Z System Automation
===================

The **IBM Z® System Automation collection**, also represented as
`ibm_zos_sysauto`_ in this document, is part of the broader
initiative to bring Ansible® Automation to IBM Z through the offering
**Red Hat® Ansible® Certified Content for IBM Z**.

The **IBM Z System Automation collection** provides `Ansible`_ playbooks and
roles that can create and delete `dynamic resources`_ from a template defined in
the current active policy of an `IBM Z System Automation`_ environment.

The Ansible modules in this collection are written in Python and interact with
the `Operations REST server component`_ of `IBM Z System Automation`_.

The Ansible modules in this collection are written in Python and interact with
the Web Services API of the Hardware Management Console (HMC) of the Z machines
to be managed.

.. _ibm_zos_sysauto:
   https://galaxy.ansible.com/ibm/ibm_zos_sysauto
.. _IBM Z System Automation:
   https://www.ibm.com/products/z-system-automation
.. _Operations REST server component:
   https://www.ibm.com/support/knowledgecenter/de/SSWRCJ_4.2.0/com.ibm.safos.doc_4.2/Integrating.html
.. _dynamic resources:
   https://www.ibm.com/support/knowledgecenter/de/SSWRCJ_4.2.0/com.ibm.safos.doc_4.2/UserGuide/Dynamic_Resources.html


.. toctree::
   :maxdepth: 1
   :caption: Collection Content

   source/roles