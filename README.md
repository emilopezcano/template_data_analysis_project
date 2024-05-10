# Template for data analysis projects

This is an opinionated template for data analysis projects (using R). I used to ended up with this structure when starting a project from scratch, so I decided to create a project template as a repository. 

## Structure

- This `README.md` file, to be changed for any new project.
- `LICENCE`: For this template, I have chosen the GNU GENERAL PUBLIC LICENSE. My data analysis projects are usually private and I don't include a licence.
- `.gitignore`: Extension of the R template in GitHub (see comments inside the file)
- 📁 `data`: For data files
- 📁 `R`: For R scripts
- 📁 `reports`: For quarto and/or R Markdown files

Possible additions:

- `.Renviron`: When connecting to databases or other no-shared values are needed
- `.Rprofile`: When needed initial code (actually I only use that when using {renv} 📦)
- 📁 `tests`: For {testthat} 📦 stuff
- 📁 `xx-app`: For shiny apps (I will create another template, though)
- `Dockerfile*`, `docker-compose.yml`: for dockerized apps.
- Branches: In this projects I don't usually use branches at all. Sometimes, I create issues and branches per feature from the issue.

## Process

1. Create GitHub Repo from template
2. Recommended: use {renv} 📦: `renv::init()` (install if needed)
3. Create project in RStudio from control version


## Acknowledgements

Thank you [Victor](https://github.com/Vacek-Ace) for putting me on the path to github repo templates.

Comments and improvements are very welcome!


