# A starter website build with Jekyll

Inspired and created following https://www.taniarascia.com/make-a-static-website-with-jekyll/

## Install Jekyll - https://jekyllrb.com/

```
sudo gem install jekyll bundler
```

If behind a proxy server.

```
sudo gem install jekyll bundler --http-proxy=http://192.168.1.248:8080/
```

* One needs to clone the repo and cd into its root.

```
git clone https://github.com/akolinski/startjekyll.git
```

```
cd /startjekyll
```

* Run bundle install inside the repository folder

```
bundle install
```

* If that fails you might need to update your version of ruby. You can update ruby using homebrew - https://brew.sh/. 

* If behind a proxy run the export command below before running the brew command below.

```
export http_proxy=http://192.168.1.248:8080 && export https_proxy=http://192.168.1.248:8080 && export HTTP_PROXY=http://192.168.1.248:8080 && export HTTPS_PROXY=http://192.168.1.248:8080
```

```
brew install ruby
```

* Now try to install jekyll again.

## Clone the repository

Using your terminal navigate to the location where you have all your development projects. Clone the repository in this location using the line below.

```
git clone git@github.com:akolinski/startjekyll.git
```

## Get to work

Run this command.

```
bundle exec jekyll serve --config _config.yml, _config_dev.yml --port 4444 --watch
```

Access the website externally - https://akolinski.github.io/startjekyll/
Access the website locally - http://127.0.0.1:4444/startjekyll/