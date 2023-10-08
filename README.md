<!-- Begin README -->

> [!WARNING] 
> THIS REPO IS STILL A WORK IN PROGRESS - CHECK BACK SOON FOR MORE UPDATES

[![App Logo](./docs/images/banner_large.png)](https://github.com/scottgriv/PRG-Personal-Repository-Guidelines)

<p align="center">
    <a href="https://github.com/scottgriv/PRG-Personal-Repository-Guidelines">
        <img src="https://img.shields.io/badge/PRG-1.0.0-6236FF?style=for-the-badge&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iMjYuMDAwMDAwcHQiIGhlaWdodD0iMzQuMDAwMDAwcHQiIHZpZXdCb3g9IjAgMCAyNi4wMDAwMDAgMzQuMDAwMDAwIgogcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCI+Cgo8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCwzNC4wMDAwMDApIHNjYWxlKDAuMTAwMDAwLC0wLjEwMDAwMCkiCmZpbGw9IiNGRkZGRkYiIHN0cm9rZT0ibm9uZSI+CjxwYXRoIGQ9Ik0xMiAzMjggYy04IC04IC0xMiAtNTEgLTEyIC0xMzUgMCAtMTA5IDIgLTEyNSAxOSAtMTQwIDQyIC0zOCA0OAotNDIgNTkgLTMxIDcgNyAxNyA2IDMxIC0xIDEzIC03IDIxIC04IDIxIC0yIDAgNiAyOCAxMSA2MyAxMyBsNjIgMyAwIDE1MCAwCjE1MCAtMTE1IDMgYy04MSAyIC0xMTkgLTEgLTEyOCAtMTB6IG0xMDIgLTc0IGMtNiAtMzMgLTUgLTM2IDE3IC0zMiAxOCAyIDIzCjggMjEgMjUgLTMgMjQgMTUgNDAgMzAgMjUgMTQgLTE0IC0xNyAtNTkgLTQ4IC02NiAtMjAgLTUgLTIzIC0xMSAtMTggLTMyIDYKLTIxIDMgLTI1IC0xMSAtMjIgLTE2IDIgLTE4IDEzIC0xOCA2NiAxIDc3IDAgNzIgMTggNzIgMTMgMCAxNSAtNyA5IC0zNnoKbTExNiAtMTY5IGMwIC0yMyAtMyAtMjUgLTQ5IC0yNSAtNDAgMCAtNTAgMyAtNTQgMjAgLTMgMTQgLTE0IDIwIC0zMiAyMCAtMTgKMCAtMjkgLTYgLTMyIC0yMCAtNyAtMjUgLTIzIC0yNiAtMjMgLTIgMCAyOSA4IDMyIDEwMiAzMiA4NyAwIDg4IDAgODggLTI1eiIvPgo8L2c+Cjwvc3ZnPgo=" alt="PRG Badge" />
    </a>
    <a href="https://github.github.com/gfm/">
        <img src="https://img.shields.io/badge/GFMarkdown-0.29-093FA1?style=for-the-badge&logo=markdown" alt="Markdown Badge" />
    </a>
        <a href="https://github.com/scottgriv/PRG-Personal-Repository-Guidelines">
        <img src="https://img.shields.io/badge/PRG-Gold Project-FFD700?style=for-the-badge&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iMjYuMDAwMDAwcHQiIGhlaWdodD0iMzQuMDAwMDAwcHQiIHZpZXdCb3g9IjAgMCAyNi4wMDAwMDAgMzQuMDAwMDAwIgogcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCI+Cgo8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCwzNC4wMDAwMDApIHNjYWxlKDAuMTAwMDAwLC0wLjEwMDAwMCkiCmZpbGw9IiNGRkQ3MDAiIHN0cm9rZT0ibm9uZSI+CjxwYXRoIGQ9Ik0xMiAzMjggYy04IC04IC0xMiAtNTEgLTEyIC0xMzUgMCAtMTA5IDIgLTEyNSAxOSAtMTQwIDQyIC0zOCA0OAotNDIgNTkgLTMxIDcgNyAxNyA2IDMxIC0xIDEzIC03IDIxIC04IDIxIC0yIDAgNiAyOCAxMSA2MyAxMyBsNjIgMyAwIDE1MCAwCjE1MCAtMTE1IDMgYy04MSAyIC0xMTkgLTEgLTEyOCAtMTB6IG0xMDIgLTc0IGMtNiAtMzMgLTUgLTM2IDE3IC0zMiAxOCAyIDIzCjggMjEgMjUgLTMgMjQgMTUgNDAgMzAgMjUgMTQgLTE0IC0xNyAtNTkgLTQ4IC02NiAtMjAgLTUgLTIzIC0xMSAtMTggLTMyIDYKLTIxIDMgLTI1IC0xMSAtMjIgLTE2IDIgLTE4IDEzIC0xOCA2NiAxIDc3IDAgNzIgMTggNzIgMTMgMCAxNSAtNyA5IC0zNnoKbTExNiAtMTY5IGMwIC0yMyAtMyAtMjUgLTQ5IC0yNSAtNDAgMCAtNTAgMyAtNTQgMjAgLTMgMTQgLTE0IDIwIC0zMiAyMCAtMTgKMCAtMjkgLTYgLTMyIC0yMCAtNyAtMjUgLTIzIC0yNiAtMjMgLTIgMCAyOSA4IDMyIDEwMiAzMiA4NyAwIDg4IDAgODggLTI1eiIvPgo8L2c+Cjwvc3ZnPgo=" alt="Gold PRG Badge" />
    </a>
    <br>
        <a href="https://github.com/scottgriv">
        <img src="https://img.shields.io/badge/github-follow-9031AC?style=for-the-badge&logo=github&color=9031AC" alt="GitHub Badge" />
    </a>
    <a href="mailto:scott.grivner@gmail.com">
        <img src="https://img.shields.io/badge/gmail-contact me-DC4233?style=for-the-badge&logo=gmail" alt="Email Badge" />
    </a>
    <a href="https://www.buymeacoffee.com/scottgriv">
        <img src="https://img.shields.io/badge/buy me a coffee-support me-FEDE1F?style=for-the-badge&logo=buymeacoffee&color=FEDE1F" alt="BuyMeACoffee Badge" />
    </a>
</p>

---

<h1 align="center">Personal Repository Guidelines (PRG)</h1>

**PRG** is a repository guideline system developed to:
- Categorize repositories and projects that I have created.
- Define guidelines for repository `README`'s and files.
- Define guidelines for a repository's overall structure. 

## Table of Contents
- [Background](#background)
- [Repository Tiers and Naming Conventions](#repository-tiers-and-naming-conventions)
    - [1. Gold Tier](#1-gold-tier)
    - [2. Silver Tier](#2-silver-tier)
    - [3. Bronze Tier](#3-bronze-tier)
- [Project Tier List (GitHub Actions)](#project-tier-list-github-actions)
    - [Pre-requisites](#pre-requisites)
    - [Setting up the Workflow](#setting-up-the-workflow)
- [Badge References](#badge-references)
    - [Profile README Badge](/guides/badge_references.md#profile-readme-badge)
    - [Gold Project Badge](/guides/badge_references.md#gold-project-badge)
    - [Silver Project Badge](/guides/badge_references.md#silver-project-badge)
    - [Bronze Project Badge](/guides/badge_references.md#bronze-project-badge)
    - [Purple Brand Badge](/guides/badge_references.md#purple-brand-badge)
    - [Black Brand Badge](/guides/badge_references.md#black-brand-badge)
    - [White Brand Badge](/guides/badge_references.md#white-brand-badge)
- [Repository Settings (All Tiers)](#repository-settings-all-tiers)
    - [Description (Required)](/guides/repository_settings#description-required)
    - [Website (Optional)](/guides/repository_settings#website-optional)
    - [Topics (Required)](/guides/repository_settings#topics-required)
    - [Misc. Settings (Optional)](/guides/repository_settings#misc-settings-optional)
- [README Guidelies (All Tiers)](#readme-guidelies-all-tiers)
    - [Banner](/guides/readme_guidelines#banner)
    - [Badges](/guides/readme_guidelines#badges)
    - [Description](/guides/readme_guidelines#description)
    - [Table of Contents](/guides/readme_guidelines#table-of-contents)
    - [Background](/guides/readme_guidelines#background)
    - [Definitions](/guides/readme_guidelines#definitions)
    - [Limitations](/guides/readme_guidelines#limitations)
    - [Features](/guides/readme_guidelines#features)
    - [What's Inside?](/guides/readme_guidelines#whats-inside)
    - [Dependencies](/guides/readme_guidelines#dependencies)
    - [Getting Started](/guides/readme_guidelines#getting-started)
    - [Configuration](/guides/readme_guidelines#configuration)
    - [Deployment](/guides/readme_guidelines#deployment)
    - [Closing](/guides/readme_guidelines#closing)
    - [Disclaimer](/guides/readme_guidelines#disclaimer)
    - [Resources](/guides/readme_guidelines#resources)
    - [What's Next?](/guides/readme_guidelines#whats-next)
    - [Project](/guides/readme_guidelines#project)
    - [Contributing](/guides/readme_guidelines#contributing)
    - [Forking](/guides/readme_guidelines#forking)
    - [Found a Bug?](/guides/readme_guidelines#found-a-bug)
    - [License](/guides/readme_guidelines#license)
    - [Credits](/guides/readme_guidelines#credits)
    - [Footer](/guides/readme_guidelines#footer)
- [Project Structure (All Tiers)](#project-structure-all-tiers)
    - [.gitignore File](/guides/project_structure#gitignore-file)
    - [.gitattributes File](/guides/project_structure#gitattributes-file)
    - [VERSION File](/guides/project_structure#version-file)
    - [LICENSE File](/guides/project_structure#license-file)
    - [CREDITS File](/guides/project_structure#credits-file)
    - [CONTRIBUTING File](/guides/project_structure#contributing-file)
    - [Other GitHub Files](/guides/project_structure#other-github-files)
    - [Images](/guides/project_structure#images)
    - [Templates](/guides/project_structure#templates)
- [Brand Guidelines (All Tiers)](#brand-guidelines-all-tiers)
    - [Color Palette](/guides/brand_guidelines#color-palette)
    - [Typography](/guides/brand_guidelines#typography)
    - [Logo](/guides/brand_guidelines#logo)
    - [Icon](/guides/brand_guidelines#icon)
    - [Banners](/guides/brand_guidelines#banners)
        - [Small Banner](/guides/brand_guidelines#small-banner)
        - [Large Banner](/guides/brand_guidelines#large-banner)
        - [Social Banner](/guides/brand_guidelines#social-banner)
    - [Other](/guides/brand_guidelines#other)
- [Tier README Templates (All Tiers)](#tier-readme-templates-all-tiers)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## Background 
I needed a system to showcase my GitHub portfolio and keep it organized and standardized. My repository README and folder/file structures were different from each other, which was a pain to maintain or use as a template for a future projects, so I created this repository and document, the <u><b>Personal Repository Guidelines</b></u> or **PRG** for short, to help solve my problem. 
- This document primarily applies to the version control system here on *GitHub* but it can be extended or applied to other version control systems as well. 
- This repository is treated no differently than my other repositories, it also adheres to **PRG** (itself in this case). 
- Feel free to fork this repo and adjust the guidelines to fit your own needs, this was designed to be a template above all else.
- If you decide to fork it and make changes to it, please provide proper credit by linking back to the main branch of this repository! Thank you!

### "The GitHub Portfolio Problem"
Another reason I created this document was to solve the "GitHub Portfolio Problem" (as I like to call it):
> GitHub is being used to showcase my portfolio, but I don't want to showcase every single repository I have created. I want to showcase my best work, but I also want to showcase my other work that I am proud of. How do I do that?

**PRG** is designed to solve this problem by catagozing repositories into three tiers: `Gold`, `Silver`, and `Bronze` to destinguish the quality of the project.
**PRG** is more than a categorization system, it also defines guidelines (and templates for you to use) for repository `README`'s and files, and defines guidelines for a repository's overall structure.

## Repository Tiers and Naming Conventions
- There are <u>three</u> tiers to describe repository projects under **PRG** collection.
- The tier is **required** to be added to the top of each repository to conform to **PRG**.
- This is what links your repository to the guidelines and helps categorize it.

### 1. Gold Tier
<a href="https://github.com/scottgriv/PRG-Personal-Repository-Guidelines">
    <img src="https://img.shields.io/badge/PRG-Gold Project-FFD700?style=for-the-badge&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iMjYuMDAwMDAwcHQiIGhlaWdodD0iMzQuMDAwMDAwcHQiIHZpZXdCb3g9IjAgMCAyNi4wMDAwMDAgMzQuMDAwMDAwIgogcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCI+Cgo8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCwzNC4wMDAwMDApIHNjYWxlKDAuMTAwMDAwLC0wLjEwMDAwMCkiCmZpbGw9IiNGRkQ3MDAiIHN0cm9rZT0ibm9uZSI+CjxwYXRoIGQ9Ik0xMiAzMjggYy04IC04IC0xMiAtNTEgLTEyIC0xMzUgMCAtMTA5IDIgLTEyNSAxOSAtMTQwIDQyIC0zOCA0OAotNDIgNTkgLTMxIDcgNyAxNyA2IDMxIC0xIDEzIC03IDIxIC04IDIxIC0yIDAgNiAyOCAxMSA2MyAxMyBsNjIgMyAwIDE1MCAwCjE1MCAtMTE1IDMgYy04MSAyIC0xMTkgLTEgLTEyOCAtMTB6IG0xMDIgLTc0IGMtNiAtMzMgLTUgLTM2IDE3IC0zMiAxOCAyIDIzCjggMjEgMjUgLTMgMjQgMTUgNDAgMzAgMjUgMTQgLTE0IC0xNyAtNTkgLTQ4IC02NiAtMjAgLTUgLTIzIC0xMSAtMTggLTMyIDYKLTIxIDMgLTI1IC0xMSAtMjIgLTE2IDIgLTE4IDEzIC0xOCA2NiAxIDc3IDAgNzIgMTggNzIgMTMgMCAxNSAtNyA5IC0zNnoKbTExNiAtMTY5IGMwIC0yMyAtMyAtMjUgLTQ5IC0yNSAtNDAgMCAtNTAgMyAtNTQgMjAgLTMgMTQgLTE0IDIwIC0zMiAyMCAtMTgKMCAtMjkgLTYgLTMyIC0yMCAtNyAtMjUgLTIzIC0yNiAtMjMgLTIgMCAyOSA4IDMyIDEwMiAzMiA4NyAwIDg4IDAgODggLTI1eiIvPgo8L2c+Cjwvc3ZnPgo=" alt="Gold PRG Badge" />
</a>
<br>

- 10+ hours of work to complete the project.
- These are the best open-sourced projects you have completed in your repository collection.
- These repositories can be used in a business/real-world environment. 
- These are considered actual **products** and more than a demo or example "Hello World" repo.
- These repositories should have their own graphic designs and brands/app icons.
- The naming scheme that will be followed for this project tier is: 
	- `Application-Brand-Name`
	- i.e. [River-Charts](https://github.com/scottgriv/River-Charts)

**Gold Repo Additional Requirements:**
- Use **upper** case letters for the first letter of each word in the project name.
- Use dashes `-` to separate words or apply spaces in the project name.
- The name should be "catchy" and easy to remember, but also descriptive of what the project is (which is why coming up with a brand for your project is important).

### 2. Silver Tier
<a href="https://github.com/scottgriv/PRG-Personal-Repository-Guidelines">
    <img src="https://img.shields.io/badge/PRG-Silver Project-C0C0C0?style=for-the-badge&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iMjYuMDAwMDAwcHQiIGhlaWdodD0iMzQuMDAwMDAwcHQiIHZpZXdCb3g9IjAgMCAyNi4wMDAwMDAgMzQuMDAwMDAwIgogcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCI+Cgo8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCwzNC4wMDAwMDApIHNjYWxlKDAuMTAwMDAwLC0wLjEwMDAwMCkiCmZpbGw9IiNDMEMwQzAiIHN0cm9rZT0ibm9uZSI+CjxwYXRoIGQ9Ik0xMiAzMjggYy04IC04IC0xMiAtNTEgLTEyIC0xMzUgMCAtMTA5IDIgLTEyNSAxOSAtMTQwIDQyIC0zOCA0OAotNDIgNTkgLTMxIDcgNyAxNyA2IDMxIC0xIDEzIC03IDIxIC04IDIxIC0yIDAgNiAyOCAxMSA2MyAxMyBsNjIgMyAwIDE1MCAwCjE1MCAtMTE1IDMgYy04MSAyIC0xMTkgLTEgLTEyOCAtMTB6IG0xMDIgLTc0IGMtNiAtMzMgLTUgLTM2IDE3IC0zMiAxOCAyIDIzCjggMjEgMjUgLTMgMjQgMTUgNDAgMzAgMjUgMTQgLTE0IC0xNyAtNTkgLTQ4IC02NiAtMjAgLTUgLTIzIC0xMSAtMTggLTMyIDYKLTIxIDMgLTI1IC0xMSAtMjIgLTE2IDIgLTE4IDEzIC0xOCA2NiAxIDc3IDAgNzIgMTggNzIgMTMgMCAxNSAtNyA5IC0zNnoKbTExNiAtMTY5IGMwIC0yMyAtMyAtMjUgLTQ5IC0yNSAtNDAgMCAtNTAgMyAtNTQgMjAgLTMgMTQgLTE0IDIwIC0zMiAyMCAtMTgKMCAtMjkgLTYgLTMyIC0yMCAtNyAtMjUgLTIzIC0yNiAtMjMgLTIgMCAyOSA4IDMyIDEwMiAzMiA4NyAwIDg4IDAgODggLTI1eiIvPgo8L2c+Cjwvc3ZnPgo=" alt="Silver PRG Badge" />
</a>
<br>

- 2-10 hours of work to complete the project.
- These are fully functional projects, but are not quite as developed to make it an actual product. 
- The naming scheme that will be followed for this project tier is: 
	- `technology/framework/language-project_name`
	- i.e. [java-backsplash_tile_square_footage_calculator](https://github.com/scottgriv/java-backsplash_tile_square_footage_calculator)
    - i.e. [angular-github_user_info](https://github.com/scottgriv/angular-github_user_info)
    
### 3. Bronze Tier
<a href="https://github.com/scottgriv/PRG-Personal-Repository-Guidelines">
    <img src="https://img.shields.io/badge/PRG-Bronze Project-CD7F32?style=for-the-badge&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iMjYuMDAwMDAwcHQiIGhlaWdodD0iMzQuMDAwMDAwcHQiIHZpZXdCb3g9IjAgMCAyNi4wMDAwMDAgMzQuMDAwMDAwIgogcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCI+Cgo8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCwzNC4wMDAwMDApIHNjYWxlKDAuMTAwMDAwLC0wLjEwMDAwMCkiCmZpbGw9IiNDRDdGMzIiIHN0cm9rZT0ibm9uZSI+CjxwYXRoIGQ9Ik0xMiAzMjggYy04IC04IC0xMiAtNTEgLTEyIC0xMzUgMCAtMTA5IDIgLTEyNSAxOSAtMTQwIDQyIC0zOCA0OAotNDIgNTkgLTMxIDcgNyAxNyA2IDMxIC0xIDEzIC03IDIxIC04IDIxIC0yIDAgNiAyOCAxMSA2MyAxMyBsNjIgMyAwIDE1MCAwCjE1MCAtMTE1IDMgYy04MSAyIC0xMTkgLTEgLTEyOCAtMTB6IG0xMDIgLTc0IGMtNiAtMzMgLTUgLTM2IDE3IC0zMiAxOCAyIDIzCjggMjEgMjUgLTMgMjQgMTUgNDAgMzAgMjUgMTQgLTE0IC0xNyAtNTkgLTQ4IC02NiAtMjAgLTUgLTIzIC0xMSAtMTggLTMyIDYKLTIxIDMgLTI1IC0xMSAtMjIgLTE2IDIgLTE4IDEzIC0xOCA2NiAxIDc3IDAgNzIgMTggNzIgMTMgMCAxNSAtNyA5IC0zNnoKbTExNiAtMTY5IGMwIC0yMyAtMyAtMjUgLTQ5IC0yNSAtNDAgMCAtNTAgMyAtNTQgMjAgLTMgMTQgLTE0IDIwIC0zMiAyMCAtMTgKMCAtMjkgLTYgLTMyIC0yMCAtNyAtMjUgLTIzIC0yNiAtMjMgLTIgMCAyOSA4IDMyIDEwMiAzMiA4NyAwIDg4IDAgODggLTI1eiIvPgo8L2c+Cjwvc3ZnPgo=" alt="Bronze PRG Badge" />
</a>
<br>

- 0-2 hours of work to complete the project.
- These repositories are projects I made to learn or understand a specific technology better (language, framework, technology, principle, etc.).
- The naming scheme that will be followed for this project tier is the same as `Silver` above, which is:
	- `technology/framework/language-project_name`
    - i.e. [csharp-nunit_test_demo](https://github.com/scottgriv/csharp-nunit_test_demo)
    - i.e. [rust-json_note_manager](https://github.com/scottgriv/rust-json_note_manager) 
    - i.e. [python-convert_html_table_to_csv](https://github.com/scottgriv/python-convert_html_table_to_csv)

**Silver & Bronze Additional Requirements:**: 
- If you have multiple languages or technologies you want to highlight, you can use the following naming scheme: language-language-language-project_name`
    - i.e. [json-xml-yaml-portfolio_template](https://github.com/scottgriv/json-xml-yaml-portfolio_template)
- Use **lower** case letters for the first letter of each word in the project name.
- Use underscores `_` to separate words in the project name.
- Use dashesa `-` to separate each language/technology.
- The languages/technologies don't necessarily have to be in any particular order, but I would recommend putting the most important one first.
- View the [badge reference](/guides/badge_references.md) file for more details on how to create badges for your repository. 

## Project Tier List (GitHub Actions)
Included in this project is a GitHub Action that will automatically generate a list of all your repositories and their tiers using GitHub Actions.
- The script is located in the `.github/workflows` folder called `project_tier_list.yml`.
- The workflow will call `scripts/build_project_tier_list.py` which will build the list and output it to `docs/project_tier_list.md`.
- The script will run on a weekly basis.
- See [Project Tier List](/guides/project_tier_list.md) for an output of what the list looks like.
- The script will also update the [Badge References](/guides/badge_references.md) file with the latest badges for your repository under your GitHub username.

### Pre-requisites:
1. You must have a `Tier` label on each repository (defined in the `PRG.txt` file)
    - In each repository, there should be a folder path that looks like this: `[project_root]/docs`.
    - Inside the `docs` folder, there should be a file called `PRG.txt`.
    - Change the repository's `Tier` label to match the tier of the repository (Gold, Silver, or Bronze).
    - See the PRG Tier file used in this repo, [here](/docs/PRG.txt), for an example.
2. Also inside the `docs` folder, there should be a subfolder called `images`.
    - Inside the `images` folder, there should be a file called `icon-rounded.png`.
    - This is the icon that will be used for the project tier list.
    - See the PRG Tier file used in this repo, [here](/docs/images/icon-rounded.png), for an example.
    - See [Brand Guidelines](/guides/brand_guidelines.md) for more details on how to create your own icon.

> [!NOTE] 
> You can reference your built project tier list in your repository `README` or wherever you see fit.
> This can be helpful showcasing your projects using the PRG system.

### Setting up the Workflow

1. Fork this repository.
2. Go to your forked repository and click on the `Actions` tab.
3. Click on the `Set up a workflow yourself` button.

## Badge References
See [Badge References](/guides/badge_references.md) for more details on how to create badges for your repository.
- Run the workflow above to get an update `badge_references.md` file pointing to your **PRG** system.

## Repository Settings (All Tiers)
See [Repository Settings](./guides/repository_settings.md) for more details on how to configure your repository settings.

## README Guidelies (All Tiers)
See [README Guidelies](./guides/readme_guidelines.md) for more details on how to structure your repository `README`.

## Project Structure (All Tiers)
See [Project Structures](./guides/project_structure.md) for more details on how to structure your overall repository/files.

## Brand Guidelines (All Tiers)
See [Brand Guidelines](./guides/brand_guidelines.md) for more details on how to create your own brand for your project.

## Tier README Templates (All Tiers)
See the following links for README templates for each tier:
- [Gold Tier README Template](./templates/gold_tier_readme_template.md)
- [Silver Tier README Template](./templates/silver_tier_readme_template.md)
- [Bronze Tier README Template](./templates/bronze_tier_readme_template.md)

## Closing
- By default, forked repositories will not have the `Tier` label, so you will need to add it manually.
    - If you forked the repository without making any changes, by default the repo will be considered a `Bronze` tier.
    - Because you did not originate the work, a forked repo can only be considered a `Bronze` or `Silver` tier, never `Gold`.

- I won't say this is *required*, because I don't want to tell you what to do with your personal profile `README`, but I strongly encourage adding the following badge to your main "About Me" profile `README` to showcase your **PRG** tier collection (this is the essence of fixing the "GitHub Portfolio Problem" I mentioned earlier):

<a href="https://github.com/scottgriv/PRG-Personal-Repository-Guidelines/blob/main/guides/project_tier_list.md">
    <img src="https://img.shields.io/badge/PRG-Optimized-6236FF?style=for-the-badge&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iMjYuMDAwMDAwcHQiIGhlaWdodD0iMzQuMDAwMDAwcHQiIHZpZXdCb3g9IjAgMCAyNi4wMDAwMDAgMzQuMDAwMDAwIgogcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCI+Cgo8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjAwMDAwMCwzNC4wMDAwMDApIHNjYWxlKDAuMTAwMDAwLC0wLjEwMDAwMCkiCmZpbGw9IiNGRkZGRkYiIHN0cm9rZT0ibm9uZSI+CjxwYXRoIGQ9Ik0xMiAzMjggYy04IC04IC0xMiAtNTEgLTEyIC0xMzUgMCAtMTA5IDIgLTEyNSAxOSAtMTQwIDQyIC0zOCA0OAotNDIgNTkgLTMxIDcgNyAxNyA2IDMxIC0xIDEzIC03IDIxIC04IDIxIC0yIDAgNiAyOCAxMSA2MyAxMyBsNjIgMyAwIDE1MCAwCjE1MCAtMTE1IDMgYy04MSAyIC0xMTkgLTEgLTEyOCAtMTB6IG0xMDIgLTc0IGMtNiAtMzMgLTUgLTM2IDE3IC0zMiAxOCAyIDIzCjggMjEgMjUgLTMgMjQgMTUgNDAgMzAgMjUgMTQgLTE0IC0xNyAtNTkgLTQ4IC02NiAtMjAgLTUgLTIzIC0xMSAtMTggLTMyIDYKLTIxIDMgLTI1IC0xMSAtMjIgLTE2IDIgLTE4IDEzIC0xOCA2NiAxIDc3IDAgNzIgMTggNzIgMTMgMCAxNSAtNyA5IC0zNnoKbTExNiAtMTY5IGMwIC0yMyAtMyAtMjUgLTQ5IC0yNSAtNDAgMCAtNTAgMyAtNTQgMjAgLTMgMTQgLTE0IDIwIC0zMiAyMCAtMTgKMCAtMjkgLTYgLTMyIC0yMCAtNyAtMjUgLTIzIC0yNiAtMjMgLTIgMCAyOSA4IDMyIDEwMiAzMiA4NyAwIDg4IDAgODggLTI1eiIvPgo8L2c+Cjwvc3ZnPgo=" alt="PRG Badge" />
</a>

- This will link to your `project_tier_list.md` file in your forked repository to showcase all of your repositories under *PRG*. 
- Feel free to add this URL to the badges on each of your repositories as well instead of pointing to the main branch of this repository or your forked repository for your Gold, Silver, and Bronze badges.

> [!WARNING] 
> Make sure you run the GitHub action workflow to replace the projects in the list with your own.
> Also, make your you change the username in the badge to your own to link to your forked repositories Project Tier List.
> Running the workflow will output a badge with your username as a hyperlink in the [Badge References](/guides/badge_references.md) file.

Thank you for taking the time to read through this document and I hope you find it useful!
If you have any questions or suggestions, please feel free to reach out to me.

## Resources
Below are some resources I found helpful when creating my repositories and **PRG** in general:
- [GitHub Docs](https://docs.github.com/en)
- [GitHub Docs - About READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)

## Project
Please reference the [GitHub Project](https://github.com/users/scottgriv/projects/8) tab inside this Repo to get a good understanding of where I'm currently at with the overall project. 
- Bugs and Enhancements will also be tracked there as well.

## Forking
Feel free to fork this repository and adjust the guidelines to fit your own needs, this was designed to be a template above all else. 
- Be sure to link back to the main branch of this repository if you decide to fork it and/or make changes to it to give proper credit! Thank you!

## Contributing
Feel free to submit a pull request if you find any issues or have any suggestions on how to improve this project.
- Please reference the [CONTRIBUTING](CONTRIBUTING.md) file in this repository for more details.

## License
This project is released under the terms of the **GNU General Public License, version 3 (GPLv3)**. 
- The GPLv3 is a "copyleft" license, ensuring that derivatives of the software remain open source and under the GPL.
- For more details and to understand all requirements and conditions, see the [LICENSE](LICENSE) file in this repository.

## Credits
**Author:** Scott Grivner <br>
**Email:** scott.grivner@gmail.com <br>
**Website:** [scottgrivner.dev](https://www.scottgrivner.dev) <br>
**Reference:** [Main Branch](https://github.com/scottgriv/River-Charts) <br>
<div align="center">
    <a href="https://github.com/scottgriv/PRG-Personal-Repository-Guidelines" target="_blank">
        <img src="./docs/images/icon-rounded.png" width="100" height="100"/>
    </a>
</div>

<!-- End README -->


