# Chemnode LTE | LoRa PSOC5 Firmware

## Version v92.04.33 - Stable

# What's New?

	- added USB output with sensor data

	Example Output:
	
	```
		0.051726,-0.037169,0.039155,0.572270,0.022382,-0.048760,0.570927,0.076997,-0.016701,-0.170870,0.586684,-0.003257,0.00,0.00,0.00,55.3,0.01,3.83,23.5,3,5,6,6,17,22,23.777742,24,24,0.79,0,AA-59-38-29,36,22,22,22,22,21,22,22,21,22,22,22,22,22,22,22,22,22,22,22,22,21,22,22,22,22,22,22,22,22,21,22,22,22,23,22,22,21,21,22,22,22,21,23,22,21,21,21,21,22,22,22,22,22,20,21,21,22,21,21,21,21,22,21,21,123
	```

	Data format:
	```
	Indexes		Description		Unit
	0 - 11		GasSensor		V
	12			Temperature		ºC
	13			Pressure		Pa
	14			Humidity		%RH
	15			Battery Charge	%
	16			Net Current		A
	17			Tension			V
	18			Battery Temp 	ºC
	19			PM 1.0			µg/m³
	20			PM 2.5			µg/m³
	21			PM 4.0			µg/m³
	22			PM 10.0			µg/m³
	23			PM 1.0			1/cm³
	24			PM 2.5			1/cm³
	25 			PM 4.0			1/cm³
	26 			PM 10.0			1/cm³
	27			PM Typ Size		µm
	28			CO2				ppm
	29			Station ID		
	30			msg counter
	31 - 94		IRCamera Pixels	ºC
	95			Packt CheckSum
	```	

# Known Bugs

	- resets at usb connection / disconnection


## Environment:
PSoC Creator  4.4 (4.4.0.80)
Culture: English (United States)
OS Version: Microsoft Windows NT 10.0.22000.0
CLR Version: 4.0.30319.42000

Installed CyInstaller Products:
Peripheral Driver Library 3.1.3
Peripheral Driver Library 3.1.5
PSoC Programmer 3.29.1
PSoC Creator 4.4

Loaded Plugins:
Name: Customizer Loader
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Loads component customizers.

Name: Addin Discovery
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Discovers PSoC Creator addins (kits, language packs, etc)

Name: Device Catalog
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Device Catalog Plugin

Name: Documentation
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Adds the topics available in the documentation.

Name: Start Page
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Adds a start page to the framework.

Name: Output Window Plugin
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Adds the output window

Name: SCC Manager
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: The Source Code Control Manager is the central class used for SCC actions within PSoC Creator.

Name: Symbol, Schematic and SchMacro Factory
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: The Symbol and Schematic Factory is used to load, cache, and retrieve symbols and schematics.

Name: Project Manager Plugin
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Adds project management related functionality.

Name: GDE Plugin
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Loads the Symbol and Schematic editors

Name: Language Plugin
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Supports user files in multiple languages

Name: Workspace Factory
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: The Workspace Factory is used to retrieve instances of PSoC Creator workspaces.

Name: Project Factory
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: The Project Factory is used to retrieve instances of PSoC Creator projects.

Name: Toolchain Manager
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: PSoC Creator Toolchain Manager

Name: ARM GCC Generic
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: ARM GNU Generic

Name: ARM MDK Generic
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: ARM MDK Generic

Name: ARM IAR Generic
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: ARM IAR Generic

Name: DP8051 Keil Generic
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: DP8051 Keil Generic

Name: Device Selector
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Adds a dialog that allows the user to select a device.

Name: File Editor Factory Plugin
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Add file editors to the framework.

Name: Transport Framework
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Provides a generic device communication framework for use by other plugins.

Name: Debugger Core
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: The Core Debugger provides an architecture independent framework for the common debug features.

Name: PSoC Debugger
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Provides debugging support for the different PSoC families through a GDB back end.

Name: FM Debugger
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Provides debugging support for FM device families

Name: Device IO Transport
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Provides device IO support for Cypress devices though PSoC Programmer APIs.

Name: Serial Transport
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Provides basic serial device support for the rest of the tool.

Name: Bootloader Host
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Provides a host tool to perform bootloading operations.

Name: Background Elaborator
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: PSoC Creator Background Elaborator.

Name: TypeCache Factory
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: The TypeCache Factory is used to retrieve instances of TypeCaches.

Name: PSoC Fitter
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: PSoC Fitter Plugin

Name: FM Fitter
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: FM Fitter Plugin

Name: DWR Plugin
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Registers resource editors with devices.

Name: DMA Wizard
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Enables quick and correct development of applications that use DMA.

Name: Tuner Plugin
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: Manages custom component tuner executables

Name: Notice Window
Version: 4.4.0.80
Company: Cypress Semiconductor
Description: The Notice Window displays notices (status messages / errors with managed lifetimes).

