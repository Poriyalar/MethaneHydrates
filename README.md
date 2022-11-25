# MethaneHydrates

<h3>Usage</h3>
<h5>Hydrate Stability</h5>
The methane hydrate stability equation is coded as a global function using MS-Excel Macros (VBA). The excel sheet with an example calculation is provided here. 

Example --> hydp(285,35)   

Result --> 10.4682   

The first input is temperature in K and the second input is salinity in PPT (parts per thousand). The output is the minimum pressure in MPa for methane hydrate stability for specified conditions. Any pressures above this value are hydrate stable.

<h5>Methane Solubility</h5>
The methane solubility equation is coded as a global function using MS-Excel Macros (VBA). The excel sheet with an example calculation is provided here. This function predicts methane solubility in aqueous phase in methane hydrate stable conditions.

Example --> methhyd(285,35,11)   

Result --> 0.1029
   
The first input is temperature in K, the second input is salinity in PPT (parts per thousand) and the third input is pressure in MPa. The pressure input should be above the hydrate stable pressure. The output is the methane solubility in aqueous phase in the presence of hydrates in molality units (mol/kg of water)


<h3>Acknowledgement</h3>

This work was supported by the [SEAMSTRESS project](https://site.uit.no/seamstress/). The SEAMSTRESS project is supported by the Tromsø Research Foundation (TFS) and the Research Council of Norway (RCN-Frinatek) through two starting grants awarded to Andreia Plaza-Faverola. In addition, the Faculty of Science and Technology, the Department of Geosciences at UiT, and the Center for Arctic gas hydrates, environment and climate (CAGE) provide significant support to the project.
