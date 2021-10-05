# Contributing to IDSA Github

This is the official repository of [IDSA](https://www.internationaldataspaces.org) to provide a general overview of what is available on the IDS Open Source Landscape.

All content published here is provided and approved by the IDSA Head Office. Detailed information on the contribution process can be found in the [IDS-G Handbook](Handbook/README.md). Nevertheless, you are very welcome to contribute
to this project when you find a bug, want to suggest an improvement, or have an idea for a useful
feature. For this, always create an issue and a corresponding branch, and follow our style
guides as described below.

Please note that we have a [code of conduct](CODE_OF_CONDUCT.md) that all contributors should stick to.

## Changelog

We document changes in the [CHANGELOG.md](CHANGELOG.md) on root level which is formatted and
maintained according to the rules documented on http://keepachangelog.com.

## Issues

You always have to create an issue if you want to propose or integrate a bugfix, improvement, or feature.
Briefly and clearly describe the purpose of your contribution in the corresponding issue.
The pre-defined [labels](#labels) improve the understanding of your intentions and help to follow
the scope of your changes.

**Bug Report**: As mentioned above, bug reports should be submitted as an issue. To give others
the chance to reproduce the error in order to find a solution as quickly as possible, the report
should at least include the following information:
* Description: What did you expect and what happened instead?
* Steps to reproduce (system specs included)
* Relevant logs and/or media (optional): e.g. an image

## Labels

The [labels](https://github.com/International-Data-Spaces-Association/ids-g/labels) are listed at the
[issues](https://github.com/International-Data-Spaces-Association/IDS-G/issues).
There are two types of labels: one describes the content of the issue and should be used by the
developer that creates the issue. The other one, starting with `status`, will be added from the
developer that takes on the issue. New issues should be initially marked with `status:open`.
*  Basic labels: `bug`, `enhancement`, `suggestion`, `documentation` `outdated`, `question`, `discussion`
*  `status:closed`: issue is closed (after successful approval by issuer and QA)
*  `status:duplicate`: issue is a duplicate of another linked issue and therefore discontinued
*  `status:in-progress`: issue has been assigned and is currently being worked on
*  `status:on-hold`: issue may be implemented at a later date
*  `status:open`: issue has been submitted or re-opened recently
*  `status:out-of-scope`: issue is considered out of the project's scope and therefore not further considered
*  `status:resolved`: issue has been implemented and tested by a developer
*  `status:wont-fix`: issue is in scope but considered impossible or too expensive to deal with

## Branches

After creating an issue yourself or if you want to address an existing issue, you have to create a
branch with a unique number and name that assigns it to an issue. Therefore, follow the guidelines
at https://deepsource.io/blog/git-branch-naming-conventions/. After your changes, update the
`README.md`, Wiki, and `CHANGELOG.md` with necessary details. Then, create a pull request and note
that **committing to the main branch is not allowed**. Please use the feature `linked issues` to
link issues and pull requests.

Pull requests have to be approved by the IDSA Head Office.

## Commits

We encourage all contributors to stick to the commit convention following the specification on
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/). In general, use  the
imperative in the present tense. A quick overview of the schema:
```
<type>[optional scope]: <description>
[optional body]
[optional footer(s)]
```

Types: `fix`, `feat`, `chore`, `test`, `refactor`, `docs`, `release`. Append `!` for breaking
changes to a type.

An example of a very good commit might look like this: `feat![login]: add awesome breaking feature`


## Versioning
IDSA uses the [SemVer](https://semver.org/) for versioning. The release versions
are tagged with their respective version.
