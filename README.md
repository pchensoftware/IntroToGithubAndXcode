# IntroToGithubAndXcode
Introduction to Github and Xcode for non-engineers

## Setup Your Github Account

- Signup for a github account on [github.com](github.com)
- [Enable two factor auth](Enable https://github.com/blog/1614-two-factor-authentication)
- Have the owner of a repository allow you to view the repository

## Create an Apple ID for Development

- Have an Apple developer add you as a member of their account

## Setup Xcode

- Download Xcode
    - the latest from the [Mac App Store](https://itunes.apple.com/us/app/xcode/id497799835?mt=12), or
    - an older version from the [Apple developer resources](https://developer.apple.com/downloads/). Here's [Xcode 6.4](http://adcdownload.apple.com/Developer_Tools/Xcode_6.4/Xcode_6.4.dmg).
- Run Xcode

## Grab the code

- Create a [github access token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/)
- Run the following from the Terminal app on your Mac:

    ```
    > cd ~/
    > mkdir Software
    > cd Software
    > git clone https://some-github-repo...
    
         username: enter_your_username
         password: enter_the_github_access_token
      
    > cd some-github-repo
    ```

