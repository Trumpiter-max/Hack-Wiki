# Analyze, detect, prevent intrusion

## Introduction IDPS

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