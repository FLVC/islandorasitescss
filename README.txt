The purpose of this repository is to version css for Islandora sites.

Normally, the workflow should be to make the css change on the test site, then move all css over to the production site.

The need for this repository is that any sites using institutional repository splash pages (FGCU, FAU, etc.) are themed using div and class tags based on Drupal's identifier numbers for blocks.  So, css can't be identical on test and production.  This repository keeps versioned css and allows a quick rollback in case css is copied over from test to production.