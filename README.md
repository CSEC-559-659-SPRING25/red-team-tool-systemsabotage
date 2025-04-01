# Service Saboteur Tool

## Author: William Faber  
**Email**: wmf1426@rit.edu

---

## Description

The **Service Saboteur** is a Python-based tool designed to sabotage critical services during red team operations, specifically targeting services such as **nginx**, **mysql**, and **samba**. The tool provides functionality to:

- **Stop and disable services**.
- **Inject invalid configurations** to cause disruptions.
- **Restore services** to their original state after sabotage.

This tool is designed to simulate attacks during the **CSEC 473 – Cyber Defense Techniques** competition, where the objective is to disrupt services and challenge the blue team’s ability to react and recover.

---

## Features

- **Service Sabotage**: Stops and disables services like `nginx`, `mysql`, `samba`, and more.
- **Configuration Injection**: Injects invalid configurations to break the target services.
- **Service Restoration**: Restores services from their backup configurations.
- **Stealthy Execution**: Commands are executed quietly, with no output to the user unless verbose mode is enabled.
- **Flexible**: Can be extended to support additional services.

---

## Requirements

- **Python 3.x**
- **Administrative privileges** on the target system (to stop/start services and modify configurations)

---

## Installation

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/yourusername/Service-Saboteur.git
