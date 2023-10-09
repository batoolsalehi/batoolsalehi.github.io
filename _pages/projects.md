---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

A selection on my research work are highlighted below.

**Interacting Real World and Digital Twins for Wireless Beamforming**
<img align="right" width="40%" src="/images/Multiverse.png">
<div style="text-align: justify; font-size: 16px">Creating a digital world that closely mimics the real world with its many complex interactions and outcomes is possible today through advanced emulation software and ubiquitous computing power. Such a software-based emulation of an entity that exists in the real world is called a ‘digital twin’. In this paper, we consider a twin of a wireless millimeter- wave band radio that is mounted on a vehicle and show how it speeds up directional beam selection in mobile environments. To achieve this, we go beyond instantiating a single twin and propose the ‘Multiverse’ paradigm, with several possible digital twins attempting to capture the real world at different levels of fidelity. Towards this goal, this paper describes (i) a decision strategy at the vehicle that determines which twin must be used given the computational and latency limitations, and (ii) a self- learning scheme that uses the Multiverse-guided beam outcomes to enhance DL-based decision-making in the real world over time. Our work is distinguished from prior works as follows: First, we use a publicly available RF dataset collected from an autonomous car for creating different twins. Second, we present a framework with continuous interaction between the real world and Multiverse of twins at the edge, as opposed to a one- time emulation that is completed prior to actual deployment. Results reveal that Multiverse offers up to 79.43% and 85.22% top-10 beam selection accuracy for LOS and NLOS scenarios, respectively. Moreover, we observe 52.72 − 85.07% improvement in beam selection time compared to 802.11ad standard.</div>

- Publication: **B. Salehi**, U. Demir, D. Roy, S. Pradhan, J. Dy, S. Ioannidis, K. Chowdhury, “Multiverse at the Edge: Interacting Real World and Digital Twins for Wireless Beamforming. [pdf](https://browse.arxiv.org/pdf/2305.10350.pdf)


<hr style="border-top: dashed 2px;" />
<!-- <p>&nbsp;</p> -->

**Digital Twin Assisted Robot Navigation and WIreless Network Management**
<img align="right" width="40%" src="/images/darwin.png">
<div style="text-align: justify; font-size: 16px">Automated warehouses involve robots that move across the floor, avoiding obstacles while remaining connected wirelessly to a central controller by associating with an access point (AP). The complex propagation environment and presence of large metallic surfaces results in spotty coverage, which may change over time as the location of stored products and machinery changes. Thus, maintaining an assured connectivity to an AP while performing navigation tasks is a challenge, although it is needed to relay local sensor data from the robots to the controller and receive safety directions from the latter. Our proposed solution, called DARWIN, involves creating a digital twin of the warehouse for training the robots by jointly optimizing the navigation tasks and avoiding wireless signal deadspots. DARWIN has three key capabilities: First, it captures the features of both the physical and RF environment in software, which can be used to generate synthetic datasets. Second, it allows real-time updating of the digital twin if significant disparity is detected compared to the physical environment. Finally, it includes a reinforcement learning algorithm that jointly optimizes navigation and network resource management. We show how DARWIN can be used to train a reinforcement learning model for handover among APs.</div>

- Publication: **B. Salehi**, D. Roy, M. Eisen, A. Baxi, D. Cavalcanti, K. Chowdhury, “DARWIN: Digital Twin Assisted Robot Navigation and WIreless Network Management”, under review (in collaboration with Intel corporation).


<hr style="border-top: dashed 2px;" />
<!-- <p>&nbsp;</p> -->



**Multimodal Beamforming in Vehicular Networks**
<img align="right" width="40%" src="/images/multimodalbeamforming.png">
<div style="text-align: justify; font-size: 16px">Fast sector-steering in the mmWave band for vehicular mobility scenarios remains an open challenge. This is because standard-defined exhaustive search over predefined antenna sectors cannot be assuredly completed within short contact times. This paper proposes machine learning to speed up sector selection using data from multiple non-RF sensors, such as LiDAR, GPS, and camera images. The contributions in this paper are threefold: First, a multimodal deep learning architecture is proposed that fuses the inputs from these data sources and locally predicts the sectors for best alignment at a vehicle. Second, it studies the impact of missing data (e.g., missing LiDAR/images) during inference, which is possible due to unreliable control channels or hardware malfunction. Third, it describes the first-of-its-kind multimodal federated learning framework that combines model weights from multiple vehicles and then disseminates the final fusion architecture back to them, thus incorporating private sharing of information and reducing their individual training times. We validate the proposed architectures on a live dataset collected from an autonomous car equipped with multiple sensors (GPS, LiDAR, and camera) and roof-mounted Talon AD7200 60GHz mmWave radios. We observe 52.75% decrease in sector selection time than 802.11ad standard while maintaining 89.32% throughput with the globally optimal solution.</div>

- Publication:
- **B. Salehi**, J. Gu, D. Roy, and K. Chowdhury, “FLASH: Federated Learning for Automated Selection of High-band mmWave Sectors” IEEE International Conference  on Computer Communication (INFOCOM 2020).

- **B. Salehi**, G. Reus-Muns, D. Roy, Z. Wang, T. Jian, J. Dy, S. Ioannidis, and K. Chowdhury, “Deep Learning on Multimodal Sensor Data at the Wireless Edge for Vehicular Network” IEEE Transactions on Vehicular Technology (2022).

- D .Roy, **B. Salehi**, S. Banou, S. Mohanti, G. Reus-Muns, M. Belgiovine,P. Ganesh, C. Dick, K. Chowdhury, “Going beyond RF: A survey on how AI-enabled multimodal beamforming will shape the NextG standard”, Computer Networks (2023).
- **B. Salehi**, M. Belgiovine, S. Garcia Sanchez, J. Dy, S. Ioannidis, K. Chowdhury, “Machine Learning on Camera Images for Fast mmWave Beamforming” IEEE International Conference of Mobile Ad-Hoc and Smart Systems (MASS 2020). 

<hr style="border-top: dashed 2px;" />
<!-- <p>&nbsp;</p> -->
