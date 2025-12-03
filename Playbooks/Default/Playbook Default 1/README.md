# Playbook Default 1




**Enabled:** True

**Version:** 1

**Type:** Playbook

**Priority:** 2

**Playbook Simulator:** False


### Playbook Trigger
**Trigger Type:** All

**Conditions Operator:** And

##### Conditions
|Key|Operator|Value|
|---|--------|-----|
||Equals||


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|Siemplify_Assign Case_1|Assign case to specific user or usergroup|Siemplify|Assign Case|
|Siemplify_Get Case Details_1|This action will get all the data from a case and return a JSON result.  The result includes comments, entity information, insights, playbooks that ran, alert information and events.|Siemplify|Get Case Details|
|Siemplify_Add Entity Insight_1|Add an insight configurable message to each targeted entity|Siemplify|Add Entity Insight|

