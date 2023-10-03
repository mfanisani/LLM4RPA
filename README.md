# LLMs and Process Mining: Challenges in RPA Task Grouping, Labelling and Connector Recommendation

This repository contains the code and data for the paper "LLMs and Process Mining: Challenges in RPA Task Grouping, Labelling and Connector Recommendation" by Mohammadreza Fani Sani, Michal Sroka, and Andrea Burattin accepted at Process Querying, Manipulation, and Intelligence 2023. 
The paper investigates how large language models (LLMs) can be used to enhance the process mining capabilities for robotic process automation (RPA) scenarios, focusing on three main challenges: task grouping, task labelling and connector recommendation.

## Task Grouping and Labelling
The corresponding prompt template for these tasks are given in prompt_template_task_grouping.txt

## Connector Recommendation
The corresponding prompt template for this task is given in prompt_template_connector_recommendation.txt

Note that both prompts have place holders that are indicated by <> tags for example, <traces> and <list_of_connectors> for connector recommendation. These place holders should be filled by the corresponding data before calling LLM.
