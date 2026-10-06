---
expect:
  issue_key: /^PAY-\d+$/
---

{"message": "Issue {{input.issue_key}} transitioned successfully", "transition_id": "{{input.transition_id}}"}
