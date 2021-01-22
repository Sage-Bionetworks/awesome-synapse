# Awesome Synapse Plugins
A curated list of packages and tools using Synapse R, Python, React clients inspired by other awesome-* lists.


## Portals
* [portals](https://github.com/Sage-Bionetworks/portals) - React component based configurations that generate community portals built on top of Synapse
* [Collaboration Portal](https://github.com/Sage-Bionetworks/sagebio-collaboration-portal) - Prototype Collaboration Portal
* [Agora](https://github.com/Sage-Bionetworks/Agora)

## R
* [sagethemes](https://github.com/Sage-Bionetworks/sagethemes) - The sagethemes package provides plot color palettes and themes that use the Sage Bionetworks branded colors.
* [challengerutils](https://github.com/Sage-Bionetworks/challengerutils) - The R version of `challengeutils`
* [dccmonitor](https://github.com/Sage-Bionetworks/dccmonitor) - This package is intended to assist Sage Bionetworks data curators to check the status of metadata and documentation files uploaded via the dccvalidator shiny application

### Shiny
* [SynapseShinyApp](https://github.com/Sage-Bionetworks/SynapseShinyApp) - Basic Shiny application for use on Sage Bionetwork's Synapse web portal.
* [data curator app](https://github.com/Sage-Bionetworks/data_curator) - Data Ingestion Shiny App
* [dccvalidator](https://sage-bionetworks.github.io/dccvalidator/index.html) - package and Shiny app to perform data validation and QA/QC
* [projectLive](https://github.com/Sage-Bionetworks/projectLive) - Track the impact of our funding partners in real time

## Python
* [s3-synapse-sync](https://github.com/Sage-Bionetworks/s3-synapse-sync) - Lambda function code to index files in S3 buckets by creating filehandles on Synapse, triggered by file changes to S3.
* [schematic](https://github.com/Sage-Bionetworks/schematic) - Python package for Data model and Data Ingress Management
* [challengeutils](https://github.com/Sage-Bionetworks/challengeutils/pull/204/files) - Synapse challenge utility functions + more
* [synapseformation](https://github.com/Sage-Bionetworks/synapseformation) - Client for using Synapse Formation templates.
* [synapseMonitor](https://github.com/Sage-Bionetworks/synapseMonitor) - Monitor a Synapse Project / entities scoped by a Synapse file view.
* [synapsegenie](https://github.com/Sage-Bionetworks/synapsegenie) - Crawl through Synapse files to validate and process them given a plugin file format registry.


## Java
* [SynapseWorkflowOrchestrator](https://github.com/Sage-Bionetworks/SynapseWorkflowOrchestrator) - Links one or more Synapse Evaluation queues to a workflow engine. Each Evaluation queue is associated with a workflow template. Each submission is a workflow job, an instance of the workflow template. Upon submission to the Evaluation queue the Workflow Orchestrator initiates and tracks the workflow job, sending progress notifications and uploading log files.


## Workflow

* [CWL Synapse Client](https://github.com/Sage-Bionetworks-Workflows/dockstore-tool-synapseclient) - CWL interface to Synapse command line.
* [nextflow Synapse Client](https://github.com/Sage-Bionetworks/synapse-nextflow) - Nextflow interface to Synapse command line.