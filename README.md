# jekyllTest

## (InstructionsPermalink)[https://jekyllrb.com/docs/]
    Install all prerequisites [https://jekyllrb.com/docs/installation/].
    Install the jekyll and bundler gems.
    gem install jekyll bundler
        bundle add webrick
    Create a new Jekyll site at ./myblog.
        jekyll new myblog
    Change into your new directory.
        cd myblog
    Build the site and make it available on a local server.
        bundle exec jekyll serve --livereload
        Browse to http://localhost:4000


    set EnvironmentsPermalink
    JEKYLL_ENV=production bundle exec jekyll build
    
    get in template
    jekyll.environment


## DeploymentPermalink
    JEKYLL_ENV=production bundle exec jekyll build
    And then copy the contents of _site to your server.