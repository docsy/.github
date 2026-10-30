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

- Docsy theme
- [docsy-example][] site
- CI and release workflows of either repository

Docsy inherits [Hugo's security model][hugo-security]. Report issues in Hugo,
other dependencies, or sites built with Docsy to their own maintainers.

<!-- prettier-ignore-start -->
[docsy-example]: https://github.com/docsy/docsy-example
[hugo-security]: https://gohugo.io/about/security/
[report]: https://github.com/docsy/docsy/security/advisories/new
[support]: https://www.docsy.dev/project/about/changelog/#official-support
<!-- prettier-ignore-end -->
