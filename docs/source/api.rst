u-LocateEngine API
==================

Interaction with u-LocateEngine can be achieved using the following application interface and data types. This section describes what u-LocateEngine is expected to provide.

Connection Types
================

u-LocateEngine supports the MQTT protocol through the deployment of an MQTT Broker. Interaction with the MQTT Broker can be achieved using MQTT clients.

MQTT API
========

This documentation provides an overview of the MQTT API topics and their respective operations.

Angles
------

**Get Angles Data**

Retrieve angles data via MQTT.

Positions
---------

**Get Positions Data**

Retrieve positions data via MQTT.

Provision/Anchor/Create
-----------------------

**Create New Anchor**

Create a new anchor via MQTT.

Provision/Anchor/Update
-----------------------

**Update Anchor**

Update an existing anchor or create a new one in case the anchor doesn't exist via MQTT.

Provision/Anchor/Delete
-----------------------

**Delete Anchor**

Delete an existing anchor via MQTT.

Provision/Anchor/Created
------------------------

**Anchor Created Notification**

Receive notifications when an anchor is created.

Provision/Anchor/Updated
------------------------

**Anchor Updated Notification**

Receive notifications when an anchor is updated.

Provision/Anchor/Deleted
------------------------

**Anchor Deleted Notification**

Receive notifications when an anchor is deleted.

Provision/Anchor/GetRequest
---------------------------

**Get Anchors List Request**

Request the list of anchors via MQTT.

Provision/Anchor/Get
---------------------

**Get Anchors Details**

Retrieve the list of anchors via MQTT.

BeaconsBlackList/GetRequest
---------------------------

**Get Beacons Blacklist Request**

Request the list of blacklisted beacons.

BeaconsBlackList/Add
---------------------

**Add Beacon to Blacklist**

Add a beacon to the blacklist via MQTT.

BeaconsBlackList/Remove
------------------------

**Remove Beacon from Blacklist**

Remove a beacon from the blacklist via MQTT.

BeaconsBlackList/Get
---------------------

**Get Blacklist of Beacons**

Retrieve the list of blacklisted beacons via MQTT.
