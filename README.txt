Steps to updating your website

1. Set working directory the location of blogdown_source repository in C:/Iwen/github. Can do this in the console 'setwd("C:/Iwen/github/blogdown_source")'
2. Make your updates in the 'static' folder. Add additional projects to 'config.toml'. Add blog posts to 'content/post' (new_post(title = 'hello-world.Rmd'))
3. Run 'library(blogdown)' and 'serve_site() to see test changes.
4. Once ready, run 'build_site()' - relevants files should be copied to the iwensu0313.github.io repository.
5. Set wd to locatin of iwensu0313.github.io repository on local computer 'setwd("C:/Iwen/github/iwensu0313.github.io")'. Then commit, pull, and push changes to GitHub.