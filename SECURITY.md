# Security policy

Do not report vulnerabilities in public issues, discussions, or pull requests.

## Reporting

Use GitHub's [private vulnerability reporting][report]; if you cannot use
GitHub, email <chalin@cncf.io>.

A maintainer triages your report privately; valid issues are fixed and disclosed
through a GitHub security advisory, which credits you unless you ask otherwise.

## Supported versions

For the supported release and tool versions, see [Official support][support].

## What to report

Vulnerabilities in:

- the Docsy theme
- the [docsy-example][] site
- their CI and release workflows

## What not to report here

- Issues in Hugo or other upstream dependencies: report them upstream
- Issues in sites built with Docsy: report them to the site's owners
- Behavior whose effects stay within a site owner's own content and
  configuration: not a vulnerability

<!-- prettier-ignore-start -->
[docsy-example]: https://github.com/docsy/docsy-example
[report]: https://github.com/docsy/docsy/security/advisories/new
[support]: https://www.docsy.dev/project/about/changelog/#official-support
<!-- prettier-ignore-end -->
