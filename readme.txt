1. Install

brew install ruby
gem install --user-install bundler jekyll
bundle update --bundler

2. Create Content 

content:
    _pages/about.yml
    
menu:
    _data/navigation.yml

3. Run 

bundle exec jekyll serve
