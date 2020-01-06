# ghclass-actions

This repository is meant to serve a central location to collect examples of different GitHub actions workflows that are related to classroom management, automated feedback, and the [`ghclass`](https://github.com/rundel/ghclass) package.

Each example provides a yml file that implements the described actions - these files can be included in the `.github/workflows/` folder to enable that action for a repository. Badges can be included by adding a markdown image link to `https://github.com/<OWNER>/<REPOSITORY>/workflows/<WORKFLOW_NAME>/badge.svg` where `WORKFLOW_NAME` is the name of the action from the yml file. Alternatively, you can use the `repo_add_badge` function from the `ghclass` package.

## Current Examples

* [Check Reproducibility](check_rmd/)  - This workflow attempts to knit the students Rmd assignment.
* [Check Allowed Files](allowed_files/) - This workflow uses a provided R script to check for allowed files within the repository
* [Auto styler](styler_pr) - Use [styler](https://github.com/r-lib/styler) to generate a pull request for student repos
