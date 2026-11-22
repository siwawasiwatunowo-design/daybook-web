# Daybook Web — Retired

The legacy standalone planner UI has been retired as part of the Daybook product direction.

Daybook is now focused on the Android experience:
- Notes
- Meeting Intelligence
- Learning Experience
- Speaking Coach

The old Timebox, Dreams, and Bucket List web interfaces are no longer active. This repository intentionally keeps a small retirement notice at `index.html`.

## Data safety

This retirement changes only the web frontend. It does not delete Firestore documents or alter the shared `users/{uid}/entries` collection. Android Notes continues to use the same account collection.

The previous implementation remains available in Git history if needed for reference.
