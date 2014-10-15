# How to set up your new mac

Please follow the steps below to set your mac for Ruby development

####Account Registrations

1. Sign up an Apple account and set it to your computer.
2. Set up an [Github](http://github.com) account. (Your personal account is allowed).
3. Set up a [Pivotal Tracker](http://pivotaltracker.com) account.
4. Set up a [Heroku](http://heroku.com) account.

####List of applications needed to be install

1. [iTerm2](http://iterm2.com/downloads.html).
2. Xcode developer tools. (Go to App Store and install Xcode).
3. [RubyMine](https://www.jetbrains.com/ruby/) latest version. (You may want to install Java).
4. [Postgres app](http://postgresapp.com/).
5. [Source Tree](http://www.sourcetreeapp.com/).
    
####List of command-line applications need to be install (After install iTerm2 and Homebrew)

1. [Homebrew](http://brew.sh/#install) - The packages manager for Mac
    
    Open iTerm and run this command
    
    ```sh
    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    ```
    
    Run `brew doctor` to make sure that you are really ready to brew.

2. [RVM](http://rvm.io/) - Ruby version manager
    
    Run this command in your terminal to install RVM and the latest version of Ruby

    ```sh
    \curl -sSL https://get.rvm.io | bash -s stable
    ```
    
    Check if the  `rvm --version` works
    
3. [Heroku Toolbelt](https://toolbelt.heroku.com/)
4. [NodeJS](http://nodejs.org/) - NodeJS is shipped with MacOS so you just need to upgrade it
    
    ```sh
    brew upgrade node
    ```
    
