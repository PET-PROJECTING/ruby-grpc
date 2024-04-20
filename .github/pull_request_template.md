## How to use this template
Each heading below should be kept in the template even if it doesn't apply to your change. If it doesn't apply,
delete the content under the heading and mark the section as "N/A".
Sections marked with *Required* can not be marked as N/A, and must be filled out.

This section "How to use this template" should be removed, with the first section starting at "JIRA Ticket".

## JIRA Ticket
*Required*

[Add a link to your JIRA ticket here]

[MSR-1234](https://jira.teladoc.net/browse/MSR-1234)

## Migrations
[Add a list of any migrations here]
- [Data Migration - 1234](https://jira.teladoc.net/browse/DM-1234)

## Related PRs and Documentation
[Add any related PR's here]
Branch | PR | Repository
------ | ------ | ------
MSR-1234 | [link](https://jira.teladoc.net/browse/MSR-1234) | oms
MSR-1234 | [link](https://jira.teladoc.net/browse/MSR-1234) | internal_documentation

## Impacted Areas of Application
*Required*

[Add a list of the impacted areas of the application here]
- RAV for GM
- RAV for Derm
- Configuration Change (for example Helm values)

# Testing
*Required*

Testing evidence for changes is required in all PR's and must be present in the PR description. Some explanation should
be provided about why the testing done covers the changes made.

Examples of good explanations:

* You add a new feature and write new specs to cover that feature.
* You determine existing specs cover the changes and point out the specific specs that provide that coverage.
* You are making a Production config change and have already tested the equivalent change on preprod.

If your change doesn't apply to one of the subsections (for example a config change probably doesn't require browser testing),
then you can mark that subsection as N/A.

## Browser Testing Checklist

### This PR has been tested in the following browsers:

(**All required for front end changes**)
- [ ] Chrome
- [ ] Safari
- [ ] FireFox
- [ ] Edge
- [ ] IE 11

### This PR has been tested in the following breakpoints

(**All required for front end changes**)
- [ ] 320px (IE not required)
- [ ] 375px (IE not required)
- [ ] 576px (IE not required)
- [ ] 768px
- [ ] 992px
- [ ] 1200px
