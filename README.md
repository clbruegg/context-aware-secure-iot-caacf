# Context-Aware Access Control Framework  
**for Secure IoT Cyberinfrastructure**

![GitHub repo size](https://img.shields.io/github/repo-size/Brueggs/context-aware-secure-iot)
![License](https://img.shields.io/badge/License-MIT-green)
![Topics](https://img.shields.io/badge/topics-iot_security-blue)

**Author:** Collin Brueggeman, MSCS  
**Institution:** Dakota State University  
**Date:** 2025  

[**Download Full Paper (PDF)**](./docs/A%20Context-Aware%20Access%20Control%20Framework%20for%20Secure%20IoT%20Cyberinfrastructure%20-%20Brueggeman.pdf)

---

## Abstract

The Internet of Things (IoT) powers critical cyberinfrastructure in healthcare, smart cities, and industrial systems — but its dynamic, resource-constrained nature makes traditional access control (RBAC/ABAC) insufficient.  

This paper proposes **CAACF** (Context-Aware Access Control Framework): a lightweight, decentralized solution that uses real-time contextual attributes (device state, location, time, network behavior) for adaptive access decisions at the edge.  

Built for CoAP-constrained environments, CAACF reduces latency, improves scalability, and resists common IoT attacks like Mirai-style botnets.

---

## Table of Contents
- [Problem & Motivation](#problem--motivation)
- [CAACF Architecture](#caacf-architecture)
- [Key Advantages](#key-advantages)
- [Proposed Implementation & Evaluation](#proposed-implementation--evaluation)

---

## Key Highlights
- **Addresses core IoT limitations**: heterogeneity, resource constraints, static policies  
- **Contextual attributes**: device state, temporal, spatial, network behavior  
- **Architecture**: Edge-based PDP + PEP, lightweight Policy Repository (JSON)  
- **Protocols**: CoAP, MQTT, ECDSA for constrained devices  
- **Evaluation focus**: Accuracy, latency (<100ms target), scalability (100–10,000 devices), context integrity  
- **Comparison**: Outperforms static RBAC in dynamic IoT environments  

---

## Technologies & Topics
`iot` `cybersecurity` `access-control` `context-aware` `cyberinfrastructure` `coap` `edge-computing` `rbac` `abac`

---

## How to Cite

```bibtex
@misc{brueggeman2025caacf,
  author       = {Brueggeman, Collin},
  title        = {A Context-Aware Access Control Framework for Secure IoT Cyberinfrastructure},
  year         = {2025},
  howpublished = {GitHub},
  url          = {https://github.com/Brueggs/context-aware-secure-iot}
}