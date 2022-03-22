# About
This repo stores documents related to the **S**leep **H**ealth **I**n Peri**n**atal Car**e** (SHINE) Project, funded by National Health and Medical Research Council (NHMRC), and based at the [Sleep and Mental Health Laboratory](https://www.monash.edu/turner-institute/bei-bei-lab) at Monash University, Australia. 

To make the research process transparent, documents in working progress are made publicly available via Creative Commons Attribution-ShareAlike 4.0 International [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) .

TBC

# Read-me-first for staff
## Checks and training
- `Required` [Working with Children Check](https://www.workingwithchildren.vic.gov.au)
- `Required` [Good Clinical Practice training](https://www.sbm.org/training/good-clinical-practice-for-social-and-behavioral-research-elearning-course)
- [Consumer and Community Involvement training](https://monashpartners.org.au/education-training-and-events/cci/)
- [Guidelines on creating accessible content](https://www.vic.gov.au/make-content-accessible) for individuals with auditory, cognitive, physical, speech, and visual impairments
- TBC

## Git
- [Learn basics](https://lab.github.com/githubtraining/introduction-to-github) from [Github Learning Lab](https://lab.github.com/). 
- [Student resources from GitKraken](https://www.gitkraken.com/resources/student-resources) have a [nice collection of videos](https://www.gitkraken.com/learn/git/tutorials) explaining git concepts, and [how to use GitKraken with GitHub](https://www.gitkraken.com/integrations/github).
- For a point and click git client, check out [Github Desktop](https://help.github.com/en/desktop/getting-started-with-github-desktop) or [GitKraken](https://www.gitkraken.com)

## Markdown
- [Learn Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
- Use a good plain text editor that supports syntax highlighting. Suggestions: [RStudio](https://www.rstudio.com), [Obsidian](https://obsidian.md) . 

## Files, formats, and naming conventions
- This repo is open to the public. Do not commit personally identifiable information to this repo.
- Use plain text (e.g., `*.md`, `*.txt`, `*.R`, `*.Rmd`) as much as possible to allow detailed version control. Only use other formats (e.g., `*.docx`, `*.pdf`) when necessary.
- Stick to strict folder/file naming convention. Problems with folder/file naming could lead to data loss. Thoroughly read [this link here](https://library.stanford.edu/research/data-management-services/data-best-practices/best-practices-file-naming). Do not use special characters, period, or spaces. You can use `-` (dash) or `_` (underscore) instead.
- R object naming conventions are different from folder and file naming. See [this R code convention](https://google.github.io/styleguide/Rguide.xml). In naming R objects, such as a data.table or variable, period `.` (not `_`) as a separator is the convention. Please also check out the [File Names](https://google.github.io/styleguide/Rguide.xml#filenames) and [Identifies](https://google.github.io/styleguide/Rguide.xml#identifiers) sections of the link above.

## How to work with a repo?
- Before you start, please learn basic git, and [git workflow](https://guides.github.com/introduction/flow/).
- The `main` branch is the final version. 
- When you work on a specific issue, make a branch from the `main`, and send pull request to merge your commits into the `main`.
- Branches can come and go. You can create as many branches as you need for working on specific sections, and once the changes you made are merged back to the `main`, you can delete them. Make a new branch when you work on the next issue.
- **IMPORTANT**: please `squash` your commits into a single one before sending pull request. This helps the reviewer view only one set of differences.
- **VERY IMPORTANT**: each time **BEFORE** you start working on your branch, make sure you fetch and merge any changes that occurred on the `main` to your working branch.
