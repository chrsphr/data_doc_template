# Data Product Template

> the goal of this document is to provide a complete manual or user guide to the data that is being produced. Good examples can be found [here](https://www.ordnancesurvey.co.uk/documents/product-support/tech-spec/os-open-greenspace-technical-specification.pdf) and [here](https://www.gov.scot/binaries/content/documents/govscot/publications/advice-and-guidance/2018/11/scotland-heat-map-documents/documents/scotlands-heat-map-user-guidance/2-0-user-guide/2-0-user-guide/govscot%3Adocument/Scotland%2BHeat%2BMap%2B-%2B2.0%2B-%2BUser%2BGuide.pdf)

## Data Product Name
> e.g. 'Consolidated Demand Dataset or 'Existing Heat Networks'

**Version History**
> We will use semantic versioning for publishing

| Version  | Date  | Description  |  
|---|---|---|
|  v1.0 | 24/05/2023  | Initial Release  | 
 
**Jira Reference** - [MDC-266](https://arupdigital.atlassian.net/jira/software/projects/MDC/boards/743?selectedIssue=MDC-226)

> Jira link to the activitiy so it can be tracked

> then we'll have the table with all the key attributes - this will also be copied into the data catalogue.. I think this will be different for the data products, may just be a list of GEMINI/INSPIRE Metadata (TODO)


| Entry                   | Description                                                                                                                                                                                                                     |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Incoming Name           | Name of dataset as we receive it                                                                                                                                                                                                |
| Data Name               | Name of data if changed from incoming name when in SDE                                                                                                                                                                          |
| SDE Name                | Name of SDE which data will be stored in                                                                                                                                                                                        |
| Version                 | P01, P02 etc. If we recieve an update of an existing dataset, the new revision should go up one number                                                                                                                          |
| Summary                 | Describe the purpose of the data in a clear and concise statement. This information helps potential users and data consumers understand the context and relevance of the dataset. It should address the dataset’s intended use. |
| Status                  | Live / Superseded / Archived                                                                                                                                                                                                    |
| Workpackage             | Work stream name                                                                                                                                                                                                                |
| Team                    | GIS / Energy Modelling                                                                                                                                                                                                          |
| Date Published          | Date data published if applicable                                                                                                                                                                                               |
| Date received/ obtained | Date we received the data                                                                                                                                                                                                       |
| Source Name             | Source of datas name                                                                                                                                                                                                            |
| Source URL              | Source URL if applicable                                                                                                                                                                                                        |
| Incoming Folder Name    | Full link to incoming folder name                                                                                                                                                                                               |
| Logged By               | Who logged the data                                                                                                                                                                                                             |
| Use constraints         | Capture information related to copyright, licensing, and access restrictions. If in doubt, the dataset should have a constraint to only use on the project it was collected/created for (e.g. For use on 285400-00).            |
| Description             | An abstract with details about the dataset’s content and subject matter.                                                                                                                                                        |
| Copyright               | Any copyright information                                                                                                                                                                                                       |
| Confidentiality         | Confidentiality                                                                                                                                                                                                                 |
| Confidence              | Confidence                                                                                                                                                                                                                      |
| Processing Required     | This will be described in full in the methodology below, but can be summarised here

## Overview

> A quick summary of what this dataset is, and what is it for. Some pictures will help

## Changelog

> Describe any methodological changes that have occured in the different versions of this product. descibe known issues with the dataset and errata

### V2.0

### V1.0

## Data Structure

> The propose of this section will be to explain how the dataset is structure, and what is in it
> Must describe the geometry type and CRS.

### Input Data

| Dataset  | Version  | Prorcess Documentation  |  
|---|---|---|
|  NHS ERIC | v1.0  | [Link to the process Docs](http://example.com)  | 

### Data Model Overview

> describe the data model, i.e. how things are link, what the primary keys are

### Feature Types

> List every field in the dataset, and describe it. We will use snake_case for the field names

| Attribute  | Definition  | Type  | Length  | Multiplcitiy |
|---|---|---|---|---|
|  uprn | Unique Property Reference Number  | Integer  |12 |[0..1] | 
|  demand_class | type of heat demand  | string  |32 |[1] | 

### Code Lists

> For every field in the dataset which has a fixed list of possible answers, we will list them here

**demand_class**

| Value  | Description  | 
|---|---|
|  building | a demand value which is attributed to an OS building part TOID or OSID | 
|  site | a demand value which is attributed to an OS site TOID or OSID   | 


