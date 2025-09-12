# www.quillweave.com with Pages
Quill weave temporary website

## Local Set up
* Install Jekyll
  
  _for macos:_
  ```
  brew install chruby ruby-install
  ruby-install ruby 3.4.1
  echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
  echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
  echo "chruby ruby-3.4.1" >> ~/.zshrc # run 'chruby' to see actual version
  gem install jekyll
  ```

* To run the application
  ```
  bundle exec jekyll serve
  ```

  
