# Queue: durable work between skills

<!-- Source skills append pending entries. Target skills mark the same entry done and add
     outputs. Never delete an entry; a new need gets a new ID. -->

## Queue

<!-- Entry shape:
### <queue-id>
- status: pending
- from: recall
- to: steward
- created: YYYY-MM-DD
- source_paths: [wiki/<path>.md]
- request: <one concrete job>
- completed: null
- output_paths: []
-->
