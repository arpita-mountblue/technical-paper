# FIREWALLS
---

* ## INTRODUCTION:-
    * Firewall is **a network security device that monitors and filters incoming and outgoing network traffic** based on an organization's previously established security policies.

    * A firewall is essentially the  barrier that sits between a private internal network and the public Internet. 

    * A firewall's main purpose is to allow non-threatening traffic in and to keep dangerous traffic out.

    ![Firewall](https://geekflare.com/wp-content/uploads/2020/07/firewall-1.png "Firewall")

<br>

* ### HISTORY:-
    * The **first firewalls were developed in the `1980s` at** the American technology companies Cisco Systems and Digital Equipment Corporation.
    * **David Pensak** claims to have built the first commercially successful firewall.

    #### `NOTE:-` For more details please [click here](https://sites.google.com/site/firewallsfordummies/history-of-firewalls "History of firewall").

    <br>

* ### TYPES OF FIREWALL:-
    * There are **six types** of firewalls, which is given below:-
        ![Types of firewall](https://networkinterview.com/wp-content/uploads/2021/04/TYPES-OF-FIREWALL-DP.jpg "Types of firewall")

    <br>

    1. ### Packet-Filtering Firewalls:-
        ![Packet-Filtering Firewalls](https://slideplayer.com/slide/4800839/15/images/17/Packet+Filtering+Firewalls.jpg "Packet-Filtering Firewalls")
        * A **packet filtering firewalls** is a network security feature that controls the flow of incoming and outgoing network data. 
        * The firewall examines each packet, which comprises user data and control information, and tests them according to a set of pre-established rules. 
        * If the packet completes the test successfully, the firewall allows it to pass through to its destination.
        * If rejects those that don't pass the test. 
        * Firewalls test packets by examining sets of rules, protocols, ports and destination addresses.

        *  ####  There are four types of packet filtering firewall, which are given below:-
            1. [Static packet filtering firewall](https://www.informit.com/articles/article.aspx?p=31945&seqNum=2)
            2. [Dynamic packet filtering firewall](https://www.informit.com/articles/article.aspx?p=23407&seqNum=3)
            3. [Stateless packet filtering firewall](https://www.juniper.net/documentation/us/en/software/junos/routing-policy/topics/concept/firewall-filter-overview.html)
            4. [Stateful packet filtering firewall](https://www.fortinet.com/resources/cyberglossary/stateful-firewall)

        * #### Benefits of Packet Filtering firewalls:-
            * Efficiency
            * Transparency
            * Affordability
            * Accessibility

        * #### Drawbacks of Packet Filtering firewalls:-
            * Reduced security
            * Inflexibility
            * Inconsistent applicability

        #### `NOTE:-` For more details please [click here](https://www.indeed.com/career-advice/career-development/packet-filtering "Packet filtering").

    <br>

    2. ### Circuit-Level Gateways:-
        ![Circuit-Level Firewalls](https://slidetodoc.com/presentation_image_h/b7dce0a3d89450cdfdcc82c69155b142/image-16.jpg)
        * A circuit-level gateway firewall helps in providing the security between `UDP` and `TCP` using the connection. 
        * It also acts as a handshaking device between trusted clients or servers to untrusted hosts and vice versa.

        * #### Benefits of Circuit-Level Gateways firewalls:-
            * A circuit-level gateway acts as a proxy for hiding the internal host from the serving host.
            * It avoids the filtering of individual packets.
            * These gateways are inexpensive.
            * Address schemes can easily develop.
            * Simple to implement.
            * Every application does not require a separate proxy server.

        * #### Drawbacks of Circuit-Level Gateways firewalls:-
            * Circuit-level Gateway does not filter the individual packets.
            * Frequent updates are required.
            * Within the firewall, it does not offer protection against data leakage from devices.
            * For using Circuit level gateways the TCP/IP stacks are mandatory to be modified by the vendor.

        #### `NOTE:-` For more details please [click here](https://www.geeksforgeeks.org/what-is-circuit-level-gateway/ "Circuit-Level Gateways").

    <br>

    3. ### Application-Level Gateways (proxy firewall):-
        ![Application-Level Gateways](https://media.geeksforgeeks.org/wp-content/uploads/20210609152010/ALG-660x304.png "Application-Level Gateways")

        * An application gateway or application level gateway (ALG) is a firewall proxy which provides network security. 
        * It filters incoming node traffic to certain specifications which mean that only transmitted network application data is filtered.
        * Such network applications include File Transfer Protocol (FTP), Telnet, Real Time Streaming Protocol (RTSP) and BitTorrent.

        * #### Benefits of Application-Level Gateways firewalls:-
            * Direct connections between internal and external hosts are disallowed.
            * User-level authentication is supported.
            * The application commands are analyzed inside the payload portion of the data packets.

        * #### Drawbacks of Application-Level Gateways firewalls:-
            * Slower than packet filters.
            * Needs the internal client to know about them.
            * Every possible type of connection can not be supported.

        #### `NOTE:-` For more details please [click here](https://en.wikipedia.org/wiki/Application-level_gateway "Application-Level Gateways"). 

    <br>

    4. ### Stateful Inspection Firewalls:-

        ![Stateful Inspection Firewalls](https://ars.els-cdn.com/content/image/3-s2.0-B9780128112489000048-f04-03-9780128112489.jpg  "Stateful Inspection Firewalls")
        * Stateful inspection firewall is a technology that controls the flow of traffic between two or more networks. 
        * Stateful inspection firewalls track the state of sessions and dropping packets that are not part of a session allowed by a pre-defined security policy. 
        * This is sometimes called session-level protection because they keep state information for each network session and make allowed/denied decisions based on a session state table.

        * #### Benefits of Stateful Inspection firewalls:-
            * Stateful firewalls are aware of the state of a connection.
            * Stateful firewalls do not have to open up a large range of ports to allow communication.
            * Stateful firewalls prevent more kinds of DoS attacks than packet-filtering firewalls and have more robust logging.
        
        * #### Drawbacks of Stateful Inspection firewalls:-
            * They can be complex to configure.
            * They cannot prevent application-layer attacks.
            * They do not support user authentication of connections.
            * Not all protocols contain state information.

        #### `NOTE:-` For more details please [click here](https://en.wikipedia.org/wiki/Stateful_firewall "Stateful Inspection Firewalls").

    <br>

    5. ### Next-Generation Firewalls(NGFW):-
        ![Next-Generation Firewalls](https://firewall.firm.in/wp-content/uploads/2019/08/Next-Generation-Firewall-NGFW.jpeg "Next-Generation Firewalls")
        * A next-generation firewall is within the third generation of firewall technology, designed to address advanced security threats at the application level through intelligent, context-aware security features. 
        * An NGFW combines traditional firewall capabilities like packet filtering and stateful inspection with others to make better decisions about what traffic to allow. 

        * #### Benefits of Next-Generation firewalls:- 
            * Provides traditional firewall functionality combined with security functions.
            * Capable of monitoring network protocols from data link layer through the application layer.

        * #### Drawbacks of Next-Generation firewalls:-
            * Consolidation of security functions makes the NGFW a single point failure.
            * Not all organization will require all the functionality of an NGFW.

        #### `NOTE:-` For more details please [click here](https://www.vmware.com/topics/glossary/content/next-generation-firewall.html "Next-Generation Firewalls").

        <br>

    6. ### Cloud Firewalls:-
        ![Cloud Firewalls](https://cdn.masergy.com/20201113050742/sase_cloudfirewall-1.png "Cloud Firewalls")
        * Cloud Firewalls are cloud-deployed, software-based security products that help prevent cyber-attacks.
        * They form a protective shield around the cloud assets, defending them from untrusted internet traffic. 
        * Cloud assets include cloud platforms, data stored on clouds, infrastructure, and applications. 
        * Additionally, cloud-based firewalls also protect the internal/ private network and the on-premise assets. Also known as Firewall-as-a-Service (FWaaS), these security products can be offered by third-party vendors as a service.

        * #### Benefits of Cloud firewalls:- 
            * Easy to deploy and scale as per needs.
            * No hardware involved, so no wasting time in troubleshooting hardware and RMA issues.

        * #### Drawbacks of Cloud firewalls:-
            * You may not get the same throughput like in a dedicated firewall.
            * Its availability is subjected to the availability of the cloud infrastructure.
            * Running advanced security features can slow down the network.
            * Choice of high density interfaces are very less and is dependent on the cloud infrastructure.

        #### `NOTE:-` For more details please [click here](https://www.indusface.com/learning/what-is-a-cloud-firewall-and-what-are-the-benefits/ "Cloud Firewalls").

        <br>
---
---

* ## References:-
    * [https://www.youtube.com/watch?v=eO6QKDL3p1I&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNA](https://www.youtube.com/watch?v=eO6QKDL3p1I&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNA)
    * [https://www.youtube.com/watch?v=bNqvq5aw7OY](https://www.youtube.com/watch?v=bNqvq5aw7OY)
    * [https://youtu.be/9GZlVOafYTg](https://youtu.be/9GZlVOafYTg)
    * [https://www.cisco.com/c/en_in/products/security/firewalls/what-is-a-firewall.html](https://www.cisco.com/c/en_in/products/security/firewalls/what-is-a-firewall.html)
    * [https://www.checkpoint.com/cyber-hub/network-security/what-is-firewall/](https://www.checkpoint.com/cyber-hub/network-security/what-is-firewall/)
    * [https://en.m.wikipedia.org/wiki/Firewall_(computing)](https://en.m.wikipedia.org/wiki/Firewall_(computing))
    * [https://www.javatpoint.com/firewall](https://www.javatpoint.com/firewall)
   
