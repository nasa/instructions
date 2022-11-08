# BEST PRACTICES FOR REPOSITORY NAMES AND ABOUT SECTION INFORMATION ON GITHUB.COM/NASA
### Context: Where These Instructions Apply

There are instructions for the public-facing GitHub! Specifically the NASA org at https://github.com/nasa

These instructions are not for any internal GitHub or GitLab instance. 

More general instructions for Open Sourcing Code are on <a href="https://code.nasa.gov/#/guide">https://code.nasa.gov/#/guide</a>

More general Instructions for Github.com/nasa are on <a href="https://github.com/nasa/instructions/blob/master/docs/INSTRUCTIONS.md">https://github.com/nasa/instructions/blob/master/docs/INSTRUCTIONS.md</a>
**/

### Certain Information Can Only Populated By Admins on GitHub.com/nasa

To comply with requests from security and legal that all repositories accessible to the public on github.com/nasa have an SRA authorization number, repositories can only be created by administrators of github.com/nasa. This means only administrators can "own" repositories using GitHub definitions. 

In addition to limiting who can "create" repositories, ownership also limits who can populate:
- repository name
- topic tags
- website link 
- description

#### This means all those fields need to be submitted in your NAMs request, or in an email to an admin, when requesting a repository!!!

<i>More information on them is below.</i>

## Repository Names
It is difficult to make absolute rules when discussing code repositories. What follows are more guidelines.

#### Changing a repository name is the easiest right when you first releasing it as open source! 
Changing a repository's name during use can cause configuration & link issues. Changing a name of a code repository as it is being released for open source is probably the easiest time to change it after creation. 

Open-sourcing is also a point in time when the audience for the code is changing. The name that made sense and was functional for your small internal team may not be a name with the same understanding and value to the general public.

#### Goals of a code repository name
Ideally, a code repository name would convey meaning to the potential future end user about its purpose, be easily distinguishable from other related code repositories, and be memorable. 

In the worst case, a name can cause confusion about what it does, be hard distinguish from related code, and be impossible to remember the name. 

A long name is actually not that much of a negative when it comes to code repositories as developers typically use tab-complete to finish the name anyways.

##### Related Repositories
For a code project that involves multiple different repositories, it is good to name them such that the shared concept is at the front. This helps for both search and discovery. 

This might look like:
``` 
projectname-coderepositoryname
```
or sometimes there may be a need for a third breakdown to convey the difference between an application build for one operating system or computer language vs. another. For example:
``` 
venusweather-api-python
```
vs.
``` 
venusweather-api-go
```
##### Syntax 
There isn't a very strict standard in terms of syntax of repository names but in general making them easier to read is better. 

This leads to the following practices:
- <b>dashes > underscores </b>
- <b>dashes-dashes > CamelCase </b>
- <b>lowercase > UPPERCASE</b>

#### Acronyms are bad names, usually
There is a tendancy in government to name everything that needs a name with an acronym. Acronyms save time for those that know their meaning, but they convey somewhere between very little and zero information to the people who don't know their meaning. As such, if there is a choice between using three words separated by dashes and an acronym, the three words separated by dashes is nearly always the better name. 

You can always explain in the README that internally, the project is referred to as acronym ___. 


## Topic tags improve code discoverability
Topic tags help the public discover your code in a variety of ways. 
- The public might search for the topic tag across all of GitHub. 
- The public might be on a related code repository on github.com/nasa that uses the same tag. They an click on the tag and see any code repositories under the NASA org with the same tag. 
- Tags also helps NASA individuals understand what types of NASA code has been open-sourced and is available for reuse.

Good examples of topic tags are domains, fields of study, frameworks used, public & internal project names, NASA org names, and especially single words that describe possible software use cases in general terms.

For examples of good tags, you can look at the tags on code.nasa.gov https://code.nasa.gov/ . Below each code project description is a list of both human populated tags and machine-learning generated tags. When you submit a new project to be cataloged on code.nasa.gov, <a href="https://code.nasa.gov/#/guide">which is mandatory for all open-source release</a>, it triggers a pipeline that generates the machine-learning generated tags.

### Required Tags For Any Machine Learning Related Code
A.I. Related Datasets Need New OMB Mandated Tags

OMB has issued guidance <a href="https://code.gov/assets/data/ai_inventory-guidance.pdf">"Guidance for Improving Discoverability of Agency Datasets for AI R&D"</a>. If your dataset in any way relates to A.I., please read the linked instructions and add the appropriate tags!
```
Agencies shall include the keyword of 
“usg-artificial-intelligence” 
for all datasets determined to support AI R&D. Datasets that specifically serve as training data for ML applications should additionally include a keyword of 
“usg-ai-training-data,”
“usg-ai-testing-data,”
```
You can find all the NASA repositories that are related to A.I. and use this tag <a href="https://github.com/orgs/nasa/repositories?language=&q=usg-artificial-intelligence&sort=&type=">here</a>. This topic tag is relatively new, so hopefully this list will expand in size over time.

## Website Link
If you want to use GitHub pages to display documentation, please request that the link to the github pages be set up and supplied in the "website" field. Alternatively, if there is no documentation website but the code was created for a NASA mission or project that does have a website, please consider adding it in that field. 

## Description
Many NASA code repositories on github.com/nasa lack a description or have a description that still leaves a members of the public unsure what exactly the code does. Please write the description with someone not familiar with the code, your project, or NASA in mind. 

This is how much text you have available, which is approximately 350 characters with spaces. 
```
Information about the NASA Github organization is on nasa.github.io/ Information about the NASA Github organization is on nasa.github.io/ Information about the NASA Github organization is on nasa.github.io/ Information about the NASA Github organization is on nasa.github.io/ Information about the NASA Github organization is on nasa.github.io/ In
```

