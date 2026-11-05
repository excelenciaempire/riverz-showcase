# Assistant integrations: engineering decisions

## Actor and account

Each team member authorizes their own identity. Requests resolve the account that owns the data separately from the member performing the action, and recheck current membership and permissions.

## Local workspace consent

A local workspace connection covers its projects; project and device IDs route an operation to its destination. They are not separate per-project login grants. Workspace revocation fences pending local controls. Shared account access does not grant another member's private device access.

## Client connection

Discovery and setup links are separate from OAuth consent and a successful authenticated tool call. The external client manages its callback and token storage.

These notes summarize the private implementation and its constraints.

[Case overview](README.md)
