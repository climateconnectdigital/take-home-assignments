# Frontend Take Home Assigment

## Table of contents

- [Frontend Take Home Assigment](#frontend-take-home-assigment)
  - [Table of contents](#table-of-contents)
  - [Carbon Footprint Tracker](#carbon-footprint-tracker)
  - [Requirements](#requirements)
    - [Product](#product)
    - [Tech](#tech)
  - [Data](#data)
  - [Contact](#contact)

## Carbon Footprint Tracker

Transport accounts for around one-fifth of global carbon dioxide (CO2) emissions [24% if we only consider CO2 emissions from energy].1 In some countries – often richer countries with populations that travel often – transport can be one of the largest segments of an individual’s carbon footprint.

Source: https://ourworldindata.org/travel-carbon-footprint

You are tasked with creating a simple carbon footprint tracker for the user to track the carbon emissions they generated based on what transportation they used and the distrance they have travelled for each day they recorded. 

## Requirements

### Product 

The tracker should be a web form where the user can add multiple rows of records. Each row of record should include 3 fields: 

* A calendar picker for the date of travel
* A dropdown menu to select the mode of transportation
* An input to record the number of kilometers travelled. 

The user should be allowed to add multiple records for each day using the same or different mode of transportation and the distance used for each mode.

You will be given a [JSON file](transportation-emissions.json) containing a list of transportations and their corresponding emissions, as demonstrated in the end of this document. Emissions for each most of transportation are expressed in **grams of carbon dioxide per kilometre (gCO2e/km)**.

The Tracker should also have the following features:

* A display area to show
  * Total number of carbon emissions for each record
  * A breakdown of the emissions from each transportation use.
  * A breakdown of the emissions from each day.
  * Total number of carbon emissions for all days and all transportations
* Basic validation to ensure that the input fields are filled out correctly and accurately.
* The ability to reset the form and start over.

To complete this task, you will need implement an algorithm or formula for calculating carbon footprint based on transportation usage by distance per day. 

### Tech

You are expected to create this tracker application in JavaScript with ReactJS. You are free to use any resources, libraries, tools, or references that you find online, but the final code should be your own work. 

You are encouraged to create this application using [component driven development](https://www.componentdriven.org/) practices and use appropriate tools such as Storybook to achieve this goal. Having appropriate documentation and unit-testing throughout your code is also highly recommended.

Please submit your completed code and any instructions or notes in a private GitHub repo. You should also include a brief summary of your approach and any challenges or considerations that you encountered while working on this task.

## Data 

| ID  | Transportation Type                      | GHG emissions (gCO2e/km) |
| --- | ---------------------------------------- | ------------------------ |
| 0   | Black cab (taxi)                         | 211.76                   |
| 1   | Bus                                      | 104.71                   |
| 2   | Coach                                    | 27.79                    |
| 3   | Diesel car, 2 passengers                 | 85.305                   |
| 4   | Diesel car, 4 passengers                 | 42.6525                  |
| 5   | Domestic flight                          | 254.92999999999998       |
| 6   | Eurostar (international rail)            | 5.97                     |
| 7   | Ferry (car passenger)                    | 129.518                  |
| 8   | Ferry (foot passenger)                   | 18.738                   |
| 9   | Large car (diesel)                       | 209.47                   |
| 10  | Large car (hybrid)                       | 131.77                   |
| 11  | Large car (petrol)                       | 282.95                   |
| 12  | Large car (plug-in hybrid electric)      | 77.31                    |
| 13  | Large electric vehicle (UK electricity)  | 66.88                    |
| 14  | Light rail and tram                      | 35.08                    |
| 15  | London Underground                       | 30.84                    |
| 16  | Long-haul flight (business class)        | 434.46000000000004       |
| 17  | Long-haul flight (economy)               | 149.81                   |
| 18  | Long-haul flight (economy+)              | 239.7                    |
| 19  | Long-haul flight (first class)           | 599.25                   |
| 20  | Medium car (diesel)                      | 170.61                   |
| 21  | Medium car (hybrid)                      | 108.95                   |
| 22  | Medium car (petrol)                      | 192.28                   |
| 23  | Medium car (plug-in hybrid electric)     | 70.83                    |
| 24  | Medium electric vehicle (UK electricity) | 53.17                    |
| 25  | Motorcycle (large)                       | 135.01                   |
| 26  | Motorcycle (medium)                      | 102.89                   |
| 27  | Motorcycle (small)                       | 84.45                    |
| 28  | National rail                            | 41.15                    |
| 29  | Petrol car, 2 passengers                 | 96.14                    |
| 30  | Petrol car, 4 passengers                 | 48.07                    |
| 31  | Short-haul flight (business class)       | 233.6                    |
| 32  | Short-haul flight (economy)              | 155.73000000000002       |
| 33  | Small car (diesel)                       | 142.08                   |
| 34  | Small car (hybrid)                       | 105.2                    |
| 35  | Small car (petrol)                       | 153.71                   |
| 36  | Small car (plug-in hybrid electric)      | 29.35                    |
| 37  | Small electric vehicle (UK electricity)  | 45.67                    |
| 38  | Taxi                                     | 150.18                   |

## Contact 

Please contact [Grey](mailto:grey@climateconnect.digital) if you have any questions regarding this task. 