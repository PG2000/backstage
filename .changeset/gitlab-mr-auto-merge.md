---
'@backstage/plugin-scaffolder-backend-module-gitlab': patch
---

Added an `autoMerge` boolean input to the `publish:gitlab:merge-request` scaffolder action. When set to `true`, the merge request is automatically merged once its pipeline succeeds, using GitLab's auto-merge feature.
