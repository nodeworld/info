# Nodeworld
**Nodeworld** is fun, interactive, and centralized approach to to old school IRC (Internet Relay Chat). The visitors (people) will be able to create and join hundreds of nodes (chat rooms). Nodes can be designed to serve a variety of purposes, ranging from hangout areas, to real-time game sessions, private business exchanges, and more! The sky is the limit.

# Features
## Detached Digital Currency
To encourage fun throughout Nodeworld, an isolated digital currency called **credits** are rotated through nodes. Besides being used for claiming new nodes, Nodeworld itself provides no credit-related services, and leaves total handling of the market up to the visitors.

Credits circulate commonly through nodes. For example: a game node may grant visitors reward credits upon meeting its winning conditions. In addition, another node may serve as a marketplace for purchasing cosmetics.

## Homebrew Scripting
Nodeworld exposes a public built-in scripting API that allows visitors to have more control over the mechanics of their nodes. Visitors can write **scripts** that, in turn, can be attached to **hooks** in their nodes.

Scripts will be based off of JavaScript, and Nodeworld will provide an overhead interface of functions, variables, and access to private databases to help visitors control their nodes. A set of hooks, present in each node, will serve as the backbone of scripts, invoking them in the appropriate context.

# Roadmap
## **0.1.0** Base
The initial alpha milestone. At this point, only the bare minimum of Nodeworld's infrastructure should be implemented.

## **0.2.0** Commands
The commands system milestone. At this point, the front-end system for handling local commands should be operating on the web interface, as well as come shipped with a default set of basic commands. This milestone should also set in place the foundation on the back-end that will support custom node commands in the 0.4.0 release.

## **0.3.0** Scripting
The homebrew scripting milestone. At this point, a built-in code editor should be exposed through the web interface (and alternatively, an external code import system) for creating scripts. The back-end API service should be capable of executing these scripts attached to node hooks in a secure context, and handling side-effects.

## **0.4.0** Subnodes & Entities
The subnodes and entities milestone. At this point, nodes should be able to have children, establishing a parent-child relationship in which the children are referred to as "subnodes". This implementation detail, although small, should allow creators to expand their nodes even further by giving them the opportunity to segment their chat room, creating a network of inner rooms for certain purposes.

Entities will also be implemented: interactive objects programmed through their own set of hooks attachable to scripts. Entities will be vaguely indistinguishable from visitors in terms of communication and action. To elaborate: entities will be able to speak, invoke commands, and even interact with each other all in the context of the node they exist in.

## **0.5.0** Credits
The credits milestone. At this point, a market based on digital currency will emerge throughout Nodeworld, and with it, interfaces for handling its exchange through scripts. Visitors will be able to add a degree of competitiveness, engagement, and fun to their node, no matter what its purpose is. Nodeworld itself will remain isolated from the market, save for a regulatory service allowing visitors to claim vacant nodes through a fixed (note: in the future, possibly bidded) exchange of credits.

*Note: Due to the state of Nodeworld currently being in active development, official named milestones may or may not be added after this point leading up to the stable 1.0.0 release.*
