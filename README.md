# GitHub Labels

A project containing a file to generate labels for GitHub projects.

## How to use it

1. Install ```npm```.

2. Install GitHub Label Manager:

	```
	npm install github-label-manager --g
	```
3. Clone repository, or download ```labels.json``` file.

4. Generate an access token for your github account (with **repo** and **public_repo** permissions), and export the following environment variables:
	
	```
	export GITHUB_USER="<githubUsername>"
	export GITHUB_TOKEN="<githubToken>"
	```

5. Import labels into your repository:

	```
	glm import <repo> labels.json
	```

Check [https://www.npmjs.com/package/github-label-manager](https://www.npmjs.com/package/github-label-manager) for more details.
