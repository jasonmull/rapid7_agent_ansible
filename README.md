# Rapid7 Agent Ansible Role

Simple Ansible role to install Rapid7 Insight Agent on Windows systems.

## Requirements

- Windows target with WinRM configured
- Valid Rapid7 token

## Role Variables

```yaml
rapid7_token: "us:your-uuid-here"  # Required
rapid7_config_path: "C:\\Windows\\Temp"  # Optional