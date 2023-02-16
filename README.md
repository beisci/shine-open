# About
This repo stores documents related to the **S**leep **H**ealth **I**n Peri**n**atal Car**e** (SHINE) Project, funded by National Health and Medical Research Council (NHMRC) Clinical Trials & Cohort Studies Grant. SHINE is a collaborative project amongst [Monash University](https://www.monash.edu/) [Sleep and Mental Health Laboratory](https://www.monash.edu/turner-institute/bei-bei-lab) (Lead), [Stanford University](https://med.stanford.edu/insomnia.html) (USA), [Monash Health](https://monashwomens.org), and the [Royal Women's Hospital](https://thewomens.org.au). It studies changes in sleep and wellbeing across pregnancy and the postpartum years, and evaluates interventions for improving sleep during this important period for Australian families.

To make the research process transparent, documents in working progress are made publicly available via Creative Commons Attribution-ShareAlike 4.0 International [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) . Briefly, it is free to share or adapt content in this repo as long as you credit the source and make the resulting content open access.

Questions or comment: bei.bei@monash.edu

# Read-me-first for staff
## Checks and training
- `Required` [Working with Children Check](https://www.workingwithchildren.vic.gov.au)
- `Required` Good Clinical Practice training: [Monash Partners](https://monashpartners.org.au/education-training-and-events/good-clinical-practice-in-clinical-trials/), [SBM Online](https://www.sbm.org/training/good-clinical-practice-for-social-and-behavioral-research-elearning-course)
- [Consumer and Community Involvement training](https://monashpartners.org.au/education-training-and-events/cci/)
- [safeTALK](https://www.monash.edu/students/support/health/mental-health/programs/safetalk-suicide-awareness) and [ASSIST](https://www.livingworks.com.au/programs/asist/)
- [Guidelines on creating accessible content](https://www.vic.gov.au/make-content-accessible) for individuals with auditory, cognitive, physical, speech, and visual impairments.
- TBC

## Systems to access
- [Github](https://github.com/), we require all staff to enable [multi-factor authentification](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication). Please also request a free `Pro` account via Github Education [students](https://education.github.com/students) or [teachers](https://education.github.com/teachers) programs.
- [Microsoft Teams](https://www.microsoft.com/en-au/microsoft-teams/).
- [REDCap](https://redcap.helix.monash.edu), if new user, admin to [request access](https://servicedeskonline-myit.onbmc.com/dwp/app/#/srm/profile/SRGAA5V0G7HC6AOIWNGLOIBI7PHY36/srm).
- S Drive: [setup information for users](https://www.monash.edu/esolutions/data-storage/how-to-map-s-drive); admin's [user management portal](https://groupadmin.monash.edu/) (VPN required).
- [Zoom phone](https://www.monash.edu/esolutions/phones/zoom-phone).
- Ethics ([Monash Health](https://au.forms.ethicalreviewmanager.com/Account/Login)).
- Sleep and Circadian Rhythm mailing list, seminar program.
- Building access.

## Git
- [Learn basics](https://github.com/skills/introduction-to-github) from [Github Skills](https://github.com/skills). 
- [Student resources from GitKraken](https://www.gitkraken.com/resources/student-resources) have a [nice collection of videos](https://www.gitkraken.com/learn/git/tutorials) explaining git concepts, and [how to use GitKraken with GitHub](https://www.gitkraken.com/integrations/github).
- For a point and click git client, check out [Github Desktop](https://help.github.com/en/desktop/getting-started-with-github-desktop) or [GitKraken](https://www.gitkraken.com)

## Markdown
- [Learn Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
- Use a good plain text editor that supports syntax highlighting (e.g., [Obsidian](https://obsidian.md)). 

## Files, formats, and naming conventions
- **IMPORTANT**: This repo is open to the public. Do not commit personally identifiable information to this repo.
- Use plain text (e.g., `*.md`, `*.txt`, `*.R`, `*.Rmd`) as much as possible to allow detailed version control. Only use other formats (e.g., `*.docx`, `*.pdf`) when necessary.
- Stick to strict folder/file naming convention. Problems with folder/file naming could lead to data loss.  Read [this link here](https://developers.google.com/style/filenames). Do not use special characters, period, or spaces. You can use `-` (dash) or `_` (underscore) instead. Try to use **lowercase** only, especially folders.
- R object naming conventions are different from folder and file naming. See [this R code convention](https://google.github.io/styleguide/Rguide.xml). In naming R objects, such as a data.table or variable, period `.` (not `_`) as a separator is the convention. Please also check out the [File Names](https://google.github.io/styleguide/Rguide.xml#filenames) and [Identifies](https://google.github.io/styleguide/Rguide.xml#identifiers) sections of the link above.

## How to work with a repo?
- Before you start, please learn basic git, and [git workflow](https://guides.github.com/introduction/flow/).
- The `main` branch is usually a stable version. 
- When you work on a specific issue, make a branch from the `main`, and send pull request to merge your commits into the `main`.
- Branches can come and go. You can create as many branches as you need for working on specific sections, and once the changes you made are merged back to the `main`, you can delete them. Make a new branch when you work on the next issue.
- Please `squash` your commits into a single one before sending pull request. This helps the reviewer view only one set of differences.
- **IMPORTANT**: each time **BEFORE** you start working on your branch, make sure you fetch and merge any changes that occurred.

## What is `.gitignore`?
- It is a (usually) hidden file that can be opened using any text editor. 
- It is helpful to turn on "always show hidden files" to see all files being committed to a repo. Google how to do this and turn this on.
- `.gitignore` contains files and directories that are **ignored** by git. This is very helpful for items like private notes, messy temporary hidden files, or sensitive data. Adding these items to the `.gitignore` file will tell git to automatically skip them, so they will not be committed to Github server online, or to collaborators.
- A frequent use case is `/data` line being part of `.gitignore`. This way, we can store data locally in our repo without committing them to be shared with others.
