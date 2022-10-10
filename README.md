# Azure Enterprise Analytics Knowledge

*Knowledge Store for Azure data services technical content: repo of repos*

Contents

- [Useful blogs](#useful-blogs)
    - [General thoughts](#general-thoughts)
    - [Data Lake Guidance](#data-lake-guidance)
    - [Monitoring & Optimisation](#monitoring--optimisation)
- [Labs and Code](#labs-and-code)
    - [Broad range of Labs, including data](#broad-range-of-labs-including-data)
    - [SQL Labs](#sql-labs)
    - [Repos](#repos)
- [Useful videos](#useful-videos)



# Useful Blogs

## General thoughts

[James Serra Delta Lake Blog](https://www.jamesserra.com/archive/2022/03/azure-synapse-and-delta-lake/)
Interesting thoughts on Synapse and Delta

## Data Lake Guidance

[ADLS - Hitchhikers guide to the Data Lake](https://github.com/rukmani-msft/adlsguidancedoc/blob/master/Hitchhikers_Guide_to_the_Datalake.md)
Slightly dated (written in 2020), but still has loads of useful info

[Azure Databricks - ADLS Access Patterns](https://github.com/hurtn/datalake-ADLS-access-patterns-with-Databricks)
Broad discussion of various patterns centred around ADLS, using pass through, service principals, secrets scopes. Includes recommendations. Does not yet included Unity implications.

## Monitoring & Optimisation

[Azure Databricks: Using Tags in Azure Cost Management](https://medium.com/microsoftazure/understanding-azure-databricks-costs-using-azure-cost-management-for-observability-and-chargebacks-86e7911fb989)
Techniques for using tags to understand ADB costs: more detailed tags can give you job level granularity

[Azure Databricks: Using Log Analytics for general analysis and cost management](https://github.com/bricrsa/azuredatabricks_loganalytics)

[Alerting on ADLS activity from Databricks using Databricks audit logs, Log Analytics and Azure Monitor](https://medium.com/@rebremer/how-to-prevent-data-exfiltration-from-azure-databricks-c1c55df5c9f2)

[Azure Databricks Best Practices (Old)](https://github.com/Azure/AzureDatabricksBestPractices/blob/master/toc.md)
PG and community best practices for ADB deployments

[Azure Synapse Analytics: Dedicated Pool - Optimisation with PowerBI report](https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/azure-synapse-analyzer-report-to-monitor-and-improve-azure/ba-p/3276960)
Understanding of table geometry, statistics etc in a hand PBI report, underlying code part of Synapse Toolbox [here](https://github.com/microsoft/Azure_Synapse_Toolbox/tree/master/Synapse_Analyzer/Synapse_BPA_Report).

[Azure Synapse Toolbox](https://github.com/microsoft/Azure_Synapse_Toolbox), includes analyser for dedicated pools, Log Analytics queries for various Synapse engines, distribution advisor

[Azure Synapse Analytics: Dedicated Pool - Optimisation with Log Analytics](https://github.com/bricrsa/SynapseMonitor)
Some more detailed Synapse Log Analytics queries, including cost estimation/attribution per query



# Labs and Code

## Broad range of Labs, including data

[What the Hack](https://microsoft.github.io/WhatTheHack/)


## SQL Labs

[What the hack SQL labs](https://microsoft.github.io/WhatTheHack/043-SQLModernization/)

[Synapse Toolbox](https://github.com/microsoft/Azure_Synapse_Toolbox)
Curated queries for building and monitoring performance, including some PBI built resources


## Repos

https://github.com/hurtn/datalake-on-ADLS

https://github.com/Azure/azure-synapse-analytics-end2end

https://github.com/Azure/AzureDatabricksBestPractices/blob/master/toc.md


# Useful Videos


and related resources

- [Advancing Analytics on YouTube](https://www.youtube.com/c/AdvancingAnalytics/videos)  
  Si Whitely and the Advancing Analytics team make informative videos on all our favourite topics including Databricks, Spark, Delta Lake, Azure Synapse Analytics, Machine Learning etc.  Always well worth a look for an independent opinion.  It's important to __never__ encourage Simon's use of the egregious portmanteau / neologism of his own invention 'Sparkitecture'.

- [Paul Andrew](https://mrpaulandrew.com/2022/06/06/building-a-data-mesh-architecture-in-azure-part-11-lets-recap/)  
  Paul works for Avanade these days and is a popular community speaker on topics like Azure Data Factory, Azure Synapse Analytics and more recently, his extensive series on [Data Mesh](https://mrpaulandrew.com/tag/data-mesh-vs-azure/).  The one-hour video linked above is hosted by our own Kasper de Jonge and is a comprehensive introduction to the subject and some of its issues.  The fact that Paul's full blog series on this is now at 13 parts (as at time of printing) is an indicator that the whole Data Mesh concept is ...  non-trivial.

  Paul also offers his own set of handy [Visio stencils](https://mrpaulandrew.com/2022/08/19/visio-stencils-for-the-azure-solution-architect/) for Azure and Data Factory.  The icons are all massive for some reason, but a useful resource nevertheless.

- [SQLBits](https://sqlbits.com/Content/Event22)  
  SQLBits is the UK's biggest SQL Server, Azure and Power BI conference.  It's still got a strong connection with its SQL Server and DBA roots (hence the name), but make no mistake, this is a very modern conference nowadays.  A whole range of technical topics are covered including those mentioned above, plus (but not limited to) DevOps, performance tuning, Master Data Management (MDM), Spark, Data Mesh, Data Lakehouse architecture to name but a few.

  You may have to register to view the free content via sqlbits.com but the videos are also available on YouTube.  Microsoft community speakers are often well represented with superstars like Bob Ward, Buck Woody, Anna Hoffman, Chris Webb and Guy in a Cube having presented here, but the real star is the community, with Saturday speaking slots normally reserved for them.  They encourage new speakers eg by lighting talks or buddying up with a more experienced speaker and more recently, professional development, mental health and neurodiversity topics have entered the schedule.

  The conference is normally five days including 2 days of full-day workshops, then 3 days of mixed 20 or 50 minutes sessions and a Friday afterparty but you can pick and choose which days you go to.  Importantly, they share all their recorded content **for free** which is impressive.

  The next episode has already been scheduled 14-18 March 2023, location yet to be announced.  Rumour has it they do one year in London and one year not London so it could be in Manchester, Glasgow or even Birmingham next year, like Eurovision.  Co-incidentally this is how me and my wife deal with our respective in-laws.

  It's not particularly cheap with a full 5-day ticket being over £1,000 now, but it's still pretty good value for five days in-person training by some of the best MSFT and community speakers in our space.

