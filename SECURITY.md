# Security policy

This policy applies to every repository in the [docsy GitHub organization][org].
Do not report vulnerabilities in public issues, discussions, or pull requests.

## Reporting

Use GitHub's private vulnerability reporting on the affected repository: open
its **Security** tab, then **Report a vulnerability**. For the theme, that is
the [docsy/docsy advisory form][report]. If you cannot use GitHub, email
<chalin@cncf.io>.

A maintainer triages your report privately. Valid issues are fixed and disclosed
through a GitHub security advisory on the affected repository, which credits you
unless you ask otherwise.

## Supported versions

Only the latest release receives fixes; to update, see [Update your Docsy
site][update].

## Scope

In scope: the Docsy theme in every install form (the `@docsy/theme` npm package,
the Hugo module, the git submodule), the [docsy-example][] site, and the
organization's CI and release workflows. The high-impact cases: markup or script
injection through the theme's templates or bundled JavaScript, and the publish
pipeline.

Out of scope: Hugo and other upstream dependencies (report them upstream), sites
built with Docsy (report to the site's owners), and behavior whose effects stay
within a site owner's own content and configuration.

## Verifying a release

`npm audit signatures` checks that a registry-installed `@docsy/theme` carries a
valid signature and provenance attestation (stable releases since 0.17.0 are
published from CI with provenance; for the pipeline, see [Publishing a
release][publish]). Hugo module and git submodule installs carry no attestation.

<!-- prettier-ignore-start -->
[docsy-example]: https://github.com/docsy/docsy-example
[org]: https://github.com/docsy
[publish]: https://www.docsy.dev/project/about/maintainer-notes/#publishing-a-release
[report]: https://github.com/docsy/docsy/security/advisories/new
[update]: https://www.docsy.dev/docs/update/
<!-- prettier-ignore-end -->
