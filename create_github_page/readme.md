This is how I make my first github page:

## Step 1 Create new repositary
- Use "github_username.github.io" to name the repositary
- make it a public repositary
- .gitignore template: Node
- Create "README.me"

## Step 2 Page source setting
- go to repositary settings
- click "Pages" under the "Code and automation"
- Source: Deploy from a branch
- Branch: main

## Step 3 jekyll themes
- make new file "_config.yml" under the main directory
```
theme: jekyll-theme-cayman
```

## Step 4 Edit "README.me" file
- this file will be the actuall content of the page
- links can be added
```
[folder](folder)
# folder means a new folder under the main directory
# folder contains a "README.me" file containing the content of the new page
# folder also contains a "_config.yml" file making the jekyll theme
```

