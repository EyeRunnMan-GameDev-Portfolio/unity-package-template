
# Unity Package Template

This is a template repo for creating custom Unity Pacakge (upm) with github actions implemented to support auto update of packages in the npm package registery.


## Features

- A Base unity Package template to work.
- Github actions implemented to support easy distribution of packages and their updates


[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

## Usage

**After cloning the repo :** 
- replace com.`org-name`.package-name with your org name in all file/dir names and their contents
- replace com.org-name.`package-name` with your package name in all files/dir names and their contents 

**To use packages in unity from npm registery :**
<details>
  <summary>Set this up</summary>

  ![image](https://user-images.githubusercontent.com/46531095/209373322-f06beee7-9339-454f-ab50-aef27b97a05e.png)

</details>

- now go to window > package manger : 🎉enjoy your packages with automated changelogs and semver , don't forget to follow conventional commits

  

Also Use **Conventional Commits** for auto changelog and semver https://www.conventionalcommits.org/en/v1.0.0/

github action is taken from [google-github-actions/release-please-action](https://github.com/google-github-actions/release-please-action#automating-publication-to-npm)
## Environment Variables

To run this project, you will need to add the `NPM_TOKEN` github secrets set up for your own repositories to make the github actions work.
To get the token follow the steps below
- https://www.npmjs.com/ create your npm account
- https://www.npmjs.com/settings/your_username/tokens get the classic token and chose automation token , it is required in the github actions for publishing without 2FA




## 🔗 Links
**Build with ❤ By :**  [@Eyerunnman](https://www.github.com/eyerunnman)

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://eyerunnman.github.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karanbatradev/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/EyeRunnMan)

