---
layout: default
---

## The Inter-Sectoral Impact Model Intercomparison Project

# ISIMIP3a 

## Simulation protocol

last updated [insert automatic date here]


## Introduction

### ISIMIP: General concept
**This should be a part that is only visible if no filter was set.**

ISIMIP provides a framework for the collation of a consistent set of climate impact data across sectors and scales. This framework will s erve as a
basis for model evaluation and improvement, allowing for improved estimates of the biophysical and socio-economic impacts of climate change at
different levels of global warming. It also provides a unique opportunity for considering interactions between climate change impacts across
sectors through consistent scenarios.
ISIMIP is intended to be structured in successive rounds, each having its own focus topics (see section 2.1) and focus regions (see section 2.2) that
inform the scenario design. The main components of the ISIMIP framework are:

* A common set of climate and other input data which will be distributed via a central database
* A common modelling protocol to ensure consistency across sectors and scales in terms of data, format and scenario set-up
* A central archive where the output data will be collected and made available to the scientific community


## Motivation of experiment design
**This should be a part that is only visible if no filter was set.**

This chapter provides a short description of the scientific rationale behind the design of each of the experiments in ISIMIP2a. The details of the
experiments are further described in the remainder of the protocol.

## Common input data
**This should be a part that is always visible.**

This chapter describes climate forcing data and other input data that should be used by modelling groups in all sectors. See chapter 7 for
additional, sector-specific input data and data for model validation. Note in particular that for some sectors the individual tasks (e.g. historical
validation runs ISIMIP2a) may involve several different experiments with differences in input data and other settings. In this chapter we only
describe the general rationale of the different tasks and list the common input data sets.
If you require additional input data that is neither specified in this chapter nor in chapter 7, please use your default data source. In case anything
remains unclear please contact the coordination team or sectoral coordinators.

### Historical validation runs
#### Atmospheric data
Here is an example of text that is shortened (do not expect sense).

<div class="topic topic-rivers">
*part only shown for river floods*
Please use the historical climate data listed in Table 3 for the historical validation runs. The runs should start in 1971, or earlier if spin-up is needed
(see below and section 6.1). All data will be available through the ISIMIP website, www.isimip.org. Separate historical simulations should be
conducted with each of four different datasets, in the order indicated in the last column of Table 3. This is becaus e each of the datasets has its
own advantages and shortcomings, and thus by using several it will be possible to assess the influence of the choice of forcing data on the overall
results. 
</div>

<div class="topic topic-rivers topic-biomes">
*part shown for river floods and biomes*
Moreover, this procedure serves the needs of the different participating sectors (e.g. data over ocean is needed for the fisheries sector),
and facilitates consistency with other model intercomparison exercises (e.g. ISIMIP Fast Track; GSWP3). Modelling groups that cannot run all four
datasets before the submission deadline should nonetheless begin in the order indicated, and inform the ISIMIP coordination team.
</div>

*part always shown*
Historical CO2 concentrations are also provided in the input data archive (historical_CO2_annual.txt). They are based on time series of global
atmospheric CO2-concentrations from Meinshausen, Raper, & Wigley (2011) for 1765-2005 and Dlugokencky & Tan (2014) from 2006-2013.

<div class="topic topic-coasts">
*part only shown for coastal systems*
Note that simulation results only need to be submitted for the reporting periods specified in s ection 6.1. The parts of the climate forcing data prior
to the reporting period may be used for spin-up purpos es and/or to facilitate further analyses. Simulation results for years outside the reporting
period may still be submitted to the ISIMIP repository on a voluntary basis.
</div>



## ---Formatting options below, for reference and cherrypicking ---


<div class="datatable-begin"></div>

Variable    | Name           | Unit (NetCDF format) | Frequency | Bias correction method
------- | ------------------------------------- | -------- | -------- | -----------
Apples  | A small, somewhat round ...           | Fruit    | Fuji     |  lala
Bananas | A long and curved, often-yellow ...   | Fruit    | Snow     |  lala
Kiwis   | A small, hairy-skinned sweet ...      | Fruit    | Golden   |  lala 
Oranges | A spherical, orange-colored sweet ... | Fruit    | Navel    |  lala

<div class="datatable-end"></div>



Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

### Check out datatables

<div class="datatable-begin"></div>

Food    | Description                           | Category | Sample type
------- | ------------------------------------- | -------- | -----------
Apples  | A small, somewhat round ...           | Fruit    | Fuji
Bananas | A long and curved, often-yellow ...   | Fruit    | Snow
Kiwis   | A small, hairy-skinned sweet ...      | Fruit    | Golden
Oranges | A spherical, orange-colored sweet ... | Fruit    | Navel

<div class="datatable-end"></div>


```
The final element.
```
