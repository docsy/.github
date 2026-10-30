# Security policy

Do not report vulnerabilities in public issues, discussions, or pull requests.

## Reporting

Use GitHub's [private vulnerability reporting][report]; if you cannot use
GitHub, email <chalin@cncf.io>.

A maintainer triages your report privately; valid issues are fixed and disclosed
through a GitHub security advisory, which credits you unless you ask otherwise.

## Supported versions

For the supported release and tool versions, see [Official support][support].

## In scope

- The Docsy theme
- The [docsy-example][] site
- Their CI and release workflows

## Out of scope

- Hugo and other upstream dependencies: report them upstream
- Sites built with Docsy: report to the site's owners
- Behavior whose effects stay within a site owner's own content and
  configuration

## Verifying a release

`npm audit signatures` checks that a registry-installed `@docsy/theme` carries a
valid signature and provenance attestation (stable releases since 0.17.0 are
published from CI with provenance; for the pipeline, see [Publishing a
release][publish]). Hugo module and git submodule installs carry no attestation.

<!-- prettier-ignore-start -->
[docsy-example]: https://github.com/docsy/docsy-example
[publish]: https://www.docsy.dev/project/about/maintainer-notes/#publishing-a-release
[report]: https://github.com/docsy/docsy/security/advisories/new
[support]: https://www.docsy.dev/project/about/changelog/#official-support
<!-- prettier-ignore-end -->
