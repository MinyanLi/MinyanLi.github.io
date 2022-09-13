## How I make my first github pages blog

updated on 2022-09-13

#### Step 1 Create new repositary
- Use "github_username.github.io" to name the repositary
- make it a public repositary
- .gitignore template: Node
- Create "README.me"

#### Step 2 Page source setting
- go to repositary settings
- click "Pages" under the "Code and automation"
- Source: Deploy from a branch
- Branch: main

#### Step 3 jekyll themes
- make new file "_config.yml" under the main directory

```
remote_theme: pages-themes/slate@v0.2.0
plugins: - jekyll-remote-theme
title: Blog title
```

#### Step 4 Edit "README.me" file
- this file will be the actuall content of the page
- links can be added
```
[folder](folder)
# folder means a new folder under the main directory
# folder contains a "README.me" file with contents of the new page
```

