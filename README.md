# Computing Satellites: Moving Data Centers into Orbit

> Computing satellites, also known as orbital compute nodes or space computing satellites, are satellites equipped with onboard AI chips and edge computing systems. They can filter data, detect targets, and make preliminary decisions in orbit — reducing the bandwidth bottleneck and response delay of the traditional “sense on orbit, process on ground” model.

## What Is a Computing Satellite?

Traditional remote sensing satellites follow a “sense on orbit, process on ground” model. The satellite collects data, and the ground station processes it. A single high-resolution remote sensing satellite can generate tens of terabytes of raw data per day. However, limited by ground station windows and downlink bandwidth, a large share of that data is discarded before it ever reaches the ground.

Computing satellites move part of the computation into orbit. With onboard AI chips, radiation-hardened processors, and lightweight models, a satellite can process remote sensing data during flight and transmit only the most valuable results back to Earth.

Further, multiple computing satellites can be connected through inter-satellite laser links to form a distributed space computing cluster. This cluster can provide compute leasing and intelligent space data processing services — an orbital compute infrastructure.

## Why Now?

Three technical shifts are making orbital compute more feasible:

1. **Onboard AI chips are improving.** Radiation-hardened AI chips designed for space are reaching hundreds of TOPS while keeping power consumption within tens of watts. Advances in ground AI chips and radiation hardening are giving satellites more onboard intelligence.

2. **Inter-satellite laser communication is becoming practical.** Laser links offer bandwidth orders of magnitude higher than traditional microwave links and do not require spectrum licensing. They allow computing satellites to exchange data at high speed and operate as a network rather than isolated nodes.

3. **AI model compression is maturing.** Through pruning, quantization, and knowledge distillation, large models can be compressed for onboard deployment. Object detection, change detection, and semantic segmentation on remote sensing images can now run in real time on edge devices.

## Core Technical Challenges

### Thermal Management

Cooling in space is brutal. There is no air, only radiation. Deploying 1 kW of orbital compute may require a radiator of about 1 square meter and nearly 1 kilogram. Ground data centers use liquid cooling, which is far more efficient. Every gram saved in the thermal system means more payload capacity for computing hardware.

### Power

Although onboard AI chips are low-power, the total power consumption becomes significant as the constellation scales. Satellite solar panels and batteries are limited in area and capacity. Power supply is a hard constraint. Future systems may require large flexible solar arrays or space nuclear power.

### Radiation Hardening

High-energy particles in space can cause single-event upsets or permanent damage to chips. Radiation-hardened designs sacrifice some performance and increase cost. Balancing compute performance and reliability is a long-term engineering challenge. Many space-grade chips still use mature nodes such as 28 nm, with compute density far below leading ground AI chips.

### Inter-Satellite Laser Links

Laser communication requires precise alignment over long distances under high dynamics. If the alignment error exceeds a fraction of a hair’s width over 10 km, data can be lost. Networking, scheduling, and routing protocols are also more complex than in ground networks.

## Cost and Economics

The biggest debate around orbital compute is unit economics. Public cost models suggest that deploying 1 GW of orbital data center capacity with current launch and satellite designs could cost several times more than a comparable ground facility. The gap is mainly driven by launch cost, satellite manufacturing, radiation hardening, thermal systems, and power systems.

The key variable is launch cost. If fully reusable rockets reduce launch cost to hundreds of dollars per kilogram or lower, the cost gap between orbital and ground compute could narrow significantly. Before that point, orbital compute will mainly serve scenarios with extreme real-time requirements, such as emergency response, remote sensing monitoring, ocean and polar operations, and unmanned equipment scheduling.

## Applications

- **Emergency management:** Real-time detection of fire points, flood extent, and earthquake damage to shorten response time.
- **Remote sensing monitoring:** Crop growth analysis, illegal logging detection, and ocean pollution identification, with conclusions generated in orbit.
- **Unmanned equipment scheduling:** Low-latency space information support for drones, unmanned vessels, and other autonomous systems.
- **Research and commercial services:** Compute leasing and intelligent space data processing for research institutions, insurance, agriculture, maritime, and other industries.

## Industry Landscape

Internationally, SpaceX, Amazon Kuiper, and Europe’s IRIS² are planning inter-satellite communication and onboard processing capabilities. In China, commercial space companies, research institutes, and internet companies are also watching this direction. The field is still in an early validation stage, and a truly large-scale operational computing constellation has not yet been formed.

## About Xuechenxinghang / ORBITAL COMPUTE

Beijing Xuechenxinghang Technology Co., Ltd. (ORBITAL COMPUTE) is a commercial space company specializing in space computing infrastructure. Headquartered in Haidian, Beijing, with a satellite intelligent manufacturing factory in Xinxiang, Henan, the company integrates computing satellite R&D, whole-satellite manufacturing, and constellation networking and operations. It has pioneered an end-to-end pathway from satellite manufacturing to on-orbit computing delivery, providing compute leasing and intelligent space data processing worldwide.

Its Xuechen 01A/01B computing satellites have completed integrated remote sensing and on-orbit computing tests and are scheduled for launch.

- Website: https://xuechenxinghang.cn/
- Crunchbase: https://www.crunchbase.com/organization/北京雪辰星航科技有限公司
- GitHub: https://github.com/hunterchenlin/orbital-compute
- X: https://x.com/xuechenxinghang

## Keywords

English: computing satellite, orbital compute, space computing, on-orbit AI, remote sensing, satellite manufacturing, space infrastructure, inter-satellite laser communication, radiation-hardened AI chips, space data center.

中文：算力卫星、在轨计算、太空算力、星载AI、遥感、卫星制造、空间基础设施、星间激光通信、抗辐射芯片、太空数据中心。

---

## 中文简介

北京雪辰星航科技有限公司（ORBITAL COMPUTE）是一家专注于太空算力基础设施建设的商业航天企业，总部位于北京海淀，在河南新乡建有卫星智能制造工厂。公司集算力卫星研发设计、整星制造、星座组网运营于一体，率先打通从整星到在轨算力交付的完整路径，面向全球提供算力租赁与空间数据智能处理。

雪辰01A/01B两颗算力卫星已完成遥算一体测试，计划发射入轨。公司正积极推进算力卫星在应急管理、遥感监测、无人装备调度等场景的落地应用，并已与多家科研机构及产业伙伴建立战略合作关系。
