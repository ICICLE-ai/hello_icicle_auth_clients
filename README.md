# HELLO ICICLE AUTHENTICATION CLIENTS
Repo for Authenticated Clients and Applications for ICICLE CI Services

NOTES:
* YAML file: See
** Component Data Yaml file:  https://github.com/ICICLE-ai/CI-Components-Catalog/blob/master/components-data.yaml


## Overview
The Artificial Intelligence (AI) institute for Intelligent Cyberinfrastructure with Computational Learning in the Environment (ICICLE) is funded by the NSF to build the next generation of Cyberinfrastructure to render AI more accessible to everyone and drive its further democratization in the larger society. ICICLE aims to develop intelligent cyberinfrastructure with transparent and high-performance execution on diverse and heterogeneous environments as well as advance plug-and-play AI that is easy to use by scientists across a wide range of domains, promoting the democratization of AI. The deep AI infrastructure that ICICLE plans to utilize to sift through data relies on knowledge graphs (KGs) in which information is stored in a graph database that uses a graph-structured data model or data model to represent a network of entities and the relationships between them. 

Finding a way to make KGs easily accessible and functional on high performance computing (HPC) systems is an important step in helping to democratize HPC. Thus a large focus of this project was contributing to the body of knowledge needed for hosting live, dynamic, and interactive services that interface with HPC systems hosting KGs for ICICLE based resources and services

In this project, we develop Jupyter Notebooks and Python command line clients that will access ICICLE resources and services using ICICLE authentication
mechanisms. To connect our clients, we used Tapis, which is a framework that supports computational research to enable scientists to access and utilize and manage multi-institution resources and services. We used Neo4j to organize data into a knowledge graph (KG). We then hosted the KG on a Tapis Pod, which offers persistent data storage with a template made specifically for Neo4j KGs. 

## Software Releases

### ICICLE_Release_04_2023

For this software release, we focussed on developing authenticated connections to kubernetes pods hosted on a TapisTACC server (URL???). 

* [Jupyter Notebooks](https://github.com/sdsc-hpc-training-org/hello_icicle_auth_clients/tree/main/ICICLE_Release_04_2023/CLI)
* [Command Line Interfaces](https://github.com/sdsc-hpc-training-org/hello_icicle_auth_clients/tree/main/ICICLE_Release_04_2023/Notebooks)

The Notebooks and the CLIs each have their own directory and software requirements which are described here: 

## REHS Program
We 



