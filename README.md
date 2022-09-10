# Hack Wiki

[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)

This repo stores what I learned, what you can learn to know how to start hacking career. However you should have knowledge about basic coding and popular algorithms.

Notes: some slides in this repo come from my course so that they are written in Vietnamese. Maybe they are out-of-date. So if you want to contribute, feel free to pull request.

## Table of content
- [Hack-Wiki](#hack-wiki)
  - [Table of content](#table-of-content)
    - [Roadmap](#roadmap)
    - [Database](#database)
      - [Introduction](#introduction-database)
    - [Computer architecture](#computer-architecture)
      - [Introduction](#introduction-architecture)
    - [Basic network](#basic-network)
      - [Introduction](#introduction-network)
    - [Basic network security](#basic-network-security)
      - [Introduction](#introduction-netsec)
    - [Analyze, detect, prevent intrusion](#analyze-detect-prevent-intrusion)
      - [Introduction](#introduction-idps)
    
---

### Roadmap

---

### Database

It is a essential part of application.

#### Introduction database

What will you learn in this session:
- Analyze, explore data in database.
- How to build, manage application - make suitable diagram, relationship, query (is it standard?). 

---

### Computer architecture 

This show how computer process works inside.

#### Introduction architecture

What will learn in this session:
- Parts, mechanism, performance of computer.
- How computer excutes commands.
- Optimizing coding skills to improve speed of programs.

Note: you can read `Computer Organization And Design 5th Edition 2014` to improve your knowledge.

---

### Basic network

Fundenmetal of network

#### Introduction network

What will learn in this session:
- Feel and termilogy. Depth, detail network.
- Basic parts in network including: internet, protocol, network edge, network core, performance, security.
- Router, switch.

Some definations:
- `Internet`: including a variety of devices connecting together all over the world.
- `Protocol`: rules to send and recieve, define format, order.
- `Network edge - end system`: network used in house, school, ... and `devices edge` are laptop, smartphone, smart tv,...

---

### Basic network security

This session is one of fundenmental security part, you should learn before start go to module Web exploit, Forensics and Reverse engineering.

#### Introduction Netsec

What will you learn in this session:
- About popular threats.
- Basic vulnerabilities in network.
- Goal: know how to attack-defense, build hacking mindset.(I wrote some ideas to start [here](https://github.com/Trumpiter-max/Tricks-in-web-exploiting#what-is-actually-hacking)) 

Preknowledge you should have before beginning:
- [Computer architecture](#computer-architecture) - how computer works.
- Basic knowledge about [network](#basic-network).
- Know how to code in Python and Golang.
- Linux fundenmental.

How to improve your performance in this module:
- Read book, some ideas and labs coming from `[SEED book] Wenliang Du (2019). Computer & internet security: A hands-on approach, 2nd edition, ISBN-13: 978-
1733003933` and `[CS book] William Stallings and Lawrie Brown (2018). Computer Security: Principles and Practice, 4th Edition, ISBN 978-0-13-479410-5.`
- Read papers and CVEs in recent years.
- Practice and practice more. Some recommended place you can learned [SEED Lab](https://seedsecuritylabs.org/), [Vulnhub](https://www.vulnhub.com/), CTFs - Box machine ([Hack the box](https://www.hackthebox.com/), [Root me](https://www.root-me.org/?lang=en)), [CEH](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/), [OSCP](https://www.offensive-security.com/pwk-oscp/), Online coure ([Udemy](https://www.udemy.com/))

Some notices:
- This session based on the triad: confidentiality, integrity, avalablability.
- `Confidentiality`: prevent from leaking information without permission.
- `Integrity`: prevent from changing information without permission.
- `Availability`: make sure the valid users can access to information and system.

---

### Analyze, detect, prevent intrusion

#### Introduction IDPS

What will you learn in this session:
- Basic knowledge abot IDPS system.
- Know how to apply IDPS system in real case.
- Experience how to use Machine Learning/ Deep Learning in IDPS system.
- Operate, rate IDPS system for per request.

Preknowledge you should have before beginning:
- Basic model of network, network mechinism.
- How to attack in network - [Basic network security](#basic-network-security)

Some notices:
- `Intrusion`: access into system without permission.
- `Evidences`: 
  - System logs are short, missing.
  - Performance of system low, or work not correctly.
  - Crash or reboot (hard to detect)
- `Detect`: track, analyze, know evidences.
- `IDS`: Intrusion Detect System - automatic system detect, analyze attacks, is suit for testing system.
- `IPS`: Instrusion Prevent System - have all functions of `IDS` but it can used for stop service, is suit for product. Moreover, `IDS/IPS` are same system but have different fuction, so that `IPS` with removing prevent function can be use as `IDS`, and vice versa.
- `IDPS` can be known as system with `IDS` and `IPS`.

---




