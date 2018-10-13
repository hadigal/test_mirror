# This repo is created to test the mirroring functionality in git #
- Create a directory.
- clone the repo you want to mirror e.g. for bitbucket to github
  * run the following cmd from the repo:
    - `git clone --mirror https://<username>@bitbucket.org/<username>/<director>.git`/
  * move to the cloned repo and run the following cmd:
    - `git remote set-url --push origin https://github.com/<username>/<directory>.git`
  * Now push: `git push --mirror`
- login to the github UI you will notice bitbucket repo with commits on github
