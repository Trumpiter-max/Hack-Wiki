# Basic network

Fundenmetal of network

## Introduction network

<details>
<summary> <b> What will learn in this session: </b> </summary>

- Feel and termilogy. Depth, detail network.
- Basic parts in network including: internet, protocol, network edge, network core, performance, security.
- Router, switch.

Some definitions:
- `Protocol`:  rules to send and receive, define the format, and order.
- `Network edge / end system`:  networks used in the house, school, ... and `devices edge` are laptops, smartphones, and smart tv,...
- `Internet`:  the network of networks, including many connected computers all over the world. 
- `Router`: a device using for fordward packet in network. Router is used by LAN as well as MAN
- `Switch`: a device using for gather many devices in local, connect the end devices. Switch is used by only LAN.
- `bps`: bits per second, a popular unit for measure network speed

</details>

----

<details>
<summary> <b> Store & Forward </b> </summary>

`Store & Forward` is all packets should be delivered to router before those are transmit to next part.

It takes `L/R seconds` per hop for transmitting a L-bit packet with R bps. So if the latency when a send packet from source to destination with 2 hops takes `2L/R` seconds 

End-end delay = `2L/R + D1/c + D2/d` caused by spread delay. D1, D2 are the length of link; c, d are spread speed.

</details>

---

<details>
<summary> <b> Alternative core </b> </summary>

Equally divided resource for connecting between source and destination

`FDM`: all connection are parallel and no queue. Using a channel per connection.
![](https://i.ibb.co/94twtMz/Capture.png)

`TDM`: all connection in queue and no parallel. Resource usage per connection in limit time.
![](https://i.ibb.co/WtBKHc7/Capture.png)

`Circuit switching`: data is transmitted follow by a router until end connection
 - Pros: stable, little latency or loss.
 - Cons: more time-consuming connect initialization, performance not high.
 - Maximum number of connect at any one time is total of connection. In this case, this is 65 circuit.
 - When connection is full, it will block another conection want to join in.


![](https://i.ibb.co/vL7Mt2d/Capture.png)

`Packet Switching`: divide data into packets application layer 
- Pros: high performance.
- Cons: more packets more time-consume, high loss rate.

</details>
 
---
<details>
<summary> <b> Reasons cause delay in network </b> </summary>

Delay time is equal by total of reasons below: 

- Process at node
- Queue
- Transmit, length 
- Spread in environment (~2x10^8 m/s)

</details>

---

<details>
<summary> <b> Throughput & Bandwidth </b> </summary>

`Bandwidth`: the maximum amount of data transmitted over an internet connection in a given amount of time.

`Throughput`: transmiting speed (bits/time unit) between source and destination. 

</details>


## OSI Model

Using for simplizing network, easy to understand relation and maintain, update network. 

<details>

<summary> There are 7 layers in OSI: </summary>

- Layer 7: Application has HTTP, FTP, Telnet, SMTP, DNS
- Layer 6: Presentation 
- Layer 5: Session
- Layer 4: Transport has TCP, UDP
- Layer 3: Network has IP
- Layer 2: Link
- Layer 1: Physics 

</details>
