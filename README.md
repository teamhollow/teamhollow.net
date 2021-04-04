# teamhollow.net

The Team Hollow Website built with Jekyll 3.8.5

## Getting Started

### Linux

#### 1A) On Linux Install Ruby

`sudo apt install ruby-full`

#### 1B) On Windows

You need to install [Ruby](https://rubyinstaller.org/). Make sure you get at least 2.6.X.

#### 2) Clone the repo

`git clone https://github.com/teamhollow/teamhollow.net.git`

#### 3) Install bundler

`gem install bundler`

#### 4) Set up the workspace

Navigate to the root of the directory and type: `bundle install`  
This should install all the packages needed for development.

**Do not commit the modified Gemfile after this finishes** ***unless a gem needs to be updated!*** **Lachney will usually take care of that if that is the case.**

## Compiling

You can either build the website or serve it.

### Build

`bundle exec jekyll build`

This will build the website and generate everything in the `_site` directory.

`bundle exec jekyll serve`

This will start a web server and serve the website on `http://127.0.0.1:4000`/`http://localhost:4000`

## Contributing

Please make sure all your code is formatted properly and neatly and double check for any errors. Verify that your HTML elements work on multiple browsers. When you have verified everything, push your changes (or send a pull request) and the live website `teamhollow.net` will update from GitHub whenever possible.
