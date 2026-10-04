# Studio in the Cloud implementation plan

Convert the cloud-production architecture notes into one testable rendering workflow before expanding the platform.

Status: proposed next work, prepared from local source inspection on 2026-10-04. Existing behavior below has not been rerun or release-verified in this planning pass. Update this file as work lands; check an item only after recording its acceptance evidence.

## Current evidence

The folder is a design collection covering render farms, task distribution, result submission, resource allocation, and live streaming. index.md describes a broad OCI studio vision; no runnable application manifest was found.

## Pending implementation

- [ ] Select one narrow prototype: submit a small scene, divide frames into tasks, render on a worker, and collect outputs; record the renderer and execution environment.
- [ ] Define job/task IDs, artifact locations, retries, duplicate-result handling, cancellation, and cleanup ownership using the existing workflow documents.
- [ ] Build a local or mocked single-worker proof with one intentionally failed task and a retry that does not duplicate final frames.
- [ ] Estimate time, transfer volume, storage, and cost from that proof before proposing cloud resource provisioning or a multi-node run.

## Acceptance

A sample scene yields a complete ordered frame set; failure and retry are visible; cancellation and cleanup affect only resources owned by that job.

## Scope and decisions

The OCI platform vision is a design proposal. Renderer licensing, cloud budget, and first customer workflow remain open; no resources are provisioned here.

## Sources

- [index.md](<index.md>)
- [Distributed Rendering.md](<Distributed Rendering.md>)
- [Task Distribution.md](<Task Distribution.md>)
- [Result Submission.md](<Result Submission.md>)
- [Cleanup and Resource Management.md](<Cleanup and Resource Management.md>)
