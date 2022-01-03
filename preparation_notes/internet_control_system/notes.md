
Negative Feedback on the Internet
---------------------------------

Critical Abstractions
=====================

    - negative feedback

        - routing control
        - capacity control (failure to isolate packet dropping from feedback messages).

    - positive feedback
    - scale
    - functionality vs. protection

Negative Feedback
-----------------

Original ideas - see Baran

Spread out Routing

Switching decisions are made by routers that use routing tables which are a map from destination
addresses to next link address.

The routing protocols are ...
The routing tables are updated regularly with a time-frame of 5 or 10 seconds. In additions the
routing protocol can communication immediately using events on response to a change.

The routing decisions are determined by a map between every address, a next address and a cost, with
the lowest cost being placed into the routing table.

The costs are determined by the administrate of each network. They can involve very static
conditions to dynamic conditions such as:

1. bandwith
2. delay
3. reliability
4. load

How are the costs made uniform across the different units?
How big are the networks?
How general is the notion of cost?

So basically, the whole internet utilizes the routing of the local networks?

  



Positive Feedback in the Internet
---------------------------------

References
----------

RFC 1583, OSPF Versioni 2


Control of Routing
------------------

Control of Network Loops
------------------------

Control of Congestion
---------------------

Congestion Collapse
-------------------

A stable state at a sub-optimal level.


