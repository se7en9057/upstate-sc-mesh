# South Carolina Mesh

## Overview

This project is the official website for **South Carolina Mesh (SC Mesh)**, a community dedicated to building and maintaining an off-grid communication network in the state of South Carolina.  SCMesh is a decentralized, but loosely organized group for South Carolina (and other) tech enthusiasts who work together on a volunteer basis to make South Carolina mesh network work the best it can. 

## What is Meshtastic?

[Meshtastic](https://meshtastic.org/) is an open-source project that leverages affordable, low-power LoRa devices to create a decentralized, off-grid communication network. It's ideal for situations requiring robust communication independent of traditional infrastructure, such as:

*   **Hiking and Outdoor Adventures:** Stay connected in remote areas where cellphones don't work due to absence of nearby towers or too much congestion.
*   **Emergency Preparedness:** Maintain communication during outages or disasters, when regular infrastructure like Cell phones or internet is unavailable.
*   **Community Building:** Connect with like-minded individuals and expand local network coverage.

## Our Community

SC Mesh is comprised of enthusiasts, hobbyists, and prepared individuals passionate about resilient communication. Our main focus is contributing to Meshtastic ecosystem in South Carolina; however, we are exploring other communication systems such as MeshCore. We encourage collaboration, knowledge sharing, and mutual support to expand our network's reach and capabilities.

## Join Us

Ready to get involved? Join our Discord server to connect with other members, ask questions, and participate in discussions about Meshtastic and our local network. Discord is similar to forum site or message boards, except you can also use audio and video to communicate with the group. 

**[Join our Discord Community](https://discord.gg/ZVtQeThnPU)**

Check out our self-reported map to see who is around you **[Meshview](https://meshview.scmesh.us/map)**

## Other ways to get involved
Join us on our MQTT Server using following settings on your node:

**_Radio Settings/LoRa_**

OK to MQTT - ON

--------------------------------
**_Radio Settings/Channels_**

Click to Add Channel

Name: SCMesh

Key Size: Default (8bit)

Key: AQ==

Channel Role: Secondary

Position: ON, 1.8 miles

MQTT: Uplink ON, Downlink ON

---------------------------------

**_Module Settings/MQTT_**

Enabled: ON

MQTT Client Proxy: ON if using cellphone. (if node connected to wifi, leave this off)

Encryption Enabled: ON

JSON Enabled: OFF

**Map Report**

Enabled: ON

Consent to voluntary transmission ON

Set Map Publish Interval to 1-3 hours

Approximate location: 1.8 miles

**Root Topic**

Root topic: msh/US/SC

**Server**

Address: mqtt.scmesh.us

Username: scmesh

Password: Meshtastical (M is capitalized)

TLS: OFF (the server should pass TLS or non TLS traffic. leave off for consistency) 


## Contact

For general inquiries, please join our Discord server.
