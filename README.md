# rails-angular-getting-started


#### Environment Setup

- Install Homebrew

`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

- Install Homebrew Cask

`brew install caskroom/cask/brew-cask`

#### Ruby Setup

- Install RVM
 
`which gpg`

`$ /usr/local/bin/gpg`

If gpg not installed:

`brew install gpg`

Install mpapis Public Key:

`gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3`

Install RVM Stable:

`\curl -sSL https://get.rvm.io | bash -s stable --ruby`

`$ rvm list`

`$ rvm install 2.2.3`

Open up a terminal and type `ruby -v`

You should have 2.2.3, Ex:

`$ ruby 2.2.3p173 (2015-08-18 revision 51636) [x86_64-darwin14]`

#### PostGRES

`$ brew install postgresql`

`$ ln -sfv /usr/local/opt/postgresql/*.plist ~/Library/LaunchAgents`

`$ launchctl load ~/Library/LaunchAgents/homebrew.mxcl.postgresql.plist`

I recommend PGAdmin III:

`$ brew cask install pgadmin3`

Create a username with no password that's the same as your username:

``

#### Install Node / NPM:

`brew install node`

node -v

`$ v4.1.1`

npm -v

`2.14.4`

Install npm packages for Angular / Gulp Generator:

`npm install -g yo gulp bower`

`npm install -g generator-gulp-angular`
