---
expect:
  issue_key: /^PAY-\d+$/
  transition_id: ["21", "31", "41", "51"]
---

{"message": "Issue {{input.issue_key}} transitioned successfully", "transition_id": "{{input.transition_id}}"}
