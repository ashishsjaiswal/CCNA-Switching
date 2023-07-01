# CCNA-SWITCHING-LAB 2 (TRUNK)
This repository provides resources for the CCNA-SWITCHING-LAB 2 (TRUNK), a lab setup aimed at practicing and understanding Cisco switching concepts. The lab consists of five switches interconnected using trunk mode, allowing for the configuration and testing of VLANs and trunking protocols.
## Lab Diagram
The lab diagram showcases the physical connections between the five switches in the setup.

![IMG_20230603_125734](https://github.com/ashishsjaiswal/CCNA-Switching/assets/75754028/b3b805c5-f10b-4877-a97f-a4e2783f75b4)

In this lab, you will find the configuration files for each switch, allowing you to replicate the lab environment. Each switch's configuration file specifies the VLAN assignments, trunk port configurations, and other necessary settings.

## Configuration
The configuration files for all the switches and the end devices can be found in the [configurations](https://github.com/ashishsjaiswal/CCNA-Switching/tree/3e1135e130db24dd16630cab152173455a9ed3e4/CCNA-SWITCHING-LAB%201%20(TRUNK)/configurations) directory. Each file contains the necessary commands to set up the lab environment, including VLAN creation and implementation, as well as the configuration of trunk ports.

- **Switch 1 Configuration:** The configuration file **switch1.cfg** contains the commands to configure VLANs 101, 256, 112 and 512 on Switch 1. It also includes the configuration for the trunk port connecting Switch 1 to Switch 2.
- **Switch 2 Configuration:** The configuration file **switch2.cfg** contains the commands to configure VLANs 101, 256, 112 and 512 on Switch 2. It also includes the configuration for the trunk port connecting Switch 1 and Switch 3.
- **Switch 3 Configuration:** The configuration file **switch3.cfg** contains the commands to configure VLANs 101, 256, 112 and 512 on Switch 3. It also includes the configuration for the trunk port connecting Switch 2 and Switch 4.
- **Switch 4 Configuration:** The configuration file **switch4.cfg** contains the commands to configure VLANs 101, 256, 112 and 512 on Switch 4. It also includes the configuration for the trunk port connecting Switch 3 and Switch 5.
- **Switch 5 Configuration:** The configuration file **switch5.cfg** contains the commands to configure VLANs 101, 256, 112 and 512 on Switch 5. It also includes the configuration for the trunk port connecting Switch 4 to Switch 5.
- **End Device Configuration:** The configuration files **laptop.cfg** & **server.cfg** contain the basic configuration for the individual end devices (laptops) and servers connected to each switch.

## Usage
To recreate this lab environment, follow these steps refer the **Lab Diagram** given above:
1. Set up two Cisco switches and connect them using a trunk link.
2. Connect the end devices (laptops & server) to each switch using access ports.
3. Configure each switch with the provided configuration files in the [configurations](https://github.com/ashishsjaiswal/CCNA-Switching/tree/3e1135e130db24dd16630cab152173455a9ed3e4/CCNA-SWITCHING-LAB%201%20(TRUNK)/configurations) directory.
4. Use **switch1.cfg** for Switch 1, **switch2.cfg** for Switch 2, **switch3.cfg** for Switch 3, **switch4.cfg** for Switch 4 and **switch5.cfg** for Switch 5.
5. Configure each end device with the respective configuration files in the [configurations](https://github.com/ashishsjaiswal/CCNA-Switching/tree/3e1135e130db24dd16630cab152173455a9ed3e4/CCNA-SWITCHING-LAB%201%20(TRUNK)/configurations) directory. Use **laptop.cfg** to configure all the end devices (laptops) and use **server.cfg** to configure all the end devices (servers) . Verify the connectivity between the end devices and ensure that VLAN traffic is isolated correctly.

## VLAN Configuration
The switches in this lab are configured with the following VLANs:
- vlan 101 (FINANCE)
- vlan 256 (PRODUCTION)
- vlan 112 (DC)
- vlan 512 (ADMIN)

The configuration files specify the VLAN creation and assignment for each switch.

<!--- ## Troubleshooting -->

<!--- If you encounter any issues while setting up or running the lab, refer to the troubleshooting directory. It contains common problems and their possible solutions. -->

## Contributing
If you find any issues or have suggestions for improving this lab environment, feel free to open an issue or submit a pull request.

## License
This lab environment is licensed under the [MIT License](https://github.com/ashishsjaiswal/CCNA-Switching/blob/00ddc3eca4f2c1c0442ba43d91cabefb51a138cd/LICENSE).
