# Steps to updating your website

1. Set working directory the location of blogdown_source repository in C:/Iwen/github by opening up `blogdown_source` project in RStudio. Run 'library(blogdown)'.

2. Make your updates in the `blogdown_source` repo: 
* Navigate to files locally
* Add additional projects to 'config.toml'.
* Add images to 'static/images'. Edit them by navigating to files locally
* Add new presentations or workshops to 'content/post' (new_post(title = 'seaweed-aquaculture'))
* For presentations or workshops with download files, may need to manually add in iwensu0313.github.io repo `post` folder (see seaweed aquaculture presentation for an example)
* Still figuring out where to customize css. Copied 'main.css' into 'static/css'

3. Run 'serve_site()` to see test changes.

4. Once ready, run 'build_site()' - relevants files should be copied to the iwensu0313.github.io repository.

5. Commit, pull, and push changes in blogdown_source repo.

6. Set wd to location of iwensu0313.github.io repository 'setwd("C:/Iwen/github/iwensu0313.github.io")'. Do this in console. OR go to iwensu0313.github.io project if you're in the blogdown_source project.

7 Then commit, pull, and push changes to iwensu0313.github.io repo to GitHub. Can also use terminal (git add -A, git commit -m "some message", git pull, git push)