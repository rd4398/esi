Usage
=====

ESI accommodates three roles:

* **Admin**
   * Views and administrates the entire inventory of nodes.
   * Assigns owners and lessees to nodes.
* **Owner**
   * Views and administrates the nodes that they own.
   * Has exclusive use of their nodes, except for those that they choose to lease.
   * Assigns lessees to the nodes that they own.
   * Creates offers for their nodes, making them available for lease.
   * *Note:* The owner role is optional; every action they do can also be performed by an admin.
* **Lessee**
   * Can only view nodes that they have leased.
   * Has temporary use of their nodes for the duration of the lease.
   * Obtains a lease on a node by claiming an available offer.

ESI will typically be used to fulfill one of two broad scenarios:

* **ESI Administrator Owns All Nodes**
   * In this scenario, there are no node owners. Instead, the ESI administrator controls access to each and every node. They do so using the mechanisms described in `Lessee Node Assignment`_.
* **Multiple Node Owners Pool Nodes in ESI**
   * In this scenario, multiple node owners pool their hardware together in a single ESI instance. The owners can then use their hardware themselves, or use the mechanisms described in `Lessee Node Assignment`_ to give others access to their nodes.

.. toctree::
   :maxdepth: 2

   common_scenarios
   cli
   openshift
   keylime

.. _Lessee Node Assignment: common_scenarios.html#lessee-node-assignment
