# Explaining CCNA Switching: Cisco Switch Features, VLANs, and Configuration Guide

This repository provides information and resources related to Cisco CCNA Switching. In this readme file, we will cover various topics related to Cisco switches and their functionalities. Whether you are a beginner or looking to refresh your knowledge, this guide will help you understand the fundamental concepts of Cisco switches.

## Cisco Switch Features

Cisco switches are versatile networking devices that enable the creation and management of local area networks (LANs). They offer a wide range of features, including:
- High-speed Ethernet connectivity
- VLAN support for network segmentation
- Quality of Service (QoS) capabilities for prioritizing network traffic
- Spanning Tree Protocol (STP) for loop prevention
- Link Aggregation for increased bandwidth and redundancy
- Security features such as Access Control Lists (ACLs) and port security
- Multilayer switching for improved performance
- Power over Ethernet (PoE) support for powering network devices

## Cisco Switch Software - IOS

Cisco switches run on Cisco Internetwork Operating System (IOS), which is a robust and feature-rich software that provides the necessary functionality to manage and control the switch. IOS offers a command-line interface (CLI) through which administrators can configure and monitor the switch. It also supports various protocols and features for network connectivity, security, and management.

## Cisco Switch Memory Types

Cisco switches have different types of memory, including:

- __Flash memory:__ It stores the operating system image (IOS), configuration files, and other software components.
- __Random Access Memory (RAM):__ It provides temporary storage for running processes, routing tables, and other dynamic data.
- __Non-Volatile Random Access Memory (NVRAM):__ It holds the switch's startup configuration, which is retained even after a power cycle.
- __Read-Only Memory (ROM):__ It contains the boot loader, which initiates the boot process and loads the IOS image.

## Cisco Switch Boot Process

When a Cisco switch powers on, it goes through the following boot process:

1. __Power-on self-test (POST):__ The switch performs a series of diagnostic tests to ensure hardware functionality.
2. __Boot loader:__ The boot loader is responsible for loading the IOS image from flash memory into RAM.
3. __IOS initialization:__ The IOS image is loaded and initialized, and the switch becomes operational.
4. __Configuration loading:__ If a startup configuration is present in NVRAM, it is loaded and applied to the switch.
5. __Switch operation:__ The switch is ready to process network traffic and execute the configured commands.

## How to Access a Switch for the First Time

To access a Cisco switch for the first time, follow these steps:

1. Connect your computer to the switch using an Ethernet cable.
2. Connect to the switch's console port using a console cable.
3. Open a terminal emulation program (such as PuTTY or SecureCRT) on your computer.
4. Configure the terminal emulation program with the appropriate settings: baud rate (usually 9600), data bits (usually 8), parity (usually none), stop bits (usually 1), and flow control (usually none).
5. Power on the switch.
6. The switch will display boot messages in the terminal emulation program.
7. Once the switch is booted and ready, you will see the command prompt, indicating that you have console access to the switch.

## Console Access of Cisco Switch

Console access provides direct access to the switch's CLI. To establish console access:

1. Connect your computer to the switch's console port using a console cable.
2. Launch a terminal emulation program on your computer.
3. Configure the terminal emulation program with the appropriate settings (baud rate, data bits, parity, stop bits, flow control).
4. Power on the switch.
5. The switch's console messages will appear in the terminal emulation program, allowing you to interact with the switch using the CLI.


## Different Types of CLI Modes in Switch

Cisco switches have different CLI modes, which provide varying levels of access and functionality:

1. User mode (also known as Enable mode): This is the default mode after logging into the switch. It provides basic monitoring and troubleshooting capabilities but doesn't allow configuration changes.
2. Privilege mode (also known as Exec mode): This mode grants elevated privileges to execute privileged commands, view configuration, and perform basic system administration tasks.
3. Configure mode (also known as Global configuration mode): In this mode, you can make changes to the switch's configuration. It allows you to configure global settings that affect the switch as a whole.
4. Interface mode: This mode is used to configure individual switch interfaces, such as Ethernet ports or VLAN interfaces. It allows you to set specific parameters for each interface.

## Switch Basic Commands

Here are some common basic commands used in Cisco switches:

- ___show interfaces:___ Displays information about the switch interfaces.
- ___show running-config:___ Shows the current running configuration of the switch.
- ___show vlan:___ Provides details about VLAN configuration and membership.
- ___show mac address-table:___ Displays the MAC address table, which maps MAC addresses to switch ports.
- ___ping:___ Tests network connectivity to a specified destination IP address.
- ___copy running-config startup-config:___ Saves the running configuration to the startup configuration, which will be loaded on the next boot.

## About Virtual LAN (VLAN)

Virtual LAN (VLAN) is a logical segmentation of a switch or network, allowing different groups of devices to be logically grouped together, even if they are physically connected to different switch ports. VLANs provide enhanced security, improved network performance, and simplified management by isolating traffic and reducing broadcast domains.

## Static VLAN, Dynamic VLAN, Native VLAN, and Voice VLAN

- Static VLAN: In a static VLAN configuration, administrators manually assign ports to specific VLANs. It is a common method for segmenting a network based on logical requirements.
- Dynamic VLAN: Dynamic VLANs use protocols such as VLAN Trunking Protocol (VTP) or Generic VLAN Registration Protocol (GVRP) to automate VLAN assignment. Ports dynamically join a VLAN based on the information received from the VTP server or GVRP advertisements.
- Native VLAN: The native VLAN is used for untagged traffic on a VLAN trunk link. It is typically used for communication between switches when the trunk link carries multiple VLANs.
- Voice VLAN: Voice VLANs are dedicated VLANs used to carry voice traffic for VoIP phones. They provide Quality of Service (QoS) and prioritize voice traffic to ensure clear and reliable communication.

## Switch Ports Mode - Access Mode and Trunk Mode

- __Access mode:__ Access ports are used to connect end devices to the switch. They belong to a single VLAN and carry untagged traffic. Access ports are typically configured with a specific VLAN ID.
- __Trunk mode:__ Trunk ports are used to carry traffic between switches or to connect switches to routers. They can carry traffic for multiple VLANs simultaneously, using VLAN tagging. Trunk ports use protocols such as IEEE 802.1Q or ISL to tag VLAN traffic.

## Configure LAN Network with VLAN and Trunk

To configure a LAN network with VLANs and trunking:

1. Define the VLANs you need and assign them appropriate VLAN IDs.
2. Assign switch ports to specific VLANs using access mode or configure trunk ports for inter-switch connections.
3. Configure VLAN interfaces or Layer 3 interfaces on the switch for inter-VLAN routing if required.
4. Implement VLAN tagging and trunking protocols on trunk ports to allow traffic from multiple VLANs to pass between switches.
5. Configure VLAN-specific settings, such as VLAN names, IP addresses, and VLAN membership.

#### By following these steps, you can create a LAN network with VLANs and trunking to achieve logical segmentation and efficient traffic flow.
 
#### This repository provides a comprehensive overview of CCNA Switching topics such as.
 __1. Explain Switching__
 
 __2. Explain Inter-VLAN Routing__
 
 __3. Explain Router on Stick (Sub-Interface)__

#### Feel free to explore the different sections and dive deeper into each subject to enhance your understanding of Cisco switching concepts.
