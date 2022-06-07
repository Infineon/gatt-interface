# gatt-interface

### Overview

This repo contains the GATT Interface Library (gatt_interface.a) used in BTSDK 3.3 or higher.

The GATT Interface Library provides the interface between the Bluetooth&#174 stack GATT layer and services or applications. It is responsible for routing the incoming GATT commands to the appropriate services or applications.

The GATT Interface Library helps applications to:
* Discover remote services, included services, characteristics, and descriptors, and map them to the registered service implementations
* Setup local services, included services, characteristics, and descriptors, and map them to the registered service implementations
* Perform basic operations such as configuring notifications, notifying remote clients, or reading characteristics
* Organize non-volatile data for storing and reading back from NVRAM
