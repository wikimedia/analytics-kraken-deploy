# DEPRECATED

THIS REPO IS DEPRECATED.

PLEASE SEE

* https://gerrit.wikimedia.org/r/#/admin/projects/analytics/refinery
* https://gerrit.wikimedia.org/r/#/admin/projects/analytics/refinery/source

INSTEAD.

# kraken-deploy

Deployment repository for
[Kraken](https://gerrit.wikimedia.org/r/#/admin/projects/analytics/kraken).

This repository adds Kraken as a git submodule, and also includes compiled
(.jar and possibly other) artifacts hosted at http://archiva.wikimedia.org
via [git-fat](https://github.com/wikimedia/operations-debs-git-fat).

Artifacts are kept in the ```artifacts``` directory in a Maven-like
repository layout.  E.g. org/wikimedia/project/version/project-version.jar.
These should be added using git-fat.
See the [Archiva - Deploying artifacts in production](https://wikitech.wikimedia.org/wiki/Archiva#Deploying_artifacts_in_production_using_Trebuchet_.28git-deploy.29)
for more information.
