# gh-pages-github

LiveSite Url: https://sayyedhammadali.github.io/gh-pages-github/

## Configuration

1. npm i gh-pages

2. Edit package.json file
```

"scripts": {
  "deploy":"npm run build && gh-pages -d build"
},
"homepage": "https://[github_username].github.io/[repository_name]",

```
3. npm run deploy
