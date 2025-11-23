---
title: Software Proposal
---

### System Flow Overview

The diagram illustrates the core operation of the Water Detection Subsystem. The system runs in a continuous loop, initializing the PIC18F57Q43 microcontroller, reading sensor inputs, updating states based on humidity, pressure loss, or water detection, and setting outputs accordingly. Each detection condition activates its corresponding LED indicator.

> **Note:** If any of the outputs—**humidity**, **pressure loss**, or **water**—are detected, the **alarm will be triggered**.


![showcase](images/Team%20Software%20Proposal.drawio.png)
