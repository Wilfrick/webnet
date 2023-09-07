# Webnet

Webnet aims to create an interconnected web of browsers that can communicated together via WebRTC. WebRTC requires server running somewhere for signalling for new users, but we would like this to be the only function this server servers. Repeat users should be able to connect to the network without needing intervention from this server and all users should be able to send messages around in a reliable way.

This is a learning project and as such the aims and design goals may change over time.

# System Overview

At the "front" end of the system we will have browsers communicating together via WebRTC. They should be able to send arbitrary data to any other connected browser without that data touching the signalling server. They will be connected with Webnet.
When a new user wants to join the webnet they will initially have no knowledge of any other connected users, so we will need a signalling server to pose as an 'introducer' to introduce new browsers into the webnet. I intend to write this server in Java using Spring Boot.

# Project Promises

All markdown files will be linked to (possibly indirectly) from this readme, for easy access.