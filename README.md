# Instructions 

This findings repository contains all the valid submissons from auditors. Secure3 team have pre-screened all the submissions and included valid ones, submissions from different auditors for the same issue are deduped.

Issue Explaination 
- Issues are labeled with one of the four severity (Critical, Medium, Low, Informational).
- For duplicate issues, they have same issue title and there are "Duplicate of #x" comment in the issue page.
- Auditors' name are omitted in this repo. However, once the issues are finalized, the auditor name will appear in the final report 


Please go through each issue submission on the [issues page](../../issues) and take action, for each issue please 
- Read through the submission content
- **Mark your response and issue status** with the pre-defined labels below
  - `client-fixed`: the issue is valid and it has been properly fixed 
  - `client-acknowledged`:  the issue is valid but we decide not to fix it this time
  - `client-mitigated`: the issue is partially fixed or mitigated by other methods other than fixing it permanently. Examples: restricting exploit conditions on the dApp, contract state variable set to a value so that the on-chain attack condition is never met, off-chain bot periodically calls a contract function or monitoring, etc
  - `client-declined`: the issue is not valid or it is desired behavior
  - `client-severity-changed`: if you have changed the severity of the issue
- **Comment the actions taken** on each issue with details 
  - fix details
  - acknowledged reason and why decided not to fix this time
  - new commit url
  - reasons you think the issue is invalid
  - reasons you think the issue is not a duplicate
  - and etc
- If you have questions or need more clarification about the status of the issue, please also comment on the issue
