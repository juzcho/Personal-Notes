---
title: Power BI
layout: default
---

# In-Page Navigation
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# Power BI
## Creating Dataflow using API
### This will utilize Power BI Online as th tool to call the API.
- Using Advanced Query Editor to edit the Power Query
#### First part:
- Using API tokens for 2 different websites to gather the site's contents. I had to utilize two different API Tokens to call each site
- Using a specific variable with specific name, editing the advanced query editor to call that variable to get each site's respective contents. This also allowed us to have two different set of dataflow.
#### Second part:
- Once the variable for the API tokens were updated, the column names for the 2 sites were the same
- This then allowed me to merge the two new dataflow created into One signle table with adding "Source" custom column to identify from which dataflow the data is from.
## Tips & Tricks
tips and tricks
# Tasks
- [ ] Architecture of the advacned query code specifically for dataflow.
