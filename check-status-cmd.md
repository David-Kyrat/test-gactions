gh run view --job=20360356378 --json jobs | jq
gh run view --job=20360356378 --json status | jq
gh run view --job=20360356378 --json status --jq .status

# extract json object "jobs" from `gh run view --job=20360356378 --json jobs` output
gh run view --job=20360356378 --json jobs --jq .jobs
