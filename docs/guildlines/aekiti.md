# ækiti Repository Guildlines
## Overview
Welcome hackers! It is **awesome** to have you here! In this guideline you would learn how to contribute to the below repository:

> [aekiti/hacktoberfest2020](https://github.com/aekiti/hacktoberfest2020){: target="_blank" }

Before you start contributing to this project make sure you have read the repository [Code Of Conduct](https://github.com/aekiti/hacktoberfest2020/blob/master/CODE_OF_CONDUCT.md){: target="_blank" }, it is really important to make this inclusive and open to everyone, otherwise, it would not be awesome.

This [repository](https://github.com/aekiti/hacktoberfest2020){: target="_blank" } was created to get developers going with Open Source during [Hacktoberfest](https://hacktoberfest.digitalocean.com/){: target="_blank" }.

## Steps
1. Fork and Clone the repository
2. Create a new branch
3. Add your contribution
4. Add your profile
5. Commit and push your fork
6. Create a pull request
7. Star the repository

## How To Contribute

=== "Step 1"
    **Fork and Clone the repository**

    _Method 1_

    To fork and clone the repo easily, execute the below `GitHub CLI` command:
    ```bash
    gh repo fork aekiti/hacktoberfest2020
    ```

    _Method 2_

    You can also click the ```Fork``` button at the right top corner and clone the forked repo using the HTTPS method

=== "Step 2"
    **Create a new branch**

    Creating a new branch for your contributions is essential, execute the below `Git` command to create your branch 
    ```bash
    git checkout -b my-branch-name
    ```

    > NOTE: The best way to replace the `my-branch-name` key in the above command is your GitHub username. E.g: aekiti

=== "Step 3"
    **Add your contribution**

    Adding your contributions can be done in 3 ways that are categorized in æpps, ærticles, and dæsigns.

    _æpps_

    The æpps categories is where you can add æpps built on æternity blockchain. Follow the below steps to add contributions based on this category:

    1. Locate the [contribution/aepps](https://github.com/aekiti/hacktoberfest2020/tree/master/contribution/aepps){: target="_blank" } directory
    2. Create a new folder/directory that respresents the æpp name
    3. Add the codes of the æpp in the newly created directory 

    _ærticles_

    The ærticles categories is where you can add articles based on æternity blockchain, open source, and hacktoberfest. Follow the below steps to add contributions based on this category:

    1. Locate the [contribution/aerticles](https://github.com/aekiti/hacktoberfest2020/tree/master/contribution/aerticles){: target="_blank" } directory
    2. Create a new folder/directory that respresents the ærticle name
    3. Add the ærticle in either pdf, txt or md format in the newly created directory 

    _dæsigns_

    The designs categories is where you can add designs based on æternity blockchain, open source, and hacktoberfest. Follow the below steps to add contributions based on this category:

    1. Locate the [contribution/daesigns](https://github.com/aekiti/hacktoberfest2020/tree/master/contribution/daesigns){: target="_blank" } directory
    2. Create a new folder/directory that respresents the design name
    3. Add the design in either png, jpg or jpeg format in the newly created directory 

=== "Step 4"
    **Add your profile**

    This is where you add your profile to showcase your contributions. Below is the step to your profile:

    1. Head to the [profile](https://github.com/aekiti/hacktoberfest2020/tree/master/profile){: target="_blank" } directory.
    2. Create a markdown file with your GitHub username in the profile directory directory: aekiti.md
    3. Copy the below snippet and fill the required field accordingly. 

    ```md
    ---
    name: FULLNAME-OR-NICKNAME # No longer than 28 characters
    institution: INSTITUTION-NAME 🚩 # No longer than 58 characters
    type: YOUR-CONTRIBUTION-TYPE # Must be in [æpp, ærticle, dæsign]
    link: <TYPE>/<CONTRIBUTION-FOLDER> # Must be your contribution folder location. <TYPE> must be in [aepps, aerticles, daesigns]
    github: YOUR-GITHUB-USERNAME # Must be your GitHub Username with the (@) symbol
    superhero: YOUR-SUPERHERO-PROFILE-LINK # Must be your Superhero profile link
    ---
    ```

=== "Step 5"
    **Commit and push your fork**

    After adding your contributions, stage, commit and push your contribution to your forked repo with the below steps:

    1. Staging Changes
    ```bash
    git add .
    ```
    2. Commiting Changes
    ```bash
    git commit -m '@username: Commit message'
    ```
    3. Pushing Changes
    ```bash
    git push origin my-branch-name
    ```

=== "Step 6"
    **Create a pull request**

    With the Step 4, your contributions would now be on your forked GitHub Repo. 
    Now you can submit a new pull request from your forked repository to be merged with main repository by clicking the `Compare & pull request` button on top of your repo. 
    Then click the `Create pull request` to create a new pull request

=== "Step 7"
    **Star the repository**

    Now that you have contributed to open source, it'd be nice to star this Repository while your contribution awaits review from the [team](https://github.com/orgs/aekiti/teams/hacktoberfest2020){: target="_blank" }

## Resources

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/){: target="_blank" }
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/){: target="_blank" }
- [GitHub CLI](https://cli.github.com/){: target="_blank" }
- [Hacktoberfest](https://hacktoberfest.digitalocean.com/details){: target="_blank" }

## Conclusion
Pat yourself on the back and wait for your **pull request** to be reviewed and merged. If merged, check your [Hacktoberfest profile](https://hacktoberfest.digitalocean.com/profile){: target="_blank" } because you have earned another contribution.