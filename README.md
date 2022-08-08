
# Greenwashing: How European food companies break their plastics promises

  
Two-thirds of pledges to go greener on plastic fail or are dropped, a DW investigation has found. Here's how European food and drink companies break their own commitments, and how legislation might hold them accountable.

This project is a collaboration within the [European Data Journalism Network](https://www.europeandatajournalism.eu/).

**Project lead:** [Deutsche Welle](https://www.dw.com/en/data/t-43091100), research by Julia Merk and Kira Schacht


**Collaborators:** [Alternatives Economiques](https://www.alternatives-economiques.fr/),  [EURACTIV](https://www.euractiv.com/), [Interruptor](https://www.interruptor.pt/), [OBC
Transeuropa](https://www.balcanicaucaso.org/), [Openpolis](https://www.openpolis.it/), [Pod črto](https://podcrto.si/)

*In this repository, you will find methodology, data and code behind this investigation.*

## Read the articles that came out of this collaboration:

Links will be added as articles are published.

DW: *"European food companies break their plastics promises"* [[English](https://www.dw.com/a-62622509) | [German](https://www.dw.com/a-62622558)]

**This repository is maintained by:** [Kira Schacht](https://twitter.com/daten_drang)


# Files


| Name | Content |
|--|--|
| `Database Plastics Promises.xlsx` | The main database used for this project. You can also find it online as a Google Sheet [here](https://docs.google.com/spreadsheets/d/xxx). |


# Data collection
Much of the data we use is collated from various sources and collected for this project by the collaborators.

To select the companies on which to focus, we compiled a list of the biggest food & drinks companies headquartered in Europe, measured by sales/revenue.

The two sources for this were:
- FoodDrink Europe: [Data & Trends, EU Food & Drink Industry](https://www.fooddrinkeurope.eu/wp-content/uploads/2021/02/FoodDrinkEurope-Data-Trends-2020-digital.pdf) 2020, p. 26 ff.
- Forbes: [The Global 2000](https://www.forbes.com/lists/global2000/?sh=2b5ea7f75ac0) 2021

Partners then added the top 10 companies from their respective country for a closer look. Selection criteria were kept as homogenous as possible, but diverged slightly.

| Region | Criteria |
|--|--|
| Global | global sales |
| Italy | revenue |
| Slovenia | total income from sales |
| Germany | revenue |

For each company, we then searched available records starting from the year 200 to find any pledges or goals publicly stated relating to plastic packaging, e.g.
- reduction or replacement of plastic packaging
- recycled content
- recyclability
- plastic waste management
- other targets aiming at reducing plastic pollution

We searched the following sources:
-   Company records (Sustainability Reports, Annual Reports)
-   Websites, including archived versions via the [Internet Archive](https://web.archive.org/)
-   Press releases, including archives
-   News articles available online

For each pledge found, we noted the following
| variable | description |
|--|--|
| pledge year | Year the commitment was made |
| goal year | Year of target |
| description | Specific indicator |
| goal | Target value |
| source | Link to source |
| Notes | Further comments |

We then noted the state of reporting in the baseline year mentioned in the promise, and again in the goal year.

# Analysis

For each promise, we evaluated the data as follows:

### Was the promise fulfilled?
| state | description |
|--|--|
| achieved | Pledge achieved |
| failed | Pledge failed |
| unclear | No information found |
| future | Target year is in the future |

### What is the promise about?

| type | description |
|--|--|
| recycled | Recycled plastics in packaging |
| recyclable | Recyclability of packaging |
| reduce | Reduce total amount or share of plastics / virgin plastics in packaging |
| replace | Replace plastics with other materials in packaging |
| recover | Recover plastic waste for recycling |
| other | Anything else related to plastic packaging |