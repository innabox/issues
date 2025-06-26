This repository contains general issues relating to the AI-in-a-box project.

## Quick links

### Issues

- [All issues](https://github.com/search?q=org%3Ainnabox+state%3Aopen&type=issues)

Find issues by label across all innabox repositories:

<!--
gh api /repos/innabox/issues/labels |
jq -r '
  .[]|
  {
    name: .name,
    description: .description,
    slug: .name|gsub(" "; "%20")
  }|
  "- [\(.name)](https://github.com/search?q=org%3Ainnabox+label%3A\(.slug)+state%3Aopen&type=issues) -- \(.description)"
'
-->

- [blocked](https://github.com/search?q=org%3Ainnabox+label%3Ablocked+state%3Aopen&type=issues) -- Blocked
- [bug](https://github.com/search?q=org%3Ainnabox+label%3Abug+state%3Aopen&type=issues) -- Something isn't working
- [development](https://github.com/search?q=org%3Ainnabox+label%3Adevelopment+state%3Aopen&type=issues) -- This issue requires development work
- [documentation](https://github.com/search?q=org%3Ainnabox+label%3Adocumentation+state%3Aopen&type=issues) -- Improvements or additions to documentation
- [duplicate](https://github.com/search?q=org%3Ainnabox+label%3Aduplicate+state%3Aopen&type=issues) -- This issue or pull request already exists
- [enhancement](https://github.com/search?q=org%3Ainnabox+label%3Aenhancement+state%3Aopen&type=issues) -- New feature or request
- [good first issue](https://github.com/search?q=org%3Ainnabox+label%3Agood%20first%20issue+state%3Aopen&type=issues) -- Good for newcomers
- [help wanted](https://github.com/search?q=org%3Ainnabox+label%3Ahelp%20wanted+state%3Aopen&type=issues) -- Extra attention is needed
- [incident](https://github.com/search?q=org%3Ainnabox+label%3Aincident+state%3Aopen&type=issues) -- A specific event resulting in a service outage
- [infrastructure](https://github.com/search?q=org%3Ainnabox+label%3Ainfrastructure+state%3Aopen&type=issues) -- Infrastructure issues not directly related to development
- [invalid](https://github.com/search?q=org%3Ainnabox+label%3Ainvalid+state%3Aopen&type=issues) -- This doesn't seem right
- [p0](https://github.com/search?q=org%3Ainnabox+label%3Ap0+state%3Aopen&type=issues) -- Highest priority
- [p1](https://github.com/search?q=org%3Ainnabox+label%3Ap1+state%3Aopen&type=issues) -- Medium priority
- [p2](https://github.com/search?q=org%3Ainnabox+label%3Ap2+state%3Aopen&type=issues) -- Low priority
- [placeholder](https://github.com/search?q=org%3Ainnabox+label%3Aplaceholder+state%3Aopen&type=issues) -- Placeholder for one or more future issues
- [question](https://github.com/search?q=org%3Ainnabox+label%3Aquestion+state%3Aopen&type=issues) -- Further information is requested
- [refactoring](https://github.com/search?q=org%3Ainnabox+label%3Arefactoring+state%3Aopen&type=issues) -- Refactor existing code
- [research](https://github.com/search?q=org%3Ainnabox+label%3Aresearch+state%3Aopen&type=issues) -- This will consist mostly of information gathering
- [security](https://github.com/search?q=org%3Ainnabox+label%3Asecurity+state%3Aopen&type=issues) -- This is a security issue
- [technicaldebt](https://github.com/search?q=org%3Ainnabox+label%3Atechnicaldebt+state%3Aopen&type=issues) -- Fixing this will reduce technical debt
- [upstream](https://github.com/search?q=org%3Ainnabox+label%3Aupstream+state%3Aopen&type=issues) -- This is a bug in a product on which we depend
- [wontfix](https://github.com/search?q=org%3Ainnabox+label%3Awontfix+state%3Aopen&type=issues) -- This will not be worked on

### Pull requests

- [All pull requests](https://github.com/search?q=org%3Ainnabox+state%3Aopen&type=pullrequests)

