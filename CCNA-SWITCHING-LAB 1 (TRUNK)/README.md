# CCNA-SWITCHING-LAB 1 (TRUNK)
This repository provides the configuration and setup for a CCNA Switching lab, focusing on the use of trunk mode to connect two switches and the configuration of VLANs. The lab consists of two switches and four individual end devices (laptops) connected to each switch using access mode. The switches are configured with four VLANs: VLAN 414, VLAN 115, VLAN 113, and VLAN 501.
## Raw Diagram
![IMG_20230603_125700](https://github.com/ashishsjaiswal/CCNA-Switching/assets/75754028/56165059-fbe8-44bb-b777-8711db119492)

## Lab Diagram
The following diagram illustrates the setup of the lab:


                +--------------------+        Trunk        +--------------------+
                |       Switch 1     |---------------------|       Switch 2     |  
                +--------------------+                     +--------------------+
              /   |                  |   \              /   |                  |   \
        Laptop1  Laptop2        Laptop3 Laptop4    Laptop5 Laptop6         Laptop7 Laptop8

## Configuration
The configuration files for both switches and the end devices can be found in the [configurations](https://github.com/ashishsjaiswal/CCNA-Switching/tree/3e1135e130db24dd16630cab152173455a9ed3e4/CCNA-SWITCHING-LAB%201%20(TRUNK)/configurations) directory. Each file contains the necessary commands to set up the lab environment, including VLAN creation and implementation, as well as the configuration of trunk ports.

- **Switch 1 Configuration:** The configuration file **switch1.cfg** contains the commands to configure VLANs 414, 115, 113, and 501 on Switch 1. It also includes the configuration for the trunk port connecting Switch 1 to Switch 2.
- **Switch 2 Configuration:** The configuration file **switch2.cfg** contains the commands to configure VLANs 414, 115, 113, and 501 on Switch 2. It also includes the configuration for the trunk port connecting Switch 2 to Switch 1.
- **End Device Configuration:** The configuration files **laptop.cfg** contain the basic configuration for the individual end devices (laptops) connected to each switch.

## Usage
To recreate this lab environment, follow these steps:
1. Set up two Cisco switches and connect them using a trunk link.
2. Connect the four individual end devices (laptops) to each switch using access ports.
3. Configure each switch with the provided configuration files in the [configurations](https://github.com/ashishsjaiswal/CCNA-Switching/tree/3e1135e130db24dd16630cab152173455a9ed3e4/CCNA-SWITCHING-LAB%201%20(TRUNK)/configurations) directory. Use **switch1.cfg** for Switch 1 and **switch2.cfg** for Switch 2.
4. Configure each end device with the respective configuration files in the [configurations](https://github.com/ashishsjaiswal/CCNA-Switching/tree/3e1135e130db24dd16630cab152173455a9ed3e4/CCNA-SWITCHING-LAB%201%20(TRUNK)/configurations) directory. Use **laptop.cfg** to configure all the end devices (laptops). Verify the connectivity between the end devices and ensure that VLAN traffic is isolated correctly.

## VLAN Configuration
The switches in this lab are configured with the following VLANs:
- VLAN 414
- VLAN 115
- VLAN 113
- VLAN 501

The configuration files specify the VLAN creation and assignment for each switch.

<!--- ## Troubleshooting -->

<!--- If you encounter any issues while setting up or running the lab, refer to the troubleshooting directory. It contains common problems and their possible solutions. -->

## Contributing
If you find any issues or have suggestions for improving this lab environment, feel free to open an issue or submit a pull request.

## License
This lab environment is licensed under the [MIT License][(https://github.com/ashishsjaiswal/CCNA-Switching/blob/00ddc3eca4f2c1c0442ba43d91cabefb51a138cd/LICENSE)].
