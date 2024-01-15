# WireGuard Implementation Playground

This repository serves as a personal playground to explore and compare various WireGuard VPN implementations, with a focus on those under the MIT License.

## Project Purpose

The primary objective is to provide a hands-on environment for practicing and evaluating the performance characteristics of different WireGuard implementations. It's a project born out of curiosity and a desire for deeper understanding, rather than for production use.

## Approach

We utilize Docker containers to host the WireGuard instances, creating an isolated and controlled setup for testing. The performance analysis is conducted using the [iperf](https://github.com/esnet/iperf) tool, which offers reliable network throughput measurements.

## Flexibility and Customization

The project is designed to be flexible, allowing for customization of key parameters such as CPU core allocation and specific WireGuard version settings. A default bash script configuration is included, primarily for quick setup and potential integration with GitHub Actions for automated testing.

## GitHub Actions Integration [ToDo]

Plans are in place to integrate with GitHub Actions, automating the testing process for consistent and repeatable results. This will aid in continuous exploration and comparison as new versions and implementations emerge.

## Getting Started[ToDo]

Instructions for setup and usage are provided, ensuring an easy start for those interested in exploring WireGuard implementations. This project is ideal for both seasoned developers and novices in the realms of Docker, VPNs, and network performance testing.

---
