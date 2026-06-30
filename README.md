# East Africa Poverty Scenarios under SSP3 and SSP4
This project dives into the analysis of population count of those living under $1.90 a day in East Africa - Kenya, Uganda, Tanzania, Rwanda and Burundi.
The data runs from 2010 to 2100

...
# The Table of Cotents
* [About the Project](#about-the-project)
* [Objectives](#Objectives-of-the-study)
* [Data & Tech Stack](#data-and-tech-stack)
* [Results](#Key-findings)
* [Conclusion and Recommendation](#conclusion-and-recommendation)

...

## About the Project
The project utilizes data from the World Bank Climate Knowledge Portal (CCKP). (https://climateknowledgeportal.worldbank.org/download-data)
This project uses two Shared Socioeconomic Pathways (SSPs) to model 
poverty projections in East Africa from 2010 to 2100:

- **SSP3 - Regional Rivalry**: A fragmented world with slow economic 
  growth, high population growth in developing regions, and poor 
  international cooperation. Represents a high-poverty risk scenario.

- **SSP4 - Inequality**: A divided world where elites and wealthy 
  nations advance while poorer regions are left behind, leading to 
  extreme inequality both within and between countries.
Both scenarios were selected to highlight worst-case poverty and 
inequality risks for the region, supporting analysis of progress 
toward SDG 1 (No Poverty).

...
## Objectives

- Clean and structure World Bank CCKP poverty data (SSP3 and SSP4) 
  for East African countries
- Visualize poverty trends (population living under $1.90/day) 
  from 2010 to 2100 for each country
- Compare SSP3 and SSP4 scenarios to understand how different 
  socioeconomic pathways affect poverty outcomes in the region
- Assess progress toward SDG 1 (No Poverty) by analyzing projected 
  poverty levels at the 2030 target year
- Identify the most and least vulnerable countries in East Africa 
  based on projected poverty trends

...
## Data and Tech Stack
* **Dataset: [https://climateknowledgeportal.worldbank.org/download-data]
* **Language:**Python 3
* ** Libraries""*`pandas` (Data manipulation and cleaning)
    *`numpy` (numerical computing)
    *`matplotlib & Seaborn` (Data visualization)

...

## Key Findings

### SSP3 - Regional Rivalry
Under the SSP3 scenario, East Africa faces a high-risk poverty outlook 
driven by slow economic growth, poor regional cooperation, and rapid 
population growth. Countries like Uganda show a worrying increase in 
the population living below $1.90/day between 2010 and 2030, moving 
in the opposite direction of SDG 1 targets.

**Link to Climate Change:**
SSP3 represents a world where climate change goes largely unaddressed 
due to fragmented international cooperation. In East Africa, this 
translates to more frequent droughts, floods, and crop failures that 
disproportionately affect rural farmers — pushing more people below 
the poverty line and making it harder for countries to sustain 
economic growth and reduce inequality

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/319a5156-499e-4067-8f73-7abae330313b" />

### SSP4
### SSP4 - Inequality
Under the SSP4 scenario, East Africa faces a deeply unequal development 
outlook where wealthy nations and elites advance while poorer regions 
are left behind. The data shows significantly different poverty 
projections compared to SSP3, reflecting a world where economic growth 
is uneven and access to resources, education, and technology remains 
deeply divided between and within countries.

**Link to Climate Change:**
SSP4 represents a world where rich countries invest in clean energy 
and climate adaptation while developing regions like East Africa 
continue to rely on fossil fuels and face the worst impacts of climate 
change. This creates a climate inequality trap — countries that 
contribute least to global emissions suffer the most, with extreme 
weather events deepening poverty and widening the gap between the 
rich and the poor both globally and within East Africa itself.

<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/93ce35a2-4fde-4e7b-a599-b8a0e0320314" />

### SDG 1 Assessment by 2030

#### SSP3 - Regional Rivalry
By 2030, no East African country is on track to end extreme poverty 
under the SSP3 scenario. Key findings:

- **Tanzania** shows the most progress with a **27.5% reduction** 
  in poverty, dropping from 23 million to 16.7 million people 
  living under $1.90/day
- **Kenya** shows minimal progress with only a **0.4% reduction**, 
  remaining at approximately 19.4 million people
- **Uganda** is moving in the **wrong direction**, with poverty 
  increasing by **11.9%** from 19.2 million to 21.5 million people 
  by 2030 — the most concerning trend in the region
- **Burundi** also shows a slight **increase of 4.1%**, signaling 
  a deteriorating situation
- **Rwanda** remains virtually unchanged at 6.6 million people
**SSP3**
| Country  | 2010 Population in Poverty | 2030 Population in Poverty | % Change |
|----------|---------------------------|---------------------------|----------|
| Tanzania | 23,017,246 | 16,683,745 | -27.5% ✅ |
| Kenya    | 19,525,472 | 19,444,900 | -0.4% ⚠️ |
| Uganda   | 19,192,324 | 21,481,304 | +11.9% 🔴 |
| Rwanda   | 6,588,251  | 6,595,055  | +0.1% ⚠️ |
| Burundi  | 7,325,353  | 7,628,627  | +4.1% 🔴 |

**Legend:**
- ✅ Declining poverty — positive trend
- ⚠️ Minimal change — stagnating
- 🔴 Increasing poverty — moving away from SDG 1

#### SSP4 - Inequality
Under the SSP4 scenario, all East African countries show a decline 
in poverty by 2030, painting a more optimistic picture compared to 
SSP3. Key findings:

- **Tanzania** leads the region with the largest reduction of **54.5%** 
  making it the strongest performer under this scenario
- **Kenya** shows a significant **34.6% reduction**, a stark contrast 
  to its near stagnation under SSP3
- **Uganda** reverses its SSP3 trend completely, showing a **38.7% 
  decline** instead of an increase
- **Rwanda** and **Burundi** both show reductions of around **34%**, 
  consistent with the regional trend

**Conclusion:** Under SSP4, progress toward SDG 1 is more promising 
across the region. However, it is important to note that SSP4 
represents a deeply unequal world — while aggregate poverty numbers 
may decline, the gains are likely concentrated among elites while 
the poorest remain vulnerable. Ending poverty on paper does not 
necessarily mean ending inequality.

> ⚠️ Note: SSP4 values are at a significantly different scale to SSP3. 
> Clarification on units has been requested from the World Bank CCKP 
> team and findings will be updated upon response.
**SSP4**
  | Country  | 2010 Population in Poverty | 2030 Population in Poverty | % Change |
|----------|---------------------------|---------------------------|----------|
| Tanzania | 55 | 25 | -54.5% ✅ |
| Kenya    | 228 | 149 | -34.6% ✅ |
| Uganda   | 62 | 38 | -38.7% ✅ |
| Rwanda   | 49 | 32 | -34.7% ✅ |
| Burundi  | 77 | 52 | -32.5% ✅ |
**Conclusion:** Under SSP3, SDG 1 is highly unlikely to be achieved 
by 2030 for any East African country. The regional rivalry and poor 
international cooperation storyline leaves millions trapped in 
extreme poverty well beyond the 2030 deadline.

