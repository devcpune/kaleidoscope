# Contributing
### Chapter 0: Making your project contribution ready
<ins>Step 1: Ensuring the readiness of your code/project</ins>

Ensure that your code and project is in a working condition and performs its intended task.

<ins>Step 2: Preparing the directory structure required for contribution</ins>

In order to ensure that your project can be accepted into our repo, please ensure your project has the
following directories/folders and files.
- **source/** -> This directory must contain your acctual project including the complete source code of your project and the `.arproj` file.
- **output/** -> This directory must contain screenshots/videos/gifs of the working of your project, the
purpose of this is to act as evidence that your project is in a working condition.
- **README.md** -> The readme file will contain general information about your project. If possible also create a trial link to the project you have created on facebook or instagram in your readme, for further infomation please refer to Step 3 for the template of this readme file.

<ins>Step 3: Preparing the README</ins>

The README file of your project must contain the following sections:
- **A Section titled Purpose** : ​ Purpose of your project
- **A Section titled Pre-requisites** ​ : What will need to be installed (including arstudio (just to make it understandable for first timers also)) in the system in order to get your
code running
- **A Section titled User Guide** : ​ How to go about using your project from the end-user perspective (may as well add pictures/videos explaining them)
- **A section titled Contact Details** : ​ Your contact information (Preferably GitHub profile and email, ⚠️ no phone numbers please)

### Chapter 1: Contributing to the DevC Pune repository
<ins>Step 1: Fork **[devcpune/kaleidoscope](https://github.com/devcpune/kaleidoscope/tree/master)** repository</ins>

<ins>Step 2: Copy project into the forked repo under ['projects'](projects/) folder</ins>

- <ins>Step 2.1 If you are creating a new project:</ins> Within the forked repo under projects directory, in the ​ develop​ branch, create a folder with the name of your project. Within
the folder create another folder in the following pattern:

  < your GitHub username >_< project name >
  
- <ins>Step 2.2 If you have developed a different flavor of an existing project:</ins>
If you have made a different version of a project that already exists in our repo then please create the
username specific folder within the original project folder with the following pattern:

  < your GitHub username >_< project name >

<details><summary>Example:</summary>
  
Let’s say a project called `Dragon` already exists in our repo and is developed by a user called `Starboy42`
The project tree will, therefore, look like:

**DevCPune/kaleidoscope/projects**
- Dragon
  - Starboy42_Dragon
    - source/
    - output/
    - README.md
    
Now, you decided to take the source code of `Dragon` and make your own improvements to it in a
manner that does not deviate the `Dragon` project from its original purpose (if it deviates from its original
purpose, then please refer Step 2.1 ). If your username is `CaptainMarvel_43`, then after your
contribution the directory tree should resemble the below structure:

**DevCPune/kaleidoscope/projects**
- Dragon
  - Starboy42_Dragon
    - source/
    - output/
    - README.md
  - CaptainMarvel_43_Dragon
    - source/
    - output/
    - README.md
</details>

<ins>Step 3: Copy all folders arranged in the desired structure into the forked repo</ins>

Once your folder has been created, copy all the files and folder created in the manner described in
Chapter 0 above (and following the structure described in that section) into the folder created in Step 2
above.

<ins>Step 4: Pull request!</ins>

Create a [pull request](#pull-request) with proper description to merge your changes into the repo hosted on the DevC Pune organization.

<ins>Step 5: Keep track of your pull request</ins>

That’s it! Wait for your pull request to be approved and merged. If there are any discrepancies, an admin
will add a comment requesting you to make the necessary changes and your pull request will have to be
updated accordingly.
## Code of Conduct

Please refer to the **[Code of Conduct](https://engineering.fb.com/codeofconduct/)** adopted by Facebook to understand what kind of behaviour will and not be tolerated when contributing to this project

## Pull Request

If you want to add your project here kindly follow the following steps:

1. Ensure your project follows all the guidelines mentioned above.
2. Open a pull request and don't forget to provide a proper description.

## Issues
We use GitHub issues to track public bugs. Please ensure your description is
clear and has sufficient instructions to be able to reproduce the issue.

## License
By contributing to this repo, you agree that your contributions will be licensed
under the LICENSE file in the root directory of this source tree.
