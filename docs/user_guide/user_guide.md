# Parameters and Assumptions for Reference Designs

Due to the several technologies that are integrated across these hybrid designs, there are many
input parameters and values to define. In the input files for each reference design, there are
comments specifying where the values are taken from, when necessary. Additionally, a write-up of
the hybrid reference designs is available [here](Reference_Design_Documentation.pdf).
The overlying assumptions and important parameter values for each technology are summarized below.
For further detail and insight, the user is directed to the document above.

Below, in Table 1, is a summary of the locations, system ratings, capacities, and levelized costs
for the reference designs.

<style type="text/css">
.tg  {border-collapse:collapse;border-color:#ccc;border-spacing:0;margin:0px auto;}
.tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 14px;word-break:normal;}
.tg th{background-color:#BDBDBD;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 14px;word-break:normal;}
.tg .tg-zyik{border-color:inherit;font-weight:bold;position:-webkit-sticky;position:sticky;text-align:center;top:-1px;
  vertical-align:top;will-change:transform}
.tg .tg-zwlc{background-color:#f9f9f9;border-color:inherit;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-7btt{border-color:inherit;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-5fiw{background-color:#f9f9f9;border-color:inherit;text-align:right;vertical-align:top}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-btxf{background-color:#f9f9f9;border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-dvpl{border-color:inherit;text-align:right;vertical-align:top}
.tg .tg-abip{background-color:#f9f9f9;border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-buh4{background-color:#f9f9f9;text-align:left;vertical-align:top}
.tg .tg-0vih{background-color:#f9f9f9;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-lqy6{text-align:right;vertical-align:top}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-p5oz{background-color:#f9f9f9;text-align:right;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
.tg .tg-dzk6{background-color:#f9f9f9;text-align:center;vertical-align:top}
.tg .tg-bbhh{font-size:18px}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-9ynr{background-color:#F9F9F9;border-color:inherit;color:#333;text-align:right;vertical-align:top}
</style>
<table class="tg"><thead>
<caption class="tg-bbhh">Table 1 - Overview of Reference Design Cases</caption>
  <tr>
    <th class="tg-7btt">ID</th>
    <th class="tg-7btt">01</th>
    <th class="tg-7btt">02</th>
    <th class="tg-7btt">03</th>
    <th class="tg-7btt">04</th>
    <th class="tg-7btt">05</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-btxf">State</td>
    <td class="tg-5fiw">Minnesota</td>
    <td class="tg-5fiw">Texas</td>
    <td class="tg-5fiw">Texas</td>
    <td class="tg-5fiw">New Jersey</td>
    <td class="tg-5fiw">California</td>
  </tr>
  <tr>
    <td class="tg-0pky">Area</td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl">Gulf Coast</td>
    <td class="tg-dvpl">New York Bight</td>
    <td class="tg-dvpl"></td>
  </tr>
  <tr>
    <td class="tg-btxf">Product</td>
    <td class="tg-5fiw">Steel</td>
    <td class="tg-5fiw">Ammonia</td>
    <td class="tg-5fiw">Hydrogen</td>
    <td class="tg-5fiw">Hydrogen</td>
    <td class="tg-5fiw">Hydrogen</td>
  </tr>
  <tr>
    <td class="tg-0pky">On/Offshore</td>
    <td class="tg-dvpl">Onshore</td>
    <td class="tg-dvpl">Onshore</td>
    <td class="tg-dvpl">Offshore</td>
    <td class="tg-dvpl">Offshore</td>
    <td class="tg-dvpl">Offshore</td>
  </tr>
  <tr>
    <td class="tg-buh4">Hydrogen storage type</td>
    <td class="tg-p5oz">Rock cavern</td>
    <td class="tg-p5oz">Salt cavern</td>
    <td class="tg-p5oz">Salt cavern</td>
    <td class="tg-p5oz">Rock cavern</td>
    <td class="tg-p5oz">Rock cavern</td>
  </tr>
  <tr>
    <td class="tg-btxf">PEM electrolyzer rating (MW)</td>
    <td class="tg-5fiw">720.0</td>
    <td class="tg-5fiw">640.0</td>
    <td class="tg-5fiw">1125.0</td>
    <td class="tg-5fiw">1125.0</td>
    <td class="tg-5fiw">1125.0</td>
  </tr>
  <tr>
    <td class="tg-0pky">Wind farm rating (MW)</td>
    <td class="tg-dvpl">930.0</td>
    <td class="tg-dvpl">888.0</td>
    <td class="tg-dvpl">968.0</td>
    <td class="tg-dvpl">990.0</td>
    <td class="tg-dvpl">990.0</td>
  </tr>
  <tr>
    <td class="tg-btxf">Solar PV rating (MW)</td>
    <td class="tg-5fiw">800.0</td>
    <td class="tg-5fiw">400.0</td>
    <td class="tg-5fiw">1500.0</td>
    <td class="tg-5fiw">1500.0</td>
    <td class="tg-5fiw">1500.0</td>
  </tr>
  <tr>
    <td class="tg-0pky">Total generation rating (MW)</td>
    <td class="tg-dvpl">1730.0</td>
    <td class="tg-dvpl">1288.0</td>
    <td class="tg-dvpl">2486.0</td>
    <td class="tg-dvpl">2490.0</td>
    <td class="tg-dvpl">2490.0</td>
  </tr>
  <tr>
    <td class="tg-btxf">Battery power rating (MW)</td>
    <td class="tg-5fiw">108.0</td>
    <td class="tg-5fiw">0.1</td>
    <td class="tg-5fiw">375.7</td>
    <td class="tg-5fiw">375.7</td>
    <td class="tg-5fiw">375.7</td>
  </tr>
  <tr>
    <td class="tg-0pky">Battery energy rating (MWh)</td>
    <td class="tg-dvpl">108.0</td>
    <td class="tg-dvpl">0.1</td>
    <td class="tg-dvpl">1500.0</td>
    <td class="tg-dvpl">1500.0</td>
    <td class="tg-dvpl">1500.0</td>
  </tr>
  <tr>
    <td class="tg-btxf">Hydrogen generation rating (kt)</td>
    <td class="tg-5fiw">115.0</td>
    <td class="tg-5fiw">103.0</td>
    <td class="tg-5fiw">181.0</td>
    <td class="tg-5fiw">181.0</td>
    <td class="tg-5fiw">181.0</td>
  </tr>
  <tr>
    <td class="tg-0pky">Hydrogen storage capacity (kt)</td>
    <td class="tg-dvpl">1.7</td>
    <td class="tg-dvpl">3.4</td>
    <td class="tg-dvpl">5.3</td>
    <td class="tg-dvpl">6.6</td>
    <td class="tg-dvpl">8.2</td>
  </tr>
  <tr>
    <td class="tg-0lax">Hydrogen storage max fill rate (t/h)</td>
    <td class="tg-lqy6">13.2</td>
    <td class="tg-lqy6">11.7</td>
    <td class="tg-lqy6">20.7</td>
    <td class="tg-lqy6">20.7</td>
    <td class="tg-lqy6">20.7</td>
  </tr>
  <tr>
    <td class="tg-btxf">Steel capacity (Mt/yr)</td>
    <td class="tg-5fiw">1.0</td>
    <td class="tg-5fiw"></td>
    <td class="tg-5fiw"></td>
    <td class="tg-5fiw"></td>
    <td class="tg-5fiw"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Ammonia capacity (kt/yr)</td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl">329.0</td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
  </tr>
  <tr>
    <td class="tg-btxf">LCOH (USD/kg-H2)</td>
    <td class="tg-5fiw">6.3</td>
    <td class="tg-5fiw">4.8</td>
    <td class="tg-5fiw">9.6</td>
    <td class="tg-5fiw">10.3</td>
    <td class="tg-5fiw">14.2</td>
  </tr>
  <tr>
    <td class="tg-0pky">LCOS (USD/t steel)</td>
    <td class="tg-dvpl">1191.0</td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
  </tr>
  <tr>
    <td class="tg-btxf">LCOA (USD/kg-NH3)</td>
    <td class="tg-5fiw"></td>
    <td class="tg-5fiw">1.1</td>
    <td class="tg-5fiw"></td>
    <td class="tg-5fiw"></td>
    <td class="tg-5fiw"></td>
  </tr>
</tbody></table>

&nbsp;

# PEM Configuration

Table 2 summarizes the physical, cost, and financial modeling parameters for the PEM electrolyzer 
that were used across all reference design scenarios.

<table class="tg"><thead>
<caption class="tg-bbhh">Table 2 - Summary of PEM Parameters and Assumptions</caption>
  <tr>
    <th class="tg-amwm">PEM Physical Parameters</th>
    <th class="tg-amwm">Value</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-buh4">Stack life (hours)</td>
    <td class="tg-p5oz">80,000</td>
  </tr>
  <tr>
    <td class="tg-0lax">Turndown ratio</td>
    <td class="tg-lqy6">10%</td>
  </tr>
  <tr>
    <td class="tg-buh4">End-of-life efficiency loss</td>
    <td class="tg-p5oz">10%</td>
  </tr>
  <tr>
    <td class="tg-0lax">Steady degradation rate (mV/hour)</td>
    <td class="tg-lqy6">0.0025</td>
  </tr>
  <tr>
    <td class="tg-buh4">On/off cycle degradation (mV/off-cycle)</td>
    <td class="tg-p5oz">0.148</td>
  </tr>
  <tr>
    <td class="tg-0lax">Rated beginning-of-life efficiency (kWh/kg)</td>
    <td class="tg-lqy6">51.0</td>
  </tr>
  <tr>
    <td class="tg-0lax">Number of cells</td>
    <td class="tg-lqy6">135</td>
  </tr>
  <tr>
    <td class="tg-0lax">Cell active area (cm^2)</td>
    <td class="tg-lqy6">1949</td>
  </tr>
  <tr>
    <td class="tg-0lax">Stack rating (MW)</td>
    <td class="tg-lqy6">1.0</td>
  </tr>
  <tr>
    <td class="tg-0lax">Membrane thickness (cm)</td>
    <td class="tg-lqy6">0.0077</td>
  </tr>
  <tr>
    <th class="tg-amwm">PEM Cost Parameters</th>
    <th class="tg-amwm">Value</th>
  </tr>
  <tr>
    <td class="tg-0lax">Installed CapEx cost ($/kW)</td>
    <td class="tg-lqy6">1295.00</td>
  </tr>
  <tr>
    <td class="tg-buh4">Fixed O&amp;M ($/kW-year)</td>
    <td class="tg-p5oz">12.80</td>
  </tr>
  <tr>
    <td class="tg-0lax">Variable O&amp;M ($/MWh)</td>
    <td class="tg-lqy6">1.30</td>
  </tr>
  <tr>
    <td class="tg-buh4">Stack replacement cost</td>
    <td class="tg-dzk6">15% of installed capital cost</td>
  </tr>
  <tr>
    <th class="tg-amwm">PEM financial parameters</th>
    <th class="tg-amwm">Value</th>
  </tr>
  <tr>
    <td class="tg-buh4">Combined state and federal tax rate</td>
    <td class="tg-p5oz">25.74%</td>
  </tr>
  <tr>
    <td class="tg-0lax">Capital gains tax rate</td>
    <td class="tg-lqy6">15%</td>
  </tr>
  <tr>
    <td class="tg-buh4">Depreciation method</td>
    <td class="tg-p5oz">7-year MACRS</td>
  </tr>
  <tr>
    <td class="tg-0lax">General inflation rate</td>
    <td class="tg-lqy6">0%</td>
  </tr>
  <tr>
    <td class="tg-buh4">Plant life</td>
    <td class="tg-p5oz">30 years</td>
  </tr>
  <tr>
    <td class="tg-0lax">U.S. dollar year</td>
    <td class="tg-lqy6">2022</td>
  </tr>
</tbody></table>

&nbsp;

# Wind Configuration

Table 3 summarizes the physical, cost, and financial modeling parameters for the wind plant that
were used across all reference design scenarios.

<table class="tg"><thead>
<caption class="tg-bbhh">Table 3 - Summary of Wind Parameters and Assumptions</caption>
  <tr>
    <th class="tg-zyik">ID</th>
    <th class="tg-zyik">01</th>
    <th class="tg-zyik">02</th>
    <th class="tg-zyik">03</th>
    <th class="tg-zyik">04</th>
    <th class="tg-zyik">05</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-btxf">State</td>
    <td class="tg-5fiw">Minnesota</td>
    <td class="tg-5fiw">Texas</td>
    <td class="tg-5fiw">Texas</td>
    <td class="tg-5fiw">New Jersey</td>
    <td class="tg-5fiw">California</td>
  </tr>
  <tr>
    <td class="tg-0pky">Area</td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl">Gulf Coast</td>
    <td class="tg-dvpl">New York Bight</td>
    <td class="tg-dvpl"></td>
  </tr>
  <tr>
    <td class="tg-btxf">Product</td>
    <td class="tg-5fiw">Steel</td>
    <td class="tg-5fiw">Ammonia</td>
    <td class="tg-5fiw">Hydrogen</td>
    <td class="tg-5fiw">Hydrogen</td>
    <td class="tg-5fiw">Hydrogen</td>
  </tr>
  <tr>
    <td class="tg-0pky">On/Offshore</td>
    <td class="tg-dvpl">Onshore</td>
    <td class="tg-dvpl">Onshore</td>
    <td class="tg-dvpl">Offshore</td>
    <td class="tg-dvpl">Offshore</td>
    <td class="tg-dvpl">Offshore</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="6">Wind Physical Parameters</th>
  </tr>
  <tr>
    <td class="tg-0pky">Wind farm rating (MW)</td>
    <td class="tg-dvpl">930.0</td>
    <td class="tg-dvpl">888.0</td>
    <td class="tg-dvpl">968.0</td>
    <td class="tg-dvpl">990.0</td>
    <td class="tg-dvpl">990.0</td>
  </tr>
  <tr>
    <td class="tg-btxf">Wind turbine rating (MW)</td>
    <td class="tg-5fiw">6.0</td>
    <td class="tg-5fiw">6.0</td>
    <td class="tg-5fiw">17.0</td>
    <td class="tg-5fiw">15.0</td>
    <td class="tg-5fiw">15.0</td>
  </tr>
  <tr>
    <td class="tg-0pky">Number of wind turbines</td>
    <td class="tg-dvpl">155</td>
    <td class="tg-dvpl">148</td>
    <td class="tg-dvpl">58</td>
    <td class="tg-dvpl">66</td>
    <td class="tg-dvpl">66</td>
  </tr>
  <tr>
    <td class="tg-btxf">Average wind speed (m/s)</td>
    <td class="tg-5fiw">7.4</td>
    <td class="tg-5fiw">9.1</td>
    <td class="tg-5fiw">8.4</td>
    <td class="tg-5fiw">9.5</td>
    <td class="tg-5fiw">9.2</td>
  </tr>
  <tr>
    <td class="tg-0pky">Distance from shore (km)</td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl">44.7</td>
    <td class="tg-dvpl">71.1</td>
    <td class="tg-dvpl">40.9</td>
  </tr>
  <tr>
    <td class="tg-btxf">Foundation type</td>
    <td class="tg-5fiw"></td>
    <td class="tg-5fiw"></td>
    <td class="tg-5fiw">Fixed</td>
    <td class="tg-5fiw">Fixed</td>
    <td class="tg-5fiw">Floating</td>
  </tr>
  <tr>
    <td class="tg-0pky">Depth (m)</td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl">45.0</td>
    <td class="tg-dvpl">34.0</td>
    <td class="tg-dvpl">905.0</td>
  </tr>
  <tr>
    <td class="tg-btxf">Onshore latitude</td>
    <td class="tg-5fiw">47.5000</td>
    <td class="tg-5fiw">32.3171</td>
    <td class="tg-5fiw">27.6096</td>
    <td class="tg-5fiw">39.7755</td>
    <td class="tg-5fiw">40.8837</td>
  </tr>
  <tr>
    <td class="tg-0pky">Onshore longitude</td>
    <td class="tg-dvpl">-93.0000</td>
    <td class="tg-dvpl">-100.1800</td>
    <td class="tg-dvpl">-97.4023</td>
    <td class="tg-dvpl">-74.2302</td>
    <td class="tg-dvpl">-124.1335</td>
  </tr>
  <tr>
    <td class="tg-btxf">Offshore latitude</td>
    <td class="tg-5fiw"></td>
    <td class="tg-5fiw"></td>
    <td class="tg-5fiw">27.1808</td>
    <td class="tg-5fiw">39.5397</td>
    <td class="tg-5fiw">40.8538</td>
  </tr>
  <tr>
    <td class="tg-0pky">Offshore longitude</td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl">-96.9330</td>
    <td class="tg-dvpl">-73.3299</td>
    <td class="tg-dvpl">-124.6752</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="6">Wind Cost Parameters</th>
  </tr>
  <tr>
    <td class="tg-0pky">Wind CapEx (USD/kW)</td>
    <td class="tg-dvpl">1380.00</td>
    <td class="tg-dvpl">1380.00</td>
    <td class="tg-dvpl">2470.36*</td>
    <td class="tg-dvpl">2470.89*</td>
    <td class="tg-dvpl">4247.0*</td>
  </tr>
  <tr>
    <td class="tg-btxf">Wind fixed O&amp;M (USD/kW)</td>
    <td class="tg-5fiw">29.00</td>
    <td class="tg-5fiw">29.00</td>
    <td class="tg-5fiw">134.98*</td>
    <td class="tg-5fiw">145.05*</td>
    <td class="tg-5fiw">118.96*</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="6">Wind Financial Parameters</th>
  </tr>
  <tr>
    <td class="tg-btxf">Real ROE wind</td>
    <td class="tg-abip" colspan="2">6.30%</td>
    <td class="tg-abip" colspan="3">7.00%</td>
  </tr>
  <tr>
    <td class="tg-0pky">Debt percentage wind</td>
    <td class="tg-c3ow" colspan="2">72.40%</td>
    <td class="tg-c3ow" colspan="3">73.40%</td>
  </tr>
  <tr>
    <td class="tg-btxf">Debt interest rate wind</td>
    <td class="tg-abip" colspan="5">4.40%</td>
  </tr>
  <tr>
    <td class="tg-buh4">Debt type</td>
    <td class="tg-dzk6" colspan="5">Revolving</td>
  </tr>
  <tr>
    <td class="tg-0lax">Depreciation method</td>
    <td class="tg-baqh" colspan="5">MACRS</td>
  </tr>
  <tr>
    <td class="tg-buh4">Depreciation period (years)</td>
    <td class="tg-dzk6" colspan="5">7</td>
  </tr>
</tbody></table>

&nbsp;

# Solar PV Configuration

Table 4 summarizes the physical, cost, and financial modeling parameters for the solar PV plant
that were used across all reference design scenarios.

<table class="tg"><thead>
<caption class="tg-bbhh">Table 4 - Summary of Solar PV Parameters and Assumptions</caption>
  <tr>
    <th class="tg-zyik">ID</th>
    <th class="tg-zyik">01</th>
    <th class="tg-zyik">02</th>
    <th class="tg-zyik">03</th>
    <th class="tg-zyik">04</th>
    <th class="tg-zyik">05</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-btxf">State</td>
    <td class="tg-5fiw">Minnesota</td>
    <td class="tg-5fiw">Texas</td>
    <td class="tg-5fiw">Texas</td>
    <td class="tg-5fiw">New Jersey</td>
    <td class="tg-5fiw">California</td>
  </tr>
  <tr>
    <td class="tg-0pky">Area</td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl">Gulf Coast</td>
    <td class="tg-dvpl">New York Bight</td>
    <td class="tg-dvpl"></td>
  </tr>
  <tr>
    <td class="tg-btxf">Product</td>
    <td class="tg-5fiw">Steel</td>
    <td class="tg-5fiw">Ammonia</td>
    <td class="tg-5fiw">Hydrogen</td>
    <td class="tg-5fiw">Hydrogen</td>
    <td class="tg-5fiw">Hydrogen</td>
  </tr>
  <tr>
    <td class="tg-0pky">On/Offshore</td>
    <td class="tg-dvpl">Onshore</td>
    <td class="tg-dvpl">Onshore</td>
    <td class="tg-dvpl">Offshore</td>
    <td class="tg-dvpl">Offshore</td>
    <td class="tg-dvpl">Offshore</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="6">PV Physical Parameters</th>
  </tr>
  <tr>
    <td class="tg-0pky">Solar PV rating (MW)</td>
    <td class="tg-dvpl">800.0</td>
    <td class="tg-dvpl">400.0</td>
    <td class="tg-dvpl">1500.0</td>
    <td class="tg-dvpl">1500.0</td>
    <td class="tg-dvpl">1500.0</td>
  </tr>
  <tr>
    <td class="tg-btxf">Onshore latitude</td>
    <td class="tg-9ynr"><span style="color:#333;background-color:#F9F9F9">47.5000</span></td>
    <td class="tg-9ynr">32.3171</td>
    <td class="tg-5fiw">27.6096</td>
    <td class="tg-5fiw">39.7755</td>
    <td class="tg-5fiw">40.8837</td>
  </tr>
  <tr>
    <td class="tg-0pky">Onshore longitude</td>
    <td class="tg-dvpl">-93.0000</td>
    <td class="tg-dvpl">-100.1800</td>
    <td class="tg-dvpl">-97.4023</td>
    <td class="tg-dvpl">-74.2302</td>
    <td class="tg-dvpl">-124.1335</td>
  </tr>
  <tr>
    <td class="tg-0pky">Direct horizontal irradiance (kWh/m^2)</td>
    <td class="tg-dvpl">59.5</td>
    <td class="tg-dvpl">59.2</td>
    <td class="tg-dvpl">76.3</td>
    <td class="tg-dvpl">67.7</td>
    <td class="tg-dvpl">60..2</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="6">PV Cost Parameters</th>
  </tr>
  <tr>
    <td class="tg-btxf">Solar PV CapEx (USD/kW)</td>
    <td class="tg-abip" colspan="5">1323.00</td>
  </tr>
  <tr>
    <td class="tg-0pky">Solar PV fixed O&amp;M (USD/kW)</td>
    <td class="tg-c3ow" colspan="5">18.0</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="6">PV Financial Parameters</th>
  </tr>
  <tr>
    <td class="tg-0pky">Real ROE solar PV</td>
    <td class="tg-c3ow" colspan="5">5.90%</td>
  </tr>
  <tr>
    <td class="tg-btxf">Debt percentage solar PV</td>
    <td class="tg-abip" colspan="5">75.30%</td>
  </tr>
  <tr>
    <td class="tg-0pky">Debt interest rate solar PV</td>
    <td class="tg-c3ow" colspan="5">4.40%</td>
  </tr>
  <tr>
    <td class="tg-buh4">Debt type</td>
    <td class="tg-dzk6" colspan="5">Revolving</td>
  </tr>
  <tr>
    <td class="tg-0lax">Depreciation method</td>
    <td class="tg-baqh" colspan="5">MACRS</td>
  </tr>
  <tr>
    <td class="tg-buh4">Depreciation period (years)</td>
    <td class="tg-dzk6" colspan="5">7</td>
  </tr>
</tbody></table>

&nbsp;

# Battery Storage Configuration

Table 5 summarizes the physical, cost, and financial modeling parameters for the battery storage
that were used across all reference design scenarios.

<table class="tg"><thead>
<caption class="tg-bbhh">Table 5 - Summary of Battery Storage Parameters and Assumptions</caption>
  <tr>
    <th class="tg-zyik">ID</th>
    <th class="tg-zyik">01</th>
    <th class="tg-zyik">02</th>
    <th class="tg-zyik">03</th>
    <th class="tg-zyik">04</th>
    <th class="tg-zyik">05</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-btxf">State</td>
    <td class="tg-5fiw">Minnesota</td>
    <td class="tg-5fiw">Texas</td>
    <td class="tg-5fiw">Texas</td>
    <td class="tg-5fiw">New Jersey</td>
    <td class="tg-5fiw">California</td>
  </tr>
  <tr>
    <td class="tg-0pky">Area</td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl"></td>
    <td class="tg-dvpl">Gulf Coast</td>
    <td class="tg-dvpl">New York Bight</td>
    <td class="tg-dvpl"></td>
  </tr>
  <tr>
    <td class="tg-btxf">Product</td>
    <td class="tg-5fiw">Steel</td>
    <td class="tg-5fiw">Ammonia</td>
    <td class="tg-5fiw">Hydrogen</td>
    <td class="tg-5fiw">Hydrogen</td>
    <td class="tg-5fiw">Hydrogen</td>
  </tr>
  <tr>
    <td class="tg-0pky">On/Offshore</td>
    <td class="tg-dvpl">Onshore</td>
    <td class="tg-dvpl">Onshore</td>
    <td class="tg-dvpl">Offshore</td>
    <td class="tg-dvpl">Offshore</td>
    <td class="tg-dvpl">Offshore</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="6">Battery Storage Physical Parameters</th>
  </tr>
  <tr>
    <td class="tg-0pky">Battery power rating (MW)</td>
    <td class="tg-dvpl">108.0</td>
    <td class="tg-dvpl">0.1</td>
    <td class="tg-dvpl">375.7</td>
    <td class="tg-dvpl">375.7</td>
    <td class="tg-dvpl">375.7</td>
  </tr>
  <tr>
    <td class="tg-btxf">Battery energy rating (MWh)</td>
    <td class="tg-9ynr">108.0</td>
    <td class="tg-9ynr">0.1</td>
    <td class="tg-5fiw">1500.0</td>
    <td class="tg-5fiw">1500.0</td>
    <td class="tg-5fiw">1500.0</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="6">Battery Storage Cost Parameters</th>
  </tr>
  <tr>
    <td class="tg-btxf">Battery CapEx (USD/kW)</td>
    <td class="tg-abip" colspan="5">311.00</td>
  </tr>
  <tr>
    <td class="tg-0pky">Battery fixed O&amp;M (USD/kW)</td>
    <td class="tg-c3ow" colspan="2">15.53</td>
    <td class="tg-c3ow" colspan="3">38.77</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="6">Battery Storage Financial Parameters</th>
  </tr>
  <tr>
    <td class="tg-0pky">Real ROE battery</td>
    <td class="tg-c3ow" colspan="5">6.60%</td>
  </tr>
  <tr>
    <td class="tg-btxf">Debt percentage battery</td>
    <td class="tg-abip" colspan="5">75.40%</td>
  </tr>
  <tr>
    <td class="tg-0pky">Debt interest rate battery</td>
    <td class="tg-c3ow" colspan="5">4.40%</td>
  </tr>
  <tr>
    <td class="tg-btxf">Debt type</td>
    <td class="tg-abip" colspan="5">Revolving</td>
  </tr>
  <tr>
    <td class="tg-0pky">Depreciation method</td>
    <td class="tg-c3ow" colspan="5">MACRS</td>
  </tr>
  <tr>
    <td class="tg-btxf">Depreciation period (years)</td>
    <td class="tg-abip" colspan="5">7</td>
  </tr>
</tbody></table>

&nbsp;

# Steel Configuration

Table 6 summarizes the physical, cost, and financial modeling parameters for the steel plant that
were used across all reference design scenarios. Currently there is just one plant that includes
steel production, ID 01 in Minnesota.

<table class="tg"><thead>
<caption class="tg-bbhh">Table 6 - Summary of Steel Parameters and Assumptions</caption>
  <tr>
    <th class="tg-zyik">ID</th>
    <th class="tg-zyik">01</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-btxf">State</td>
    <td class="tg-5fiw">Minnesota</td>
  </tr>
  <tr>
    <td class="tg-0pky">Product</td>
    <td class="tg-dvpl">Steel</td>
  </tr>
  <tr>
    <td class="tg-btxf">On/Offshore</td>
    <td class="tg-5fiw">Onshore</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="2">Steel Physical Parameters</th>
  </tr>
  <tr>
    <td class="tg-btxf">Steel capacity (Mt/yr)</td>
    <td class="tg-5fiw">1.0</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="2">Steel Cost Parameters</th>
  </tr>
  <tr>
    <td class="tg-btxf">Steel plant CapEx (USD/kW)</td>
    <td class="tg-5fiw">592.50*</td>
  </tr>
  <tr>
    <td class="tg-0pky">Steel plant fixed O&amp;M (USD/kW)</td>
    <td class="tg-dvpl">103.41*</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="2">Steel Financial Parameters</th>
  </tr>
  <tr>
    <td class="tg-0pky">Real ROE steel</td>
    <td class="tg-dvpl">10.89%</td>
  </tr>
  <tr>
    <td class="tg-btxf">Debt percentage steel</td>
    <td class="tg-5fiw">38.45%</td>
  </tr>
  <tr>
    <td class="tg-0pky">Debt interest rate steel</td>
    <td class="tg-dvpl">5.00%</td>
  </tr>
  <tr>
    <td class="tg-btxf">Debt type</td>
    <td class="tg-5fiw">Revolving</td>
  </tr>
  <tr>
    <td class="tg-0pky">Depreciation method</td>
    <td class="tg-dvpl">MACRS</td>
  </tr>
  <tr>
    <td class="tg-btxf">Depreciation period (years)</td>
    <td class="tg-5fiw">7</td>
  </tr>
</tbody></table>

&nbsp;

# Ammonia Configuration

Table 7 summarizes the physical, cost, and financial modeling parameters for the ammonia plant that
were used across all reference design scenarios. Currently there is just one plant that includes
ammonia production, ID 02 in Texas.

<table class="tg"><thead>
<caption class="tg-bbhh">Table 7 - Summary of Ammonia Parameters and Assumptions</caption>
  <tr>
    <th class="tg-zyik">ID</th>
    <th class="tg-zyik">02</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-btxf">State</td>
    <td class="tg-5fiw">Texas</td>
  </tr>
  <tr>
    <td class="tg-0pky">Product</td>
    <td class="tg-dvpl">Ammonia</td>
  </tr>
  <tr>
    <td class="tg-btxf">On/Offshore</td>
    <td class="tg-5fiw">Onshore</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="2">Ammonia Physical Parameters</th>
  </tr>
  <tr>
    <td class="tg-btxf">Ammonia capacity (Mt/yr)</td>
    <td class="tg-5fiw">329.0</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="2">Ammonia Cost Parameters</th>
  </tr>
  <tr>
    <td class="tg-btxf">Ammonia plant CapEx (USD/kW)</td>
    <td class="tg-5fiw">289.99*</td>
  </tr>
  <tr>
    <td class="tg-0pky">Ammonia plant fixed O&amp;M (USD/kW)</td>
    <td class="tg-dvpl">32.67*</td>
  </tr>
  <tr>
    <th class="tg-amwm" colspan="2">Ammonia Financial Parameters</th>
  </tr>
  <tr>
    <td class="tg-0pky">Real ROE ammonia</td>
    <td class="tg-dvpl">10.89%</td>
  </tr>
  <tr>
    <td class="tg-btxf">Debt percentage ammonia</td>
    <td class="tg-5fiw">38.45%</td>
  </tr>
  <tr>
    <td class="tg-0pky">Debt interest rate ammonia</td>
    <td class="tg-dvpl">5.00%</td>
  </tr>
  <tr>
    <td class="tg-btxf">Debt type</td>
    <td class="tg-5fiw">Revolving</td>
  </tr>
  <tr>
    <td class="tg-0pky">Depreciation method</td>
    <td class="tg-dvpl">MACRS</td>
  </tr>
  <tr>
    <td class="tg-btxf">Depreciation period (years)</td>
    <td class="tg-5fiw">7</td>
  </tr>
</tbody></table>

&nbsp;
