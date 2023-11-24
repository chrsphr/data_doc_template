# Data Import Process Template

> Each dataset will have (at least one) of these process pages. At the top there will be a coversheet with the key attributes

## Dataset Transformation Name

**Version History**
> We will use semantic versioning for publishing

| Version  | Date  | Description  |  
|---|---|---|
|  v1.0 | 24/05/2023  | Initial Release  | 
 
**Jira Reference** - [MDC-266](https://arupdigital.atlassian.net/jira/software/projects/MDC/boards/743?selectedIssue=MDC-226)

> Jira link to the activitiy so it can be tracked

> then we'll have the table with all the key attributes - this will also be copied into the data catalogue

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

## Methodology

> This section needs to describe how we are going from A -> B, with as much info as possible. The goal should be that someone would be able to read this methodology and repeat it. Sceenshots, diagrams and code samples will all supporting in adding context
> Don't forget to include any other external datasets that were used in carrying  out the analysis

### Assumptions

> Subsection in methodology - we need to log assumptions made when processing the data

## Results

> What does the output data look like? 
> Include summary of the output data, key attributes (such as heat, building or site count)
> Errata and known issues - if there's anything wrong with the data that is know, describe it