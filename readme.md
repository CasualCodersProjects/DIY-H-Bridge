# Casual Coders DIY H-Bridge Kit
The H-Bridge is a simple circuit which enables the user to switch the polarity of a voltage across it's output terminals. This is often necessary to allow bidirectional control of DC motors.  

This DIY Kit includes:
- 2x Base PCBs which must be populated with 2x NMOS and 2x PMOS each. This board has built in Pull-Down reistors and PMOS Drivers.
- 2.54mm pitch header pins for logic inputs.
- 60V MAX input voltage.

This kit is designed such that the user may select their own MOSFETS specific to their application. This facilitates learning about mosfet characteristics and allows you to optimize characristics such as on resistance, gate threshold, drain-source voltage, and more. As such, this is essentially an Application Specific H Bridge.

You may instead elect to select a premade configuration by Casual Coders. Our premade configuration should be functional for most applications, but is comprablly costly. We include:
- 4x [MPG50N06](https://datasheet.lcsc.com/lcsc/2206211730_Minos-MPG50N06_C2980287.pdf) (NMOS) with an Id of 50A, on Resistance of 12.5mΩ, and Vds of 60V.
- 4x [IFR9Z34NPBF](https://www.infineon.com/dgdl/irf9z34npbf.pdf?fileId=5546d462533600a40153561220af1ddd) (PMOS) with an Id of -19A, on Resistance of 100mΩ, and Vds of -55V.
- 4x Screw Terminals.  

Diagram:  
![Diagram](./Assets/Images/Mechanical%20Drawing.svg)
