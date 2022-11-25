# MethaneHydrates

<h2>Introduction</h2>
Gas hydrates are crystalline solids that exist typically below the ocean floor at greater depths. These hydrates are observed around 200m below the ocean floor at the Vestnesa Ridge. (Plaza-Faverola et al., 2017). Simple methods to model hydrate stable conditions help develop first order approximate estimates prior to performing complex calculations. Such estimates help build conceptual models about the myriad problems related to Vestnesa Ridge. The hydrate stability was estimated using Tishchenko’s result (Tishchenko et al., 2005). Brief description about the approach, equation used, and results are shown below.

<h2>Usage</h2>
<h4>Hydrate Stability</h4>
The methane hydrate stability equation is coded as a global function using MS-Excel Macros (VBA). The excel sheet with an example calculation is provided here. 

Example --> hydp(285,35)   

Result --> 10.4682   

The first input is temperature in K and the second input is salinity in PPT (parts per thousand). The output is the minimum pressure in MPa for methane hydrate stability for specified conditions. Any pressures above this value are hydrate stable.

<h4>Methane Solubility</h4>
The methane solubility equation is coded as a global function using MS-Excel Macros (VBA). The excel sheet with an example calculation is provided here. This function predicts methane solubility in aqueous phase in methane hydrate stable conditions.

Example --> methhyd(285,35,11)   

Result --> 0.1029
   
The first input is temperature in K, the second input is salinity in PPT (parts per thousand) and the third input is pressure in MPa. The pressure input should be above the hydrate stable pressure. The output is the methane solubility in aqueous phase in the presence of hydrates in molality units (mol/kg of water)

<h2>References</h2>
<p> Pitzer, K.S., 1991. Ion interaction approach: theory and data correlation. Activity coefficients in electrolyte solutions, 2, pp.75-153.</p>
    <p> Plaza‐Faverola, A., Vadakkepuliyambatta, S., Hong, W.L., Mienert, J., Bünz, S., Chand, S. and Greinert, J., 2017. Bottom‐simulating reflector dynamics at Arctic thermogenic gas provinces: An example from Vestnesa Ridge, offshore west Svalbard. Journal of Geophysical Research: Solid Earth, 122(6), pp.4089-4105.</p>
    <p> Ruppel, C.D. and Waite, W.F., 2020. Timescales and Processes of Methane Hydrate Formation and Breakdown, With Application to Geologic Systems. Journal of Geophysical Research: Solid Earth, 125(8).</p>
    <p> Sun, R. and Duan, Z., 2007. An accurate model to predict the thermodynamic stability of methane hydrate and methane solubility in marine environments. Chemical geology, 244(1-2), pp.248-262.</p>
    <p> Tishchenko, P., Hensen, C., Wallmann, K. and Wong, C.S., 2005. Calculation of the stability and solubility of methane hydrate in seawater. Chemical geology, 219(1-4), pp.37-52.</p>

<h2>Acknowledgement</h2>
This work was supported by the [SEAMSTRESS project](https://site.uit.no/seamstress/). The SEAMSTRESS project is supported by the Tromsø Research Foundation (TFS) and the Research Council of Norway (RCN-Frinatek) through two starting grants awarded to Andreia Plaza-Faverola. In addition, the Faculty of Science and Technology, the Department of Geosciences at UiT, and the Center for Arctic gas hydrates, environment and climate (CAGE) provide significant support to the project.
