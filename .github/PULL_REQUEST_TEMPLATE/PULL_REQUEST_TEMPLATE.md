# PR Template

<!-- This template covers all PRs for Seedcase, please note that if you are: 
a/ submitting a PR for changes to general documentation you should delete the sections
Testing, Code Documentation, and the first part of the Author Checklist
b/ submitting a PR for changes to code you should delete the second section of the
Author Checklist -->

## Description

<!-- DO NOT LEAVE THIS SECTION BLANK -->

- This PR {removes/adds/fixes/replaces} the {feature/bug/issue/documentation/tests}
- These changes are done because of ... {reasons for change/why you're doing it}.
- {Remove this if not needed} Other solutions included ...

## Type of Pull Request (please select all that apply)

- [ ] Feature
- [ ] Bug Fix
- [ ] Refactoring
- [ ] Chore
- [ ] Performance improvement
- [ ] Test
- [ ] Build
- [ ] Revert
- [ ] CI
- [ ] Code documentation update
- [ ] General Documentation update (all documentation that is not related specifically to code)

<!--TODO are we missing any here? -->

## Related Issues

<!-- Connect this PR to relevant issues, to help the reviewer but also for record-keeping. -->

See Issues: #...

<!-- Also list issues the PR closes -->

Closes Issue ...

## Testing

- [ ] Yes
- [ ] No, not needed (give a reason below)
- [ ] No, I need help writing them

<!-- Please explain why the tests are not needed for this PR here -->

## Code Documentation

<!-- Please detail which parts, if any, of the documentation has been updated -->

## Reviewer Focus

<!-- Any particular section the reviewer should focus on, anywhere that would be a good place to start? -->

## Code Author Checklist

<!-- This is to help you determine if your work is ready to be reviewed, if an item is not relevant then you can mark it as done (because you have checked and found that it isn't needed) -->

For all PRs that are not general documentation

- [ ] Tests accompany or reflect changes to the code
- [ ] Tests ran and passed locally
- [ ] Ran the linter and formatter
- [ ] Build has passed locally
- [ ] Relevant documentation has been updated

For general documentation:

- [ ] Spell-check
    - [ ] US
    - [ ] UK
- [ ] Did the page(s) preview correctly on your machine without breaking
- [ ] New category words (keywords) (if any) added to the code snippet file