---
title: Kent and Medway Sustainability - NHS Emissions Cookbook
author:  Dr Dan Wright et al.
keywords: Greener NHS, Emissions, Calculation
---

# Kent & Medway Sustainability: NHS Emissions Cookbook 

**Authors**:
  Dan Wright<sup>1</sup>, James Bate <sup>2</sup>, Sirina Blankson<sup>3</sup>, Emma Clarke<sup>4</sup>, Vicky Cooper<sup>3</sup>, Stu Meades<sup>5</sup>, John Mills<sup>6</sup>, Finn Nightingale<sup>1</sup> & Alison Watson<sup>7</sup>.

1. Kent Community Health NHS Foundation Trust
2. Greener NHS
3. Kent and Medway NHS and Social Care Mental Health Trust 
4. Kent County Council
5. Greener Edge Ltd.
6. 2gether Support Solutions
7. Kent and Medway Integrated Care Board

[Intro]

Dependencies

* [Department for Business, Energy and Industrial Strategy (BEIS) conversion factors for company reporting](https://www.gov.uk/government/collections/government-conversion-factors-for-company-reporting) (Accessed: 22 July 2022)

Acknowledgements

Approach inspired by the Domestic Operation Rating (Lomas et al., 2020)

## Fossil fuels

### Definition
Emissions associated with combustion of any gaseous, liquid, and solid fossil fuels and owned sites and tenanted sites where billing responsibility to the energy supplier is held.

### Data map

| Description of data available  | Reduced calculation  | Standard calculation | Optimal Calculation |
| ------------------------------ |:---:| :---:| :---:|
| Modelled energy consumption | X |  |  |
| Monitored annual consumption, ≥11% estimated (kWh) |  | X |  |
| Monitored annual consumption, ≤10% estimated (kWh) |  |  | X |

### Calculations

#### Natural gas

**Reduced calculation**

$$ 
\sum \left( \left( \text{ModCon} \times \text{A} \right) \times \text{Fac} \right) \div 1,000 = \text{tCO}_2\text{e}^{\text{RC}}
$$

Where:
* *ModCon* = Value of modelled annual energy use (kWh/m<sup>2</sup>) from the relevant Display Energy Certificate.
* *A* = Value of total useful floor area (m<sup>2</sup>) from the relevant Display Energy Certificate.
* *Fac* = Carbon factor assigned to the fuel by the relevant BEIS carbon factor database publication.  

**Standard calculation**

$$ 
\sum \left( \text{EstMonCon} \times \text{Fac} \right) \div 1,000 = \text{tCO}_2\text{e}^{\text{SC}}
$$

Where:
* EstMonCon = Value of monitored annual energy use (kWh) where ≥11% of data are estimated.
* Fac = Carbon factor assigned to the fuel by the relevant BEIS carbon factor database publication.  

**Optimal calculation**

$$ 
\sum \left( \text{MonCon} \times \text{Fac} \right) \div 1,000 = \text{tCO}_2\text{e}^{\text{OC}}
$$

Where:
* MonCon = Value of monitored annual energy use (kWh) where ≤10% of data are estimated.
* Fac = Carbon factor assigned to the fuel by the relevant DEFRA or BEIS carbon factor database publication.  