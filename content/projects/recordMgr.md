---
title: "Reliable Management System for Record Operations"
description: "Associated with Illinois Institute of Technology"
dateString: Mar 2023 - Apr 2023
draft: false
tags: ["C", "Database", "Postgresql"]
showToc: false
weight: 203
--- 

#### 🔗 [View Project](https://github.com/anushasonte/ADO/tree/main/RecordManagar)

## Description
The purpose of this project is to create a Record Manager. The record manager handles tables with a fixed schema. Clients can insert records, delete records, update records, and scan through the records in a table. A scan is associated with a search condition and only returns records that match the search condition. Each table should be stored in a separate page file and your record manager should access the pages of the file through the buffer manager created previously. 

There are five types of functions in the record manager: functions for table and record manager management, functions for handling the records in a table, functions related to scans, functions for dealing with schemas, and function for dealing with attribute values and creating records. Additionally TID and tombstone mechanism is implemented to handle deleted records efficiently.
