---
title: Jekyll
name: jekyll
repository: https://github.com/jekyll/jekyll
documentation: https://jekyllrb.com/docs/
ingress: Static website builder
---

## Install instructions
```bash
sudo apt-get install ruby-full build-essential zlib1g-dev -y
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
gem install jekyll bundler
```

## Start new Jekyll site
`jekyll new myblog`