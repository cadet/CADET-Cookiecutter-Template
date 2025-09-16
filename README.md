# Cookiecutter Template for CADET-Repositories
This cookiecutter template automatically generates the general file structure for a new CADET-Repository on Github.
 Please refer to [https://github.com/cookiecutter/cookiecutter](https://github.com/cookiecutter/cookiecutter) for additional information. 

---

## Authors

* Katharina Paul
* Hannah Lanzrath 

---

## Using the cookiecutter template

1. Clone this repository.
2. Set up the environment using the `cookiecutter_environment.yml` file.
3. Navigate to the desired location of your new repository.
3. Run this command:

   ```bash
   cookiecutter /path/to/cloned/cookiecutter-repository/
   ```

4. Enter your input to all upcoming questions. Click Enter to assign the default values given in (). Following this, the file structure will be automatically generated.

5. Complete the repository creation by manually adding all missing information to the generated files. Initialize the git repository and add remotes to share your new repository.

---

## Content

This cookiecutter template automatically creates a repository with the following content:
* README.md
* LICENCE.md
* AUTHORS.md
* SECURITY.md
* CODE_OF.CONDUCT.md
* CONTRIBUTING.md
* CITATION.bib
* .zenodo.json
* pyproject.toml
* environment.yml
* .pre-commit-config.yml
* .github/dependabot.yml
* .github/workflow/ruff.yml