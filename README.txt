Steps to updating your website

1. Set working directory the location of blogdown_source repository in C:/Iwen/github. Can do this in the console 'setwd("C:/Iwen/github/blogdown_source")'. Or open up `blogdown_source` project

2. Make your updates in the 'static' folder: 
- Navigate to files locally
- Add additional projects to 'config.toml'. 
- Add blog posts to 'content/post' (new_post(title = 'hello-world.Rmd'))

3. Run 'library(blogdown)' and 'serve_site()` to see test changes.

4. Once ready, run 'build_site()' - relevants files should be copied to the iwensu0313.github.io repository.

5. Commit, pull, and push changes in blogdown_source repo.

6. Set wd to location of iwensu0313.github.io repository 'setwd("C:/Iwen/github/iwensu0313.github.io")'. Do this in console. OR go to iwensu0313.github.io project if you're in the blogdown_source project.

6. Then commit, pull, and push changes to iwensu0313.github.io repo to GitHub. Can also use terminal (git add -A, git commit -m "some message", git pull, git push)