![image of NASA logo](https://raw.githubusercontent.com/nasa/instructions/master/assets/NASA_logo.svg)

# INSTRUCTIONS FILE FOR NASA's PUBLIC GITHUB ORGANIZATION

## Table of Contents
- [Purpose](#purpose)
- [Instructions for Who Can Be a Member](#instructions-for-who-can-be-a-member)
- [Instructions for Once You Are a Member](#instructions-for-once-you-are-a-member)
- [Use of Large File Storage and GitHub Actions](#use-of-large-file-storage-and-github-actions)
- [GitHubPages and Websites](#githubpages-and-websites)
- [Enabling Discussions and Other Beta Features](#enabling-discussions-and-other-beta-features)
- [Most Common Requests](#most-common-requests)
- [Related Sites](#related-sites)
- [Questions](#questions)


## Purpose
This GitHub organization is intended to publicly host NASA code that has been SRA-approved for open source. You can review the SRA (software release authority) process for getting open-source approval on [https://code.nasa.gov/#/guide](https://code.nasa.gov/#/guide).

## Instructions for Who Can Be a Member
Only NASA staff can be a member of the NASA org on github.com and release code in [github.com/nasa](https://github.com/nasa) org.

If you are a NASA civil servant or contractor and would like to be added to the Public NASA GitHub Org, you will need to submit the AGCY NASA Github Collaborator Form [NAMS request ](https://nams.nasa.gov) https://nams.nasa.gov. This requires you to be behind the NASA firewall. If you were a member several years ago and recently found you are no longer a member, please see this [note](https://github.com/nasa/nasa.github.io/issues/2).

Only members have rights to directly edit code in a [github.com/nasa](https://github.com/nasa) repository. Everyone else will need to submit a pull request. We highly encourage pull requests from the public!!! However, please note that not all repositories are actively maintained. If you look at NASA code repositories on the <a href="https://github.com/nasa">https://github.com/nasa</a> front page, there is a little sparkline (small inline chart) showing activity over time. Projects with lots of activity are more likely to quickly accept a pull request. Members of the public can not attain and do not need collaborator status. <i>You don't need any special status to submit pull requests or add issues.</i>

For information on how to become a member of the NASA Org (you need to be a NASA civil servant or contractor with access to systems inside the NASA firewall), please see the instructions on [code.nasa.gov/#/guide](https://code.nasa.gov/#/guide).

### Instructions for Once You Are a Member
<i>Please read these instructions in full as using github.com/nasa has some differences with how you might be familar using github.com on personal projects.</i>

To ensure mandatory policies are followed, NASA org members are not given the full admin rights you might be used to on your personal github.com accounts. However, by using teams, team owners, collaborators, and outside collaborators roles we can make the experience pretty quick and easy.

#### Org Owners
We currently have six active owners in the org:

Drake Gordon : github username = drakegordon1

Darith Yim : github username = dsyim

Jeffery Rubio : github username = jjrubio2

Daniel Rendon : github username = dcrendon

Tessa Brazda : github username = tmbrazda


<!--
Miles Crabbe : github username = MilesCrabbe

Elizabeth Wainwright : github username = elizabeth-wainwright-->

A general purpose contact email is <a href="mailto:hq-open-innovation@mail.nasa.gov">hq-open-innovation@mail.nasa.gov</a>, please mention the specific nature of your question as this email is also used on data.nasa.gov & api.nasa.gov. 

<b>Only org owners have the ability to create new repositories, bring new users in as members of the NASA github org, and make changes to settings of repositories</b>. If there is something a member of the nasa org can not do that this arragement prevents, please reach out.

#### Repos
We do not give out admin rights on any NASA Github repos for reasons stated above. If you want a new repo created or want to edit settings on an existing repo that require admin access, please contact one of our org owners. Without admin rights on a repository, you'll still be able to make any code changes yourself as long as you're a collaborator on that repository or a member of a team whose participants are collaborators by default.

##### Required Information When Requesting New Repository
If you need for a new repository (and it has gotten SRA approval) please either submit a modification to your NAMs request with the following information:

- **Name of the repository**
- About Tab Information: These will appear on the repo's home page in the "about" section. They are extractable as metadata and assist in discoverability.
  - **Topic tags** that describe the repository. 
  - **A 350 character or less description** of the repository. 
  - **Website Link** : If you intend to start up a github pages site for documentation or have a link that goes elsewhere with that information, supply it for the about section as well.
- **SRA number**
- **Team name** for managing the repository
- **Usernames of people for that team** if it doesn't already exist. Usernames must be from the list of existing NASA org members.
 
[PLEASE READ THESE INSTRUCTIONS FOR A LONGER DESCRIPTION OF BEST PRACTICES FOR REPOSITORY NAMES AND ABOUT SECTION INFORMATION](https://github.com/nasa/nasa.github.io/blob/master/docs/about_section_instructions.md)
 
If you are joining for the first time and need a repository created, you can also include the same information in your NAMs request for access inside the more information box.

You can learn more about the software release authority process on the [guide page](https://code.nasa.gov/#/guide) of code.nasa.gov.

#### Teams
Teams are effective ways of managing repository access privileges for an entire group of users. Only org owners can create and remove teams, but we now allow users to be team maintainers. Team maintainers have permissions to add and remove users to their teams from the population of people who are already NASA org members.

Note: Team maintainers are technically able to add a user who was once in the NASA org back onto their team (thus reinstating the user in the org). However, we do not allow this and will remove maintainers who are found in violation. If you need a past member to be reinstated in the org, contact an org owner and request to be added as an outside collaborator.

#### Collaborators
Github also has a role called "collaborator". This is someone who doesn't have repository ownership or admin rights but can push edits to code directly without doing a pull request.

If you would like to add a NASA staff member who is a member of the NASA org as a collaborator on a single repository, we still suggest you contact the NASA org owners mentioned above about setting up a TEAM for that single repository instead of adding people one by one. Teams result in less requestes (and therefore waiting) on NASA org owners for actions. We are sorry you don't have normal full ownership rights. It is because everyone with write access needs to be approved NASA user. If you had normal repository owner right, you could add any github user.

#### Outside Collaborators
Only on a rare case-by-case basis we will allow non-NASA users to be added to the org as Outside Collaborators. You can collaborate without this status via forks, branches, and pull-requests. If you fork a repository, you can make changes and then submit back a pull-request. A repository maintainer can then approve those changes. You do not need formal outside-collaborator status for this!

Please reach out to us if you have any questions.

### Use of Large File Storage and GitHub Actions
<a href="https://git-lfs.github.com/">Large File Storage</a> (LFS) and <a href="https://github.com/features/actions">GitHub Actions</a> are two services for GitHub repositories that can be enabled and may result in extra costs that the NASA org on github.com has to pay. Currently, the policy is to enable these features on a per repository basis as requested for limited use. This level of use over a small number of repositories hasn't resulted in charges above our very limited budget. If you would like to use either of these services extensively, please each out to the contact email. 

#### Billing Plan & Impact on Features
A very small number of GitHub features depend on what billing plan your organization uses. This varies over time, so please refer to GitHub documentation for this information.

Github.com/nasa is on a "legacy" billing plan until October 1st, 2022 at which time it switches to a “free” plan. Free plan has costs for GitHubActions and Package storage, so there may be a future point in time when those features would be curtailed for the heaviest users. Any change would be announced. GitHub.com/nasa is not on an Enterprise plan as it would trigger internal policies that would require payment at the individual level resulting in less open source code released.

### GitHubPages and Websites
You must contact an administrator to help you turn on GitHub pages. Please let them know the branch being used and whether the starting `index.html` file is under the top level of the repository or the `docs` folder. 

<i>PLEASE NOTE: GitHub pages can be used for documentation of NASA open source code. You can not use GitHub pages to stand up a NASA website as it will not be under the nasa.gov domain.</i> Please contact the github.com/nasa administrators listed elsewhere on this page if you have any questions about the interpretation of this policy.

##### Why is this now just a markdown file instead of a website?
These instructions were previously made into a website. The fact that it looked like a website, not documentation, and lacked a nasa.gov domain caused it to attract negative attention. Hence, it was reverted back into a markdown file document format. Apologies to those who submitted pull requests to improve the old site.

### Enabling Discussions and Other Beta Features
There are some repository configurations, especially for beta features of GitHub, that are not enabled by default. These often need to be enabled in the settings menu, which is not always available for users who only have write access. If there is a feature you see elsewhere in GitHub.com that you don't see enabled on your repository, please reach out to the administrator email. We will see if that is a feature we can enable for you.

One example, would be "discussions", which is a place to have discussions that don't fall squarely within "issues" or "pull requests". Reach out to the contact email to get "discussions" enabled on a NASA repository that you can write access to. Include your name, email, GitHub username, and repository name.

### Most Common Requests
<hr>
Need: <i>If you need to be added to the NASA org on github.com/</i>

- Create a personal github account and then request to be added as a Github Collaborator via a new or modified <a href="https://idmax.nasa.gov/nams/asset/227756">NAMs request</a>. Please include your github id in the request. Please note that you will not be able to get to that link if you are not inside the NASA firewall.
<hr>

--->THIS IS THE MOST COMMON REQUEST<---

Need: <i>If you need to add a new open-sourced repository to github.com/nasa that has already been approved via the software release authority process.</i>

- Make or modify a request to start a new repository in github.com/nasa via the <a href="https://idmax.nasa.gov/nams/asset/227756">NAMs request</a>. Please give it a useful name and good documentation! We'll create a blank repository for you to put the code into. Please note that you will not be able to get to that link if you are not inside the NASA firewall. In your NAMs request, please include all the required metadata describing the respository listed in the "REPO" section above. If this is the first repository you're open sourcing, you might also want to read through the longer description of how to supply the metadata <a href="https://github.com/nasa/instructions/blob/master/docs/about_section_instructions.md">here</a>.
<hr>
Need: <i>If you need to create a new team for managing who has access to make changes on a particular repository or group of repositories.</i>

- Modify your <a href="https://idmax.nasa.gov/nams/asset/227756">NAMs request</a> to request the team creation or email the two owners above. Give team name and which repositories team members should be given access to. Please note that you will not be able to get to that link if you are not inside the NASA firewall.
<hr>
Need: <i>If you need to add a new member to an already established team.</i>

- Send an email to the Team owner, modify your NAMs request, or email the Github Owners in that order of preference. 
<hr>
Need: <i>I accidentally committed something that needs to be deleted from all git history. How do I do that?</i>

- Check out the instructions here: https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository#using-the-bfg 
<hr>

Need: <i>Someone submitted a spam pull request to a NASA repository. That user needs blocked from all NASA repositories. </i>

- Send an email to an NASA org admin using the standard contact email listed on this page. Supply a link to the issue or pull request with the spam and the username of who is to be blocked. 

<hr>

## Related Sites
### Organizationally Related Sites
In addition to github.com/nasa, NASA OCIO's Transformation and Data Division Open-Innovation staff also run:
- <a href="https://code.nasa.gov">code.nasa.gov</a> [Catalog containing metadata describing open source NASA code that is on github.com/nasa as well as other locations.]
- <a href="https://data.nasa.gov">data.nasa.gov</a> [Catalog that holds metadata that describes open datasets from many different NASA data archives.]
- <a href="https://api.nasa.gov">api.nasa.gov</a> [Listing of beginner friendly NASA APIs.]

### Open Source Related Pages on NASA.GOV
The page https://www.nasa.gov/open/open-source-development.html has some high level history and information regarding open source at NASA.

### Information on Internal Code Platforms
<a href="https://wiki.jsc.nasa.gov/fod/index.php/Knowledge_Any_Developer_New_to_NASA_Will_Need_to_Know">Internal information</a> on internal code platforms

### Why is NASA's Open Source Code in multiple locations?
The reason for NASA open source code existing in different places boils down to different requirements, both requirements of those writing the code and requirements from above.

Other NASA orgs on github.com or gitlab.com or bitbucket
Although NASA staff are highly encouraged to release open source software on github.com/nasa as that is where most people look so it ensures higher potential reuse, they are not absolutely required to use that org account. A common reason code may exist under other orgs is that the software is jointly maintained by non-NASA persons or the code was developed by non-NASA persons through a NASA grant.

To encourage disoverability, please use the #NASA topic tag on any GitHub or GitLab repositories not under github.com/nasa. Doing so helps create views of NASA open source code beyond what is under github.com/nasa. 

For example, <a href="https://justingosses.github.io/nasa-repos-visual-explorer/explore/">this webpage creates visualizations of trends and connections between NASA repositories</a> across many org accounts and not just github.com/nasa. 

### Discovering useful NASA Open-Source Code via metadata catalogs
There are several hundred NASA open-source code repositories and as previously noted, not everything is on github.com/nasa. To improve your chance of finding something useful to you, we suggest you use code.nasa.gov and software.nasa.gov. These sites host metadata descriptions for nearly all of the officially open-sourced code.

#### Code.nasa.gov
Code.nasa.gov feeds into https://code.gov, which holds open source code from across all federal government agencies. It is mandated by Congress and only holds standardized metadata about the code.

Code.nasa.gov only shows open-source software. For government-source and patented software, see software.nasa.gov

Please make sure any repos added to github.com/nasa are also tracked in code.nasa.gov!

Code.nasa.gov uses both human and A.I. generated tags to help users find NASA open source that is useful for their goals.

![image of sreenshot of code.nasa.gov showing details for Open MCT project](https://raw.githubusercontent.com/nasa/instructions/master/assets/code_demo.png)


Screenshot of NASA's project OPEN MCT

#### Software.nasa.gov

Software.nasa.gov is part of the larger https://technology.nasa.gov/ that also covers patents and spinoffs. The NASA's Technology Transfer Program ensures that innovations developed for exploration and discovery are broadly available to the public, maximizing the benefit to the Nation. Whether you're looking to start a new company, enhance an existing product, or create a new product line, you can gain a competitive edge in the marketplace by putting NASA technology to work for you.

The information on software.nasa.gov is presented in a way that leverages NASA's technology taxonomy, so if you want to see an aggregate view of NASA software categories, it is a good place to visit.

It also includes some older software products that are only available as downloadable zip files as well as software that must be requested individually as they are only open to US persons or are tied to a patent.

![image of sreenshot of software.nasa.gov showing the categories of NASA software](https://raw.githubusercontent.com/nasa/instructions/master/assets/software.png)
Screenshot of NASA's software categories


## Questions
If you have questions, you may leave an issue on this repository or contact us via <a href="mailto:hq-open-innovation@mail.nasa.gov">hq-open-innovation@mail.nasa.gov</a>. We will use those questions & answers to eventually make a FAQ section on this page.

