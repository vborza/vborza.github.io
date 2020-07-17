How to run locally:
bundle exec jekyll serve --config _config.yml,_config_dev.yml

How to deploy:
Switch to "source" branch
build the site to some different location: bundle exec jekyll build --config _config.yml -d "C:\Users\vborza\Documents\borzadev"
Switch to master branch and replace the files with the build

The repo could not be built automatically with standard github jekyll flow, because it uses custom plugin for tags pagination.