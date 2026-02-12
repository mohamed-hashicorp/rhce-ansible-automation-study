# RHCE Study Guide - Lab Code & Exercises
This is personal study repository for the **Red Hat Certified Engineer (RHCE)** certification. This repo contains the code, playbooks, and configuration files I developed while working through the study guide.

## About the repo
This repository is a collection of hands-on exercises designed to help master Ansible and RHEL automation. To keep things organized and easy to reference, the code is **divided into chapters** that mirror the structure of the book.

The focus of this code includes:
* **Ansible Fundamentals:** Inventories, playbooks, and ad-hoc commands.
* **Automation:** Managing system administration tasks through code.
* **Best Practices:** Using roles, variables, and templates efficiently.

## Repository Structure
The project is organized by chapter to align with the curriculum:

| Chapter | Topic | Description |
| :--- | :--- | :--- |
| **Chapter 01** | Getting Started | Setting up the control node and managed hosts. |
| **Chapter 02** | Ansible Ad-Hoc | Running quick commands across the inventory. |
| **Chapter 03** | Playbooks | Writing and executing YAML-based playbooks. |
| **Chapter 04** | Variables & Facts | Managing dynamic data and system information. |
| **Chapter 05** | Task Control | Using loops, conditionals, and handlers. |
| **Chapter 06** | File Deployment | Working with templates (Jinja2) and file modules. |
| **Chapter 07** | Ansible Roles | Organizing playbooks into reusable structures. |

## Lab Environment & Execution Details

All labs and exercises in this repository were executed from my local laptop, which acted as the Ansible control node.

The Ansible managed hosts were Linux servers deployed on AWS.

### Important Notes:
- Inventory files included in this repository are environment-specific.
- You must update the inventory files to match your own hostnames, IP addresses, SSH users, and key paths.
- Ensure your managed nodes are reachable from your control node and meet the required RHEL/Ansible prerequisites.