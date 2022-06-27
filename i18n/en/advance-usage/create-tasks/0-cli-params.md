---
sidebar_position: 0
---
# Public Parameter

*** Description of the public parameters of the submitted task ***

primihub-cli Public Parameter：


```bash
--input_datasets (input datasets name list); default: TrainData,TestData;
--job_id (job id); default: "100";
--params (task params, format is <name, type, is array, value>);
  default: BatchSize:INT32:0:128,NumIters:INT32:0:100,TrainData:STRING:0:train_party_0;train_party_1;train_party_2,TestData:STRING:0:test_party_0;test_party_1;test_party_2;
--server (server address); default: "127.0.0.1:50050";
--task_code (task code); default: "logistic_regression";
--task_id (task id); default: "200";
--task_lang (task language, proto or python); default: "proto";
--task_type (task type, 0-ACTOR_TASK, 1-NODE_TASK, 2-PIR_TASK, 3-PSI_TASK, 4-NODE_PIR_TASK, 5-NODE_PSI_TASK); default: 0;
```