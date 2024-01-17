# 1. How to Create GitHub PR Template
1. Create a folder named `.github`
2. Create a file `pull_request_template.md`
3. Define your template
4. Push to the main repo
5. Now whenever you'll request a PR, it will open up the default template to fill in the details.

# 2. How to Create a GitHub Issue Template
1. Create a folder named `.github`
2. Inside that directory, create another directory called `ISSUE_TEMPLATE`.
3. Under the new `ISSUE_TEMPLATE` directory, create a file called `feature_request.md`
4. Define the template.
5. Push to the main repo.
6. Now whenever you'll go to issues -> New issue, it will open up the default template to fill in the details.

# 3. Auto-Assign a Pull Request on GitHub
1. Create a folder named `.github`
2. Under the folder, create a file calle `CODEOWNERS` (all caps). Note that you can also create this file under the main project folder if you don't want to create `.github` folder.
4. Add contributors names in the file, e.g:
```
* @AbdulDevHub @mariam1203
```
Note: The `*` means global access i.e. owner of all files.

# 4. How to automatically Squash Commits on GitHub when Merging Pull Requests
1. Go to your repo's settings on GitHub
2. Scroll down until you see `Merge button` section.
3. Select `Allow squash merging` and remove the check mark from `Allow merge commits`. Now on the PR you'll notice that instead of `Merge pull request`, you see `squash and merge` button as default. If you click on it, it will automatically squash the commits asking for final text as comment and then you can merge it.

# 5. Automatically Delete Branches after Merging Pull Requests on GitHub
1. Go to your repo's settings on GitHub
2. Scroll down until you see `Merge button` section.
3. Select `Automatically delete head branches`.
4. Now after the merge your PR, the branch will be automatically deleted.
