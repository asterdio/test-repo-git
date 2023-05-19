# Asterdio Incorporated

![logo](https://asterdio.com/wp-content/uploads/2022/06/asterdio-light.png)


Boilerplate for all the porjects in the Asterdio Inc Organization

Developer tools used:
husky for pre-commit hook

Commit style:
Conventional commit

- fix — to indicate a bug fix (PATCH) ex . v0.0.1
- feat — to indicate a new feature (MINOR) ex. v0.1.0
- chore — for updates that do not require a version bump (.gitignore, comments, etc.)
- docs — for updates to the documentation
- BREAKING CHANGE — regardless of type, indicates a Major release (MAJOR) ex. v1.0.0
- revert — if reverting the commit

Application versioning
- Alpha - v1.0.0-alpha/ for active development branch i.e staging/dev branch
- Beta - v1.0.0-beta/uat for UAT branch 
- standrad - v1.0.0 for production/main branch

> Make sure to give proper permissions to the hooks and husky file

<code>
   - chmod ug+x .husky/*
</code>

<code>
   - chmod .git/hooks/*
</code>