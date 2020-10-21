# GitHub for Brown

GitHub Education is an Enterprise level GitHub service for managing source code and teams of collaborators on source code. 

## Documentation

This repo is to provide new users with some documentation to help them get familiar with the Brown University GitHub organization. It may be updated from time to time to reflect and changes. It is a public repo, and users may suggest changes to it just like any other GitHub repo.

## GitHub Account

GitHub's accounts are global, and unique to GitHub. Your **Brown ShortID** may **not** be available on GitHub, and this is **OK**; You will add your GitHub account to Brown-related 'organizations', 'teams', and 'projects' in later steps. Your GitHub account can be used for your own projects or with other organizations and projects across the entire site, it belongs to **you**. Most developers prefer to maintain a single GitHub account and associate it with organizations and projects, as opposed to creating one for each organization. The GitHub service will **not** give Brown any special access to other projects on GitHub that you might create or participate in.

If you **don't** already have a GitHub account, you can create one using using this link: [GitHub Join](https://github.com/join).

Please enable two-factor authentication for your account using an authenticator app or SMS messaging. This will help protect your entire GitHub account from unauthorized access.

## Membership to the 'BrownUniversity' organization within GitHub


Once you have an account, you can be invited to join the BrownUniversity Org via CAP (Computing Accounts and Passwords) requests. This will ensure only authorized users will be given access.

Other organizations (CIS, CCV, Libraries, etc.) may have other methods to join.

## Accessing 2FA protected resources within GitHub from the command line (or other tools that)

GitHub provides a [desktop client](https://desktop.github.com/) for macOS and Windows, but most developers prefer to use the command line or other clients. Many IDEs and [developer-oriented text editors](https://atom.io/) can make use of GitHub integration. To integrate your desktop experience with GitHub outside of the official apps, there are additional steps required to create a 'key' that you can authorize connections with.

Please follow the steps in [this document](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh) to generate a private key (this must NOT be shared or stored in a location where it is at risk of being compromised) and authorize it for use with GitHub. This creates a trust relationship between applications within your desktop environment and GitHub.

You can use the same SSH key pair for other services besides GitHub, but that is out-of-scope for this document. To read more on the subject, please start [here](https://www.ssh.com/ssh/public-key-authentication).

## Learn Git and GitHub

If you are not already familiar with git and GitHub, Brown has access to several excellent online courses at [LinkedIn Learning](https://www.linkedin.com/learning/).

Here are three helpful resources to get you started:

* [Learning GitHub](https://www.linkedin.com/learning/learning-github/version-control-and-collaboration-with-github) - 2hrs 11min: Includes bare basics of using git.  
* [GitHub Essential Training](https://www.linkedin.com/learning/github-essential-training) - 2hrs 48min: Covers CI concepts and more advanced git usage.
* [Git Cheat Sheet from GitLab](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)

## Understanding Visibility

GitHub is built on an Open Source philosophy where repositories are meant to be **open to public view** unless specified otherwise. This is important to understand when using GitHub.com's services. Brown *strongly* recommends using private repositories until you and your team are comfortable enough with software development practices that you will not be exposing any sensitive information. Sensitive information in this context could include (but not limited to):

- Passwords
- Encryption keys
- Access keys
- Service account credentials
- Proprietary software (not open source)
- User data

### Types of repositories

* **Public** - Visible to the world to view, even without Brown credentials
* **Internal** - Visible to anyone within the Brown Org and GitHub access (needs both)
* **Private** - Hidden to all unless explicitly allowed (teams and individuals)

Visibility does not mean writable. Write access to a repo is managed in each repo's settings by the owner, usually the person who created it. That person would be able to invite users or teams and determine what level of access they would have.

### A helpful hint about naming repositories

The repositories within an organization are not hierachically stored. In order to keep projects organized, we have found it useful to prefix repository names by the functional team who is the primary owner, followed by a hyphen and the project name. An example project might be named 'ISG-ThingWeDo'.

## License

GitHub is built on providing tools for Open Source projects. To this end it provides Open Source compatible licenses to new repositories. As a Brown employee or faculty member these may not be appropriate for the code you are developing. 

### Existing code

If you are modifying an **existing** code that is already under an Open Source license, you should abide by the terms of that license. Normally if that code is used only internally to your team or department then you will not have to worry about it's distribution clauses. If you are sharing the code with a larger audience, please read and understand the conditions of the license the code is under.

### New code

If you are **creating** new code you should leave the license as None for now, until Brown provides an appropriate license. 
