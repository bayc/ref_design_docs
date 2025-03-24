# Reference Design Overview

Below is a high-level overview of the current reference hybrid system designs available. More
details about each design can be found in the [User Guide](../user_guide/user_guide.md), or in the
reference design report, found [here](../user_guide/Reference_Design_Documentation.pdf).

<style type="text/css">
.tg  {border-collapse:collapse;border-color:#ccc;border-spacing:0;margin:0px auto;}
.tg td{background-color:#fff;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{background-color:#f0f0f0;border-color:#ccc;border-style:solid;border-width:1px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-1wig{font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-buh4{background-color:#f9f9f9;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-1wig">ID</th>
    <th class="tg-1wig">Region (detail)</th>
    <th class="tg-1wig">Product</th>
    <th class="tg-1wig">Grid connection</th>
    <th class="tg-1wig">Land-based technology</th>
    <th class="tg-1wig">Offshore technology</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-buh4">01</td>
    <td class="tg-buh4">Minnesota</td>
    <td class="tg-buh4">Steel</td>
    <td class="tg-buh4">Yes (ore and steel tech only)</td>
    <td class="tg-buh4">Wind, solar (pv), battery storage, electrolysis, hydrogen storage (rock cavern), iron ore refining, steel production</td>
    <td class="tg-buh4">N/A</td>
  </tr>
  <tr>
    <td class="tg-0lax">02</td>
    <td class="tg-0lax">Texas</td>
    <td class="tg-0lax">Ammonia</td>
    <td class="tg-0lax">Yes (ammonia tech only)</td>
    <td class="tg-0lax">Wind, solar (pv), battery storage, electrolysis, hydrogen storage (salt cavern), ammonia production</td>
    <td class="tg-0lax">N/A</td>
  </tr>
  <tr>
    <td class="tg-buh4">03</td>
    <td class="tg-buh4">Texas (gulf coast)</td>
    <td class="tg-buh4">Hydrogen</td>
    <td class="tg-buh4">No</td>
    <td class="tg-buh4">Solar (pv), battery storage, electrolysis, hydrogen storage (salt cavern)</td>
    <td class="tg-buh4">Wind (fixed foundation)</td>
  </tr>
  <tr>
    <td class="tg-0lax">04</td>
    <td class="tg-0lax">New York Bight</td>
    <td class="tg-0lax">Hydrogen</td>
    <td class="tg-0lax">No</td>
    <td class="tg-0lax">Solar (pv), battery storage, electrolysis, hydrogen storage (rock cavern)</td>
    <td class="tg-0lax">Wind (fixed foundation)</td>
  </tr>
  <tr>
    <td class="tg-buh4">05</td>
    <td class="tg-buh4">California</td>
    <td class="tg-buh4">Hydrogen</td>
    <td class="tg-buh4">No</td>
    <td class="tg-buh4">Solar (pv), battery storage, electrolysis, hydrogen storage (rock cavern)</td>
    <td class="tg-buh4">Wind (floating foundation)</td>
  </tr>
</tbody></table>

&nbsp;

# Organization

You will find files for the reference designs organized as follows:
- Run scripts for using the reference design with a specific software package: `reference-systems/<##-region-product>/<software-name>/`
- Input files for using the reference design with a specific software package: `reference-systems/<##-region-product>/<software-name>/input-files/`
- Supporting documentation, such as pdf files: `reference-systems/<##-region-product>/doc/` (still being implemented)
- Tests: `tests/test-<##-region-product>/test-<software-name>.py` (still being implemented)

&nbsp;

# Key Tool Dependencies

The reference designs leverage many tools developed at NREL and other labs. These tools are used by
the [H2Integrate](https://github.com/NREL/GreenHEART) code, which was used to generate the initial 
reference designs and their results. For more information on how these tools are combined and used,
the reader is referred to the [H2Integrate documentation](https://nrel.github.io/GreenHEART/intro.html).
A list of the other tools used is given below.

## General
| Application | Name | Developer | Link | 
|-|-|-|-|
| Costs | ATB | NREL | [https://atb.nrel.gov](https://atb.nrel.gov) |
| Hybrid electrical plant | HOPP | NREL | [https://github.com/NREL/HOPP](https://github.com/NREL/HOPP) |
| Finances | ProFAST | NREL | [https://github.com/NREL/ProFAST](https://github.com/NREL/ProFAST) |

## Wind
| Application | Name | Developer | Link | 
|-|-|-|-|
| Wake modeling| FLORIS | NREL | [https://github.com/NREL/floris](https://github.com/NREL/floris) |
| BOS (offshore) | ORBIT | NREL | [https://github.com/WISDEM/ORBIT](https://github.com/WISDEM/ORBIT) |
| Moorings (floating) | MoorPy | NREL | [https://github.com/NREL/MoorPy](https://github.com/NREL/MoorPy) |

## Solar PV
| Application | Name | Developer | Link | 
|-|-|-|-|
| Physics | SAM | NREL | [https://sam.nrel.gov](https://sam.nrel.gov) |

## Battery
| Application | Name | Developer | Link | 
|-|-|-|-|
| Physics | SAM | NREL | [https://sam.nrel.gov](https://sam.nrel.gov) |

<!-- ### Dispatch -->

## PEM Electrolysis
| Application | Name | Developer | Link | 
|-|-|-|-|
| Parameters | HFTO 2022 PEM Technical Targets | NREL | [https://www.energy.gov/eere/fuelcells/technical-targets-proton-exchange-membrane-electrolysis](https://www.energy.gov/eere/fuelcells/technical-targets-proton-exchange-membrane-electrolysis) |

## Hydrogen Storage
| Application | Name | Developer | Link | 
|-|-|-|-|
| Operational costs | HDSAM | Argonne | [https://hdsam.es.anl.gov](https://hdsam.es.anl.gov) |

## Steel
| Application | Name | Developer | Link |
|-|-|-|-|
| Model | Steel process | LBNL | [https://pubs.rsc.org/en/content/articlelanding/2023/ee/d3ee01077e](https://pubs.rsc.org/en/content/articlelanding/2023/ee/d3ee01077e) |

<!-- ### Ammonia -->
