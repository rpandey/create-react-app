### Github Issue or Jira
<!-- Replace with Jira ticket: https://jira.homeawaycorp.com/browse/PB-1234 -->

### Description
<!-- Steps to reproduce -->
<!-- Proctor test name -->
<!-- Useful links -->

### Blockers
<!-- Translations -->
<!-- Mocks -->

### How to Test
<!-- Steps to test -->
<!-- Credentials -->

### Screenshot(s)
<!-- Before.png -->
<!-- After.png -->

### PR Author Checklist
- [ ] JIRA ticket number & title in PR title ([SE-XXXX]: Ticket title)
- [ ] Rebased with latest master and DEPLOYED INSTANCE URL filled in from SPAWG
- [ ] Code follows coding style guideline as mentioned in https://confluence.expedia.biz/display/TRAVHOME/Stay-UI+coding+style+guideline
- [ ] Added details of experiment in the doc https://confluence.expedia.biz/display/TRAVHOME/List+of+experiments+in+stay-ui
- [ ] Review requested on Slack https://homeaway.slack.com/archives/CJMC58WES
- [ ] Acceptance criteria documented in JIRA ticket
- [ ] Jenkins build passes successfully
- [ ] Test coverage is not reduced
- [ ] Preliminary review completed by peer in the same domain
- [ ] Design and product approval (if applicable)
- [ ] Tested and attached full screen screenshots for Chrome, Firefox, Safari and IE on Web
- [ ] Tested and attached screenshots for Chrome and Safari on mWeb if applicable

### Reviewer Checklist
- [ ] Jenkins build/test passed and reported back green.
- [ ] Package.json, package-lock.json are updated properly if applicable
- [ ] Unit tests added
- [ ] Validated against acceptance criteria in JIRA ticket
- [ ] Verified author checklist is valid as filled by the author
- [ ] Tested in deployed URL : Test by adding cookie 'HASESSIONV3_STG' by copying the same from a logged in session of  stage environment (https://stage.vrbo.com/)
- [ ] Verify screenshots attached for all browsers
