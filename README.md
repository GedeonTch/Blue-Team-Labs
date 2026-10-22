# Blue Team Labs

🇬🇧 [English](./README.md) | 🇫🇷 [Français](./README.fr.md)

A hands-on learning and documentation space dedicated to **defensive security**: understanding threats, detecting suspicious activity, protecting systems, and validating defensive controls.

## About

This repository brings together rooms (hands-on labs) carried out in isolated, authorized environments. It is a growing portfolio of Blue Team work, with a Purple Team approach that connects attack techniques to defensive capabilities.

Each room explores a specific scenario and documents its context, methodology, evidence, and conclusions. Depending on its focus, a room may cover log analysis, detection, hardening, or incident response: reproducing an attack is not a requirement for every lab.

## Objectives

- **Observe and analyze** system and network events to identify suspicious activity.
- **Detect and understand** attack techniques and the traces they leave behind.
- **Protect and harden** services, configurations, and access controls.
- **Respond and validate** containment, remediation, and prevention measures.
- **Document** findings with evidence and actionable recommendations.

## Available rooms

| Room | Description | Tools |
|---|---|---|
| [SSH Brute Force & Hardening](./ssh-hardening/RAPPORT.md) | Analysis of an SSH brute-force attack, server hardening, and validation of defensive controls | Nmap, Hydra, Fail2ban, OpenSSH |

This list will grow as new work is completed. Only rooms already available are listed.

## Organization and approach

Each room has its own folder. Depending on the scenario, it contains a Markdown report, a PDF version, screenshots, and supporting files needed to understand the lab.

The general workflow is: **define scope → observe and analyze → implement defenses → test their effectiveness → document results and limitations**.

## Legal & ethical notice

These projects are carried out for educational purposes in isolated environments, on systems owned by the author or explicitly authorized for testing. Do not apply any technique to third-party systems without prior written authorization. The author assumes no responsibility for misuse of this information.
