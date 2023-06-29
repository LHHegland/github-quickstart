# github-quickstart

**NAMESPACE:** me.hegland-lance

**PURPOSE:** Practice using VSCode, Git, and GitHub tools while testing development environment installation and configuration of VSCode, Git, and GitHub.

.

## Table of Contents

- [Features](#features)
- [Background](#background)
- [Known Issues](#known-issues)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Authors](#authors)
- [Roadmap](#roadmap)
- [License](#license)

.

## **Features**

Quick and easy practice and testing of VSCode, Git, and GitHub tools, including the following:

- creating local and remote GitHub repositories, including branching, plus a pull request and merge
- using VSCode to update common project files, including the following:
  - README.md
  - LICENSE.txt
  - .gitignore
- using the following Git features
   | Command | Tutorial | Git Ref |
   |---------|----------|---------|
   | init | [Link](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-init) | [Link](https://git-scm.com/docs/git-init) |
   | status | [Link](https://www.atlassian.com/git/tutorials/inspecting-a-repository) | [Link](https://git-scm.com/docs/git-status) |
   | diff | [Link](https://www.atlassian.com/git/tutorials/saving-changes/git-diff) | [Link](https://git-scm.com/docs/git-diff) |
   | add | [Link](https://www.atlassian.com/git/tutorials/saving-changes) | [Link](https://git-scm.com/docs/git-add) |
   | commit | [Link](https://www.atlassian.com/git/tutorials/saving-changes/git-commit) | [Link](https://git-scm.com/docs/git-commit) |
   | remote | [Link](https://www.atlassian.com/git/tutorials/syncing) | [Link](https://git-scm.com/docs/git-remote) |
   | push | [Link](https://www.atlassian.com/git/tutorials/syncing/git-push) | [Link](https://git-scm.com/docs/git-push) |
   | clone | [Link](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone) | [Link](https://git-scm.com/docs/git-clone) |
   | checkout | [Link](https://www.atlassian.com/git/tutorials/undoing-changes) | [Link](https://git-scm.com/docs/git-checkout) |
   | branch | [Link](https://www.atlassian.com/git/tutorials/using-branches) | [Link](https://git-scm.com/docs/git-branch) |
   | fetch | [Link](https://www.atlassian.com/git/tutorials/syncing/git-fetch) | [Link](https://git-scm.com/docs/git-fetch) |
   | merge | [Link](https://www.atlassian.com/git/tutorials/using-branches/git-merge) | [Link](https://git-scm.com/docs/git-merge) |
   | cmd | [Link]() | [Link]() |
   | cmd | [Link]() | [Link]() |
   | cmd | [Link]() | [Link]() |
   | cmd | [Link]() | [Link]() |

   See also [.gitignore](https://www.atlassian.com/git/tutorials/saving-changes/gitignore).

.

## **Background**

Lance Hegland wanted to test his local development environment, including the following tools:

- VSCode
- Git
- GitHub

.

## **Known Issues**

None

.

## **Requirements**

1. Familiarity and access to recent versions of the following development tools:
   | Tool                         | Download | Reference | with VSCode |
   |------------------------------|----------|-----------|-------------|
   | VSCode | [Link](https://code.visualstudio.com/Download) | [Link](https://code.visualstudio.com/learn) | |
   | + Markdown Preview Github Styling | [Link](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles) | | |
   | + GitHub Pull Requests and Issues | [Link](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) | | |
   | Git | [Link](https://git-scm.com/downloads) | [Link](https://git-scm.com/videos) | [Link](https://vscode.github.com/) |
   | GitHub  | | [Link](https://github.com) | [Link](https://code.visualstudio.com/docs/sourcecontrol/github) |

.

## **Installation**

None

.

## **Configuration**

None

.

## **Usage**

1. Review README.md for [GitHub user LHHegland](https://github.com/LHHegland) [repository github-quickstart](https://github.com/LHHegland/github-quickstart)
1. Let's pretend that Dakota Smith creates a simulated project
   1. From the local projects directory, create a local working area github-quickstart (`git init github-quickstart`)
   1. Copy and update README.md
   1. Copy LICENSE.txt
   
   1. Review repository differences (working vs. staging)
      1. Review staging vs working areas (`git status`)
   1. Update working area to staging area (`git add --verbose --all`)

   1. Review repository differences (working vs. staging vs. commits vs. remote)
      1. Review staging vs working areas (`git status`)
      1. Review commit history (`git log --oneline`)
      1. Review commit change summary by file (`git log --stat`)
      1. Review brief commit messages by author (`git shortlog`)
      1. Review commit diagram (`git log --graph --oneline --decorate`)
      1. Review commit changes by file (`git log -p`)
      1. Review last commit vs working (`git diff`)
      1. Review last commit vs staging (`git diff --cached`)
   
>
> ↑ ↑ ↑ COMPLETED ↑ ↑ ↑
> ↓ ↓ ↓   TO DO   ↓ ↓ ↓
>

   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Update staging area to commits area (`git commit --message="Initial Commit with Base Files by Dakota Smith — dsmith@domain.tld — 555-987-2160"`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. [Create remote GitHub repository](https://github.com/LHHegland?tab=repositories) LHHegland/github-quickstart
   1. Connect to that remote repository (`git remote add origin git@github.com:LHHegland/github-quickstart.git`)
   1. Verify remote repository (`git remote -v`)
   1. Update remote repository (`git push -u origin master`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Create text content documents with 70-character lines in working area
      1. file-a.txt containing 3 paragraphs of sample text from [Lorem Ipsum](https://www.lipsum.com/)
      1. file-b.txt containing 3 paragraphs of sample text from [Lorem Ipsum](https://www.lipsum.com/)
      1. file-d.txt containing 3 paragraphs of sample text from [Lorem Ipsum](https://www.lipsum.com/)
      1. file-j.txt containing 3 paragraphs of sample text from [Lorem Ipsum](https://www.lipsum.com/)
      1. file-t.txt containing 3 paragraphs of sample text from [Lorem Ipsum](https://www.lipsum.com/)
      1. file-z.txt containing 3 paragraphs of sample text from [Lorem Ipsum](https://www.lipsum.com/)
   1. Create .gitignore listing file-j.txt
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Update working area to staging area (`git add --verbose --all`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Update staging area to commits area (`git commit --message="Created ABDJTZ Feature by Dakota Smith — dsmith@domain.tld — 555-987-2160"`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Update remote repository (`git push -u origin master`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
1. Then, Pat Doe creates a new feature in their local working area github-quickstart-rev-qtz
   >
   > Typically, a contributor would fork the remote repository into a new remote repository then use git fetch to gather and update the relevant files. However, GitHub doesn't allow a user to fork their own repositories. So, we will use a branch.
   >
   1. From the local projects directory, copy the entire remote GitHub repository LHHegland/github-quickstart into a local working area (`git clone git@github.com:LHHegland/github-quickstart.git github-quickstart-rev-qtz`)
   1. Verify remote repository (`git remote -v`)
   1. Review existing branches (`git branch --list`)
   1. Checkout the master branch into a new branch rev-qtz  (`git checkout -b rev-qtz`)
   1. Review existing branches (`git branch --list`)
   1. Perform the changes
      1. Create text content document file-q.txt with 70-character lines containing 3 paragraphs of sample text from [Lorem Ipsum](https://www.lipsum.com/)
      1. Update file-z.txt
         1. Edit line 26 at column 55 to replace "diam" with "quis"
         1. Edit line 7 starting with column 15 to delete "ultrices, "
         1. Edit line 13 starting with column 10 to replace "r" with "n"
         1. Edit starting with line 23 column 49 to replace "Sed ornare leo eu ex
mollis ullamcorper. Phasellus ultrices tristique molestie. Fusce ipsum
orci, vehicula et sodales aliquet, placerat non justo." through line 25 column 54 with "Donec porta posuere nisi eu gravida. Pellentesque in ullamcorper diam, ut efficitur elit. Cras lobortis convallis elit, sed accumsan ligula."
         1. Insert " Ut et risus id diam." at the end of line 10
      1. Delete file-t.txt
      1. Review repository differences (working vs. staging vs. commits vs. remote)
      1. Update working area to staging area (`git add --verbose --all`)
      1. Review repository differences (working vs. staging vs. commits vs. remote)
      1. Update staging area to commits area (`git commit --message="Add Feature Q, Delete Feature T, Update Feature Z by Pat Doe — pdoe@domain.tld — 555-987-6543"`)
      1. Review repository differences (working vs. staging vs. commits vs. remote)
      1. Update branch rev-qtz in remote repository (`git push -u origin rev-qtz`)
      1. Review repository differences (working vs. staging vs. commits vs. remote)
1. While Pat Doe was creating the new feature, Dakota Smith worked on an unrelated new feature in their local working area github-quickstart
   1. Review existing branches (`git branch --list`)
   1. Fetch the updated remote repository (`git fetch`)
   1. Review existing branches (`git branch --list`)
   1. Checkout the master branch into the working area (`git checkout master -f`)
   1. Perform the changes
      1. Create text content document file-g.txt with 70-character lines containing 3 paragraphs of sample text from [Lorem Ipsum](https://www.lipsum.com/)
      1. Delete file-d.txt
      1. Update file-a.txt
         1. Edit line 17 starting with column 19 to replace "Phasellus in pulvinar mi. Sed molestie nisi quis erat bibendum, vitae tincidunt orci mollis. Etiam et nunc scelerisque, semper elit id, lacinia eros." through line 19 column  29 with "Praesent interdum lacus ac lacus vulputate condimentum. Vivamus tincidunt varius orci, at condimentum sapien efficitur sit amet."
         1. Insert " Pharetra nibh." at the end of line 21.
         1. Edit line 7 starting with column 31 to replace "e" with "i"
         1. Edit line 25 starting with column 35 to delete "non "
         1. Edit line 13 starting with column 15 to replace "elit" with "nunc"
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Update working area to staging area (`git add --verbose --all`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Verify remote repository (`git remote -v`)
   1. Review existing branches (`git branch --list`)
   1. Fetch the updated remote repository (`git fetch`)
   1. Verify remote repository (`git remote -v`)
   1. Review existing branches (`git branch --list`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Update staging area to commits area (`git commit --message="Add Feature G, Delete Feature D, Update Feature A by Dakota Smith — dsmith@domain.tld — 555-987-2160"`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Update master branch remote repository (`git push -u origin master`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
1. While Dakota Smith was working, Pat Doe created a pull request to merge rev-qtz branch into master branch
   1. Create pull request to merge rev-qtz branch into master branch with the following message:
      > Please consider merging this update into the github-quickstart application for expanded capabilities, improved ease of use, more efficient processing, and improved readability. This update adds feature Q, which more efficiently includes and replaces feature T plus required update to Feature Z. Thank you for developing this powerful application and your consideration of this potentially helpful update. Please contact me with any concerns or questions. Sincerely, Pat Doe — pdoe@domain.tld — 555-987-6543
      >
      > This revision includes the following changes:
      >
      > - Add file-q.txt
      > - Delete file-t.txt
      > - Modified file-z.txt
      >   - Edit line 7 starting with column 15 to delete "ultrices, "
      >   - Insert " Ut et risus id diam." at the end of line 10
      >   - Edit line 13 starting with column 10 to replace "r" with "n"
      >   - Edit starting with line 23 column 50 to replace "Sed ornare leo eu ex
      mollis ullamcorper. Phasellus ultrices tristique molestie. Fusce ipsum
      orci, vehicula et sodales aliquet, placerat non justo." through line 25 column 54 with "Donec porta posuere nisi eu gravida. Pellentesque in ullamcorper diam, ut efficitur elit. Cras lobortis convallis elit, sed accumsan ligula."
      >   - Edit line 26 at column 55 to replace "quis" with "diam"
      >
1. Check to see if Dakota Smith can use git to merge rev-qtz branch into master branch correctly
1. troubleshoot if necessary 
1. Dakota Smith notices, reviews, and responds to Pat Doe's pull request to merge rev-qtz branch into master branch
   1. Reply to and close this pull request saying:
      > Before we can merge rev-qtz branch into master branch, we need to merge the most recent changes to the master branch into the rev-qtz branch to minimize potential conflicts and errors. Please review the pull request to merge the most recent changes from master branch into rev-qtz branch, preserving the desired changes in rev-qtz branch. Then, approve and merge if appropriate. Finally, submit a new pull request. If you have any questions or concerns, please contact Dakota Smith — dsmith@domain.tld — 555-987-2160. Thank you!
      >
      > The recent changes to the master branch are as follows:
      >
      >  - Added file-g.txt
      >  - Deleted file-d.txt
      >  - Updated file-a.txt
      >     - Edited line 7 starting with column 31 to replace "e" with "i"
      >     - Edited line 13 starting with column 15 to replace "elit" with "nunc"
      >     - Edited line 17 starting with column 19 to replace "Phasellus in pulvinar mi. Sed molestie nisi quis erat bibendum, vitae tincidunt orci mollis. Etiam et nunc scelerisque, semper elit id, lacinia eros." through line 19 column  29 with "Praesent interdum lacus ac lacus vulputate condimentum. Vivamus tincidunt varius orci, at condimentum sapien efficitur sit amet."
      >     - Inserted " Pharetra nibh." at the end of line 21.
      >     - Edited line 25 starting with column 35 to delete "non "
      >
1. Pat Doe reviews and integrates master branch changes into rev-qtz branch while preserving desired new feature changes
   1. Fetch the updated remote repository (`git fetch`)
   1. Checkout the rev-qtz branch into the working area (`git checkout rev-qtz -f`)
   1. Verify remote repository (`git remote -v`)
   1. Review existing branches (`git branch --list`)
   1. Review master branch vs working area (`git diff master`)


* merge ADGQTZ
|\
* | add feature ADG
| * add feature QTZ
|/
* add feature ABDTZ
* initial files

   1. Merge the master branch changes into the rev-qtz branch (`git merge --no-ff master`)
   1. ERROR
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Update working area to staging area (`git add --verbose --all`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Update staging area to commits area (`git commit --message="Merge recent master branch changes, preserving desired feature changes by Pat Doe — pdoe@domain.tld — 555-987-6543"`)
   1. Review repository differences (working vs. staging vs. commits vs. remote)
   1. Update branch rev-qtz in remote repository (`git push -u origin rev-qtz`)
   1. Create another pull request to merge rev-qtz branch into master branch with the following message:
      > Included requested master branch changes into rev-qtz branch.
      >
      > Please consider merging this update into the github-quickstart application for expanded capabilities, improved ease of use, more efficient processing, and improved readability. This update adds feature Q, which more efficiently includes and replaces feature T plus required update to Feature Z. Thank you for developing this powerful application and your consideration of this potentially helpful update. Please contact me with any concerns or questions. Sincerely, Pat Doe — pdoe@domain.tld — 555-987-6543
      >
      > This revision includes the following changes:
      >
      > - Add file-q.txt
      > - Delete file-t.txt
      > - Modified file-z.txt
      >   - Edit line 7 starting with column 15 to delete "ultrices, "
      >   - Insert " Ut et risus id diam." at the end of line 10
      >   - Edit line 13 starting with column 10 to replace "r" with "n"
      >   - Edit starting with line 23 column 50 to replace "Sed ornare leo eu ex
      mollis ullamcorper. Phasellus ultrices tristique molestie. Fusce ipsum
      orci, vehicula et sodales aliquet, placerat non justo." through line 25 column 54 with "Donec porta posuere nisi eu gravida. Pellentesque in ullamcorper diam, ut efficitur elit. Cras lobortis convallis elit, sed accumsan ligula."
      >   - Edit line 26 at column 55 to replace "quis" with "diam"
   1. Delete local working area github-quickstart-temp
1. Dakota Smith reviews, merges, and responds to Pat Doe's latest pull request to merge rev-qtz branch into master branch
   1. Reply to, merge, and close this pull request saying:
      > Reviewed and merged rev-qtz branch into master branch by Dakota Smith — dsmith@domain.tld — 555-987-2160. Thank you!
   1. Prune (delete) rev-qtz branch
   1. Delete local working area github-quickstart-rev-qtz
1. Clean-up local working area and remote repository
   1. Delete local working area github-quickstart-orig
   1. Delete remote repository github-quickstart
   1. Delete local working area github-quickstart

**References:**

- [Git Basics Videos Episode 3: Get Going with Git](https://git-scm.com/video/get-going)
- [Working with GitHub in VS Code](https://code.visualstudio.com/docs/sourcecontrol/github)
- [GitPracticeV2 Project Branch Master](https://docs.google.com/drawings/d/1f0Ouv_SPXVfDvYsHISk0JJA9yB-Y6pzUk4KfvceT_Mk/edit)
- [Set up Git](https://docs.github.com/en/get-started/quickstart/)
- [Create a repo](https://docs.github.com/en/get-started/quickstart/)
   1. [Fork a repo](https://docs.github.com/en/get-started/quickstart/)
   1. [GitHub flow](https://docs.github.com/en/get-started/quickstart/)
   1. [Contributing to projects](https://docs.github.com/en/get-started/quickstart/)
   1. [Be social](https://docs.github.com/en/get-started/quickstart/)
   1. [Communicating on GitHub](https://docs.github.com/en/get-started/quickstart/)
   1. [GitHub glossary](https://docs.github.com/en/get-started/quickstart/)
   1. [Git cheatsheet](https://docs.github.com/en/get-started/quickstart/)
   1. [Git and GitHub learning resources](https://docs.github.com/en/get-started/quickstart/)
1. Create hegland-lance workspace
1. Create Git Project github-test (`git init github-test`)
1. (`git remote add [name] [URL]`)
1. Create repository content

.

## **Authors**

- Lance Hegland ([lance.hegland@gmail.com](mailto:lance.hegland@gmail.com))

.

## **Roadmap**

None

.

## **License**

GNU General Public License v3.0 (GNU GPLv3)

- See [LICENSE.txt](LICENSE.txt)
- See [GNU General Public License v3.0 (GNU GPLv3)](https://choosealicense.com/licenses/gpl-3.0/)
