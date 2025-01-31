---
'@backstage/plugin-techdocs-backend': patch
---

A `DefaultTechDocsCollatorFactory`, which works with the new stream-based
search indexing subsystem, is now available. The `DefaultTechDocsCollator` will
continue to be available for those unable to upgrade to the stream-based
`@backstage/search-backend-node` (and related packages), however it is now
marked as deprecated and will be removed in a future version.

To upgrade this plugin and the search indexing subsystem in one go, check
[this upgrade guide](https://backstage.io/docs/features/search/how-to-guides#how-to-migrate-from-search-alpha-to-beta)
for necessary changes to your search backend plugin configuration.
