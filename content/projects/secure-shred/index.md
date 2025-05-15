---
title: "Secure Data Erasure Service"
date: 2025-05-04
weight: 1
draft: false
description: "Descriptions of the various projects that the Klamath Tech Collective is engaged in."
tags: ["about", "projects", "service"]
#series: ["Documentation"]
#series_order: 1
---
## Secure Data Erasure Service – Professional Process Overview

Proper disposal of electronic devices is essential to protect sensitive information. Simply discarding hard drives or computers may leave data vulnerable to recovery. Our service ensures complete and irreversible data erasure through a standardized, technically robust process.

### Technical Process Workflow

- **Device Intake and Preparation**  
  Clients submit computers, hard drives, or solid-state drives for secure erasure. Devices are cataloged and prepared for processing.

- **Booting a Secure Erasure Environment**  
  Each device is started using a dedicated, open-source data destruction environment.[^1] This environment operates independently of the device’s original operating system, reducing the risk of residual data access.

- **Selection of Erasure Protocol**  
  The appropriate erasure protocol is chosen based on device type and client requirements. Available methods include:  
  - Multi-pass overwriting (e.g., Department of Defense 5220.22-M, RCMP, Gutmann)[^2]  
  - Hardware-based commands such as *Sanitize* or *Security Erase* for supported drives  
  These protocols are recognized by industry and government standards for secure data destruction.

- **Data Overwrite and Validation**  
  The selected protocol overwrites all addressable sectors on the storage device. Upon completion, the system performs a verification pass to confirm that no readable data remains.[^3] This validation step is essential for ensuring compliance with data privacy requirements.

- **Documentation and Certification**  
  After successful erasure and verification, clients receive a detailed certificate. This document specifies the device, the erasure method used, and confirmation of process completion. Certification provides clients with auditable proof of secure data handling.

### Service Advantages

- **Standards-Based Technical Approach:**  
  All processes adhere to recognized data sanitization standards, ensuring regulatory compliance and best practices.

- **Transparency:**  
  The erasure environment is open source, allowing for independent review of methods and results.

- **On-Premises Processing:**  
  All data erasure occurs on-site or in the presence of the client, ensuring that data never leaves their control.

- **Comprehensive Documentation:**  
  Clients receive full documentation for legal, regulatory, or internal policy requirements.

---

*Protect your privacy and the community-let us help you recycle, donate, or dispose of your devices safely and securely.*

---

[^1]: [ShredOS.x86_64 GitHub Project](https://github.com/PartialVolume/shredos.x86_64)  
[^2]: [Media Sanitization Procedure – George Mason University IT Security](https://its.gmu.edu/working-with-its/it-security-office/it-security-standards/media-sanitization-procedure/)  
[^3]: [ShredOS/README.md at master – GitHub](https://github.com/nadenislamarre/shredos/blob/master/README.md)
