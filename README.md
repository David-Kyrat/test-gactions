# Test Github Actions

1st Test for simple devops stuff and other stuff that gets done when one pushes

## Useful Commands to check action/workflow state

- gh run view --job=20360356378 --json jobs | jq  
- gh run view --job=20360356378 --json status | jq  
- gh run view --job=20360356378 --json status --jq .status  

*Extract json object "jobs" from `gh run view --job=20360356378 --json jobs` output*  
- gh run view --job=20360356378 --json jobs --jq .jobs
