[//]: # (REPLACE_ME: Should replace with domain specific introduction)
### Intro
This implementation guide is a base template and starter point for creating new IG within TEHIK.

It provides some conventions on how to structure IG, build it and publish generated website.

[//]: # (REMOVE_ME: Needed only for this specific IG starter)
### How to start

1. Copy project and rename project.
1. Replace this IG specific values: look for comments marked **REPLACE_ME:**
1. Remove unnecessary pages, fsh files etc., look for comments marked **REMOVE_ME:**
1. Add domain specific profiles, markdown pages etc.
1. Change alias.fsh and include your domain specific values, please follow the naming pattern.

[//]: # (REMOVE_ME: Needed only for this specific IG starter)
### Structure
**input/fsh/*.fsh** files are logically grouped into folders, which are used to generate the website structure. 
Please follow the same structure when adding new files.

**input/pagecontent** folder contains markdown files which are used to generate the website pages.
Menu and pages are defined in **sushi-config.yaml** file.

[//]: # (REMOVE_ME: Needed only for this specific IG starter)
### Build and deploy

Building and deploying information is located in GitHub project README file. 
