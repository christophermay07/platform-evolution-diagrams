# Platform Evolution Diagrams

Architecture diagrams build to demonstrate the modernization of a disconnected edge platform, from an initial state of VMware, to subsequent states using OpenShift + OpenShift Virtualization. The target and future states are installed and configured by Ansible.

## Overview

The repo contains Mermaid diagrams illustrating a platform evolution across several stages:

* [Initial State](architecture-initial-state.md)
* Target State (TODO)
* Future State (short-term) (TODO)
* Future State (long-term) (TODO)

## Context

These edge sites are fully disconnected, i.e., no internet access. All software is delivered via physical installation media, and site-specific configuration (domains, certificates, credentials) is applied locally at deploy time. This air-gapped constraint drives many of the architectural and automation decisions throughout the evolution.

## Usage

Diagrams are written in [Mermaid](https://mermaid.js.org/) and can be rendered in any Mermaid-compatible viewer, including GitHub!
