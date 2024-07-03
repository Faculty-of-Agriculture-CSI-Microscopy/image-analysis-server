# Remote Desktop vs. Network Folder Mapping: Data Management on Windows

## Introduction
Understanding when to use a remote desktop or map a network folder is crucial for efficient data management. This guide will help you decide which method you need based on different scenarios.
- [Image Analysis Server Access - For HUJI Users](https://drive.google.com/file/d/118CQXZPBCW-mHCuB_DfPmw-stnbfy4up/view?usp=sharing)

## Decision-Making Flowchart

```mermaid
graph TD;
    A[Do you need to run applications on the remote machine?] -->|Yes| B[Use Remote Desktop]
    A -->|No| C[Do you need to access files from a remote location?]
    C -->|Yes| D[Map a Network Folder on your HUJI-connected PC]
    C -->|No| E[Local Access or Other Solutions]

    B --> F[High-security access or resource-intensive tasks]
    D --> G[Collaborative work and file sharing]
