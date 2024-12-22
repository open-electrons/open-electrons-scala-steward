# open-electrons-scala-steward

This project's sole purpose is to keep the open-electrons dependencies up to date. The GitHub Actions is scheduled to run every Friday midnight so
that I can have fun merging shit loads of pull requests over the weekend.

To add new projects for automatic dependency updates, add the corresponding project to the [repos.md](https://github.com/open-electrons/open-electrons-scala-steward/blob/master/repos.md) in the format as below:

'''
- repo_owner/project_name
'''

Where repo_owner is always open-electrons and the project_name is the actual project under the ownership of open-electrons.
