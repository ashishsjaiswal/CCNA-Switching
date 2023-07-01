# CCNA-SWITCHING-LAB 2 (TRUNK)
This repository provides resources for the CCNA-SWITCHING-LAB 2 (TRUNK), a lab setup aimed at practicing and understanding Cisco switching concepts. The lab consists of five switches interconnected using trunk mode, allowing for the configuration and testing of VLANs and trunking protocols.
## Lab Diagram
The lab diagram showcases the physical connections between the five switches in the setup.

![IMG_20230603_125734](https://github.com/ashishsjaiswal/CCNA-Switching/assets/75754028/602e16c1-e1b1-4927-a2c3-6de4e740d3b0)


In this lab, you will find the configuration files for each switch, allowing you to replicate the lab environment. Each switch's configuration file specifies the VLAN assignments, trunk port configurations, and other necessary settings.

## Lab Instructions
- Connect the switches using trunk ports as per the lab diagram.
- Configure each switch based on the provided configuration files.
- Connect end devices to the switches' access ports, assigning them appropriate VLANs.
- Verify connectivity between the end devices and ensure proper VLAN communication across the switches.

## Usage
To recreate this lab environment, follow these steps refer the **Lab Diagram** given above:
1. Set up five Cisco switches and connect them using a trunk link.
2. Connect the end devices (laptops & server) to each switch using access ports.
3. Configure each switch with the provided configuration files in the [configurations](https://github.com/ashishsjaiswal/CCNA-Switching/tree/08babd9a9238abf77f8753b0a97aecc41742cab9/CCNA-SWITCHING-LAB%202%20%20(TRUNK)/configurations) directory.
4. Use **switch1.cfg** for Switch 1, **switch2.cfg** for Switch 2, **switch3.cfg** for Switch 3, **switch4.cfg** for Switch 4 and **switch5.cfg** for Switch 5.
5. Configure each end device with the respective configuration files in the [configurations](https://github.com/ashishsjaiswal/CCNA-Switching/tree/08babd9a9238abf77f8753b0a97aecc41742cab9/CCNA-SWITCHING-LAB%202%20%20(TRUNK)/configurations) directory. Use **enddevices.cfg** to configure all the end devices (laptops and servers). Verify the connectivity between the end devices and ensure that VLAN traffic is isolated correctly.

## Switch Configurations

The configuration files for all the switches and the end devices can be found in the [configurations](https://github.com/ashishsjaiswal/CCNA-Switching/tree/08babd9a9238abf77f8753b0a97aecc41742cab9/CCNA-SWITCHING-LAB%202%20%20(TRUNK)/configurations) directory. Each file contains the necessary commands to set up the lab environment, including VLAN creation and implementation, as well as the configuration of trunk ports.

- Switch 1: **switch1.cfg**
- Switch 2: **switch2.cfg**
- Switch 3: **switch3.cfg**
- Switch 4: **switch4.cfg**
- Switch 5: **switch5.cfg**

Please refer to the individual configuration files for detailed switch.

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

