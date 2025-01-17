# For Contributors

## Preparation

Familiarize yourself with the short version of our [IntegrationHub Spoke Best Practices](https://github.com/ServiceNowDevProgram/SpoketoberfestResources/blob/master/SpokeDevelopmentBestPracticesPublic.docx?raw=true). This has been edited to the top recommendations. There is a 30 page version also available but start with the abbreviated version.

## Choose What to Work on

Select the project you wish to join! (List below)

Please search the issue tracker for any project before creating a new issue (problem or an improvement request). Feel free to add issues related to the project.

If you feel that you can fix or implement it yourself, please read the below to learn how to submit your changes.

## Submitting Changes

1. Comment on the issue, so others know you are working on the issue.
1. Fork the project
1. Create a user account and grant it Admin role on your Personal Developer Instance (PDI) with the same name as your GitHub account and switch to it.
1. Install your fork on your PDI with credentials (so you have write access)
1. Create Branch something-descriptive
1. Make your contribution
1. Commit your changes
1. Create a Pull Request

## For maintainers

 Each of the Spokes needs one maintainer. If you wish to be the Repo owner - please reach out to Andrew Barnes or Dave Slusher for access and include your GitHub account name.

 If you wish to maintain a repo, you have a couple of options. Everyone can work in the same instance, you can have users fork and perform full PR, or if you have lots of contributors use GitHubCompanion.

## Same Instance: Start Contributing!

### Small number of contributors

Accept the PR in GitHub - then sync the instance you are managing from the updated Repo. You may need to stash changes and reapply after sync. **Note: this does empty our your application locally - data in tables will be lost**

### Many Contributors - GitHubCompanion

1. Download and install [update set batch](https://github.com/ServiceNowDevProgram/SpoketoberfestResources/raw/master/2GHC.xml)
1. Auth to GitHub via Repositories module
1. Setup Repo's via Repo Config module
    > Important note, you need to have pulled the application from source control into the instance first
1. Click the *Subscribe to pull requests* UI Action
1. Once you have pull requests, you can open them, and use the *Open in Portal* UI action to via the differences and accept the PR.
1. Once you click accept, it loads those files into the SN Instance, and you must then use Studio to Commit to your Repo.

## List of suggested IntegrationHub Spokes

* Airtable
* Bamboo
* Circle CI
* Dropbox
* FTP
* Facebook
* GitLab
* Instagram
* LastPass Enterprise
* MQTT
* MariaDB
* MySQL
* Office 365 Calendar
* Office 365 Contacts
* Office 365 Mail
* PagerDuty
* Paypal
* PostgreSQL
* RSS
* SFTP
* Shopify
* Stripe
* SurveyMonkey
* Travis CI
* TripIt
