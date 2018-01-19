## Purpose
> LDAP is a core protocol that is used to store user, role, and group information.Identity server already supports connecting to LDAP supported authz systems for authentication and authorization. The idea of this project is to make IS itself act as a LDAP protocol provider.
## Goals
> The general model adopted by this protocol is one of clients performing protocol operations against servers.  In this model, a client send a protocol request describing the operation to be performed to a server.  The server is then responsible for performing the necessary operation(s) in the Directory.Protocol operation are exchanged at the LDAP message layer.For the purposes of protocol exchanges, all protocol operations are encapsulated in a common envelope, the LDAPMessage.
Here capture the LDAPmessage  at LDAP endpoint and Identify the message element and map it into java objects. Identity server  can use these objects to do operation  with JDBC, MySQL,  LDAP or any other type of database.

## Approach
> Describe how you are implementing the solutions. Include an animated GIF or screenshot if the change affects the UI (email documentation@wso2.com to review all UI text). Include a link to a Markdown file or Google doc if the feature write-up is too long to paste here.

## User stories
> Summary of user stories addressed by this change>

## Release note
> Brief description of the new feature or bug fix as it will appear in the release notes

## Documentation
> Link(s) to product documentation that addresses the changes of this PR. If no doc impact, enter “N/A” plus brief explanation of why there’s no doc impact

## Training
> Link to the PR for changes to the training content in https://github.com/wso2/WSO2-Training, if applicable

## Certification
> Type “Sent” when you have provided new/updated certification questions, plus four answers for each question (correct answer highlighted in bold), based on this change. Certification questions/answers should be sent to certification@wso2.com and NOT pasted in this PR. If there is no impact on certification exams, type “N/A” and explain why.

## Marketing
> Link to drafts of marketing content that will describe and promote this feature, including product page changes, technical articles, blog posts, videos, etc., if applicable

## Automation tests
 - Unit tests 
   > Code coverage information
 - Integration tests
   > Details about the test cases and coverage

## Security checks
 - Followed secure coding standards in http://wso2.com/technical-reports/wso2-secure-engineering-guidelines? yes/no
 - Ran FindSecurityBugs plugin and verified report? yes/no
 - Confirmed that this PR doesn't commit any keys, passwords, tokens, usernames, or other secrets? yes/no

## Samples
> Provide high-level details about the samples related to this feature

## Related PRs
> List any other related PRs

## Migrations (if applicable)
> Describe migration steps and platforms on which migration has been tested

## Test environment
> List all JDK versions, operating systems, databases, and browser/versions on which this feature/fix was tested
 
## Learning
> Describe the research phase and any blog posts, patterns, libraries, or add-ons you used to solve the problem.
