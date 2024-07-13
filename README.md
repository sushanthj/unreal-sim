# About this Template

While previous templates used heroku for the build, I've started moving all builds to github instead.

To replicate this template do the following:
1. Create a new repository on github
2. Clone it locally
3. Download a zip-file of this repo and move all contents to your new repository
4. In the _config.yaml change the ```url: https://sushanthj.github.io/unity``` to  ```url: https://sushanthj.github.io/<NEW_REPO_NAME>```
5. Push the changes (```git push```)
6. Then go to the repository settings on Github and set Github Pages Build option to ```Github Actions```
7. NOTE: Don't choose any 'Jekyll' action if prompted

# Local Testing
To run the following code setup Jekyll on your computer

Refer: https://jekyllrb.com/docs/installation/ubuntu/
Refer: https://jekyllrb.com/docs/step-by-step/01-setup/

The above links should follow the same procedure as shown below:
(Please recheck below commands with above links to stay updated)

Jekyll + Ruby Installation:

1. sudo apt-get install ruby-full build-essential zlib1g-dev
2. echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
3. echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
4. echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
5. source ~/.bashrc

6. gem install jekyll bundler

7. bundle init

For example jekyll project do

8. gem "jekyll"

Or clone the repo in local machine and run the following command within the working directory:

bundle exec jekyll serve
