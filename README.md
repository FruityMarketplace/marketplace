# Marketplace for FLStudio (unsupported by Image-Line)
A simple marketplace application for FLStudio

## Structure of this project / API Deployment
This repository has three unrelated active branches: `main`, `gh-pages` and `database`. While the source code is in the default branch `main`, the officialy added marketplace entries are stored in `database`. Those get deployed to the API via Github Actions into a single JSON file. The API is served statically via Github Pages in the branch `gh-pages.`
