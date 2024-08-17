# dogeopen

* [projects](projects.md)
* [ideas](ideas.md)
* [donors](donors.md)
* [linux](linux.md) 




# Mission Statement: 
# economic empowerment using opensource technology 

# donate to those in need

# transparency through blockchain

# we are one // you are vital 


help us help humanity, with ideas, support, and donations

X.COM/DOGEOPEN

name: Jekyll site CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
    - uses: actions/checkout@v2

    - name: Set up Ruby
      uses: ruby/setup-ruby@v1
      with:
        ruby-version: '3.0' # Specify the Ruby version you are using

    - name: Install dependencies
      run: |
        gem install bundler
        bundle install

    - name: Build the site
      run: bundle exec jekyll build

    - name: Deploy to GitHub Pages
      uses: peaceiris/actions-gh-pages@v3
      with:
        github_token: ${{ secrets.GITHUB_TOKEN }}
        publish_dir: ./_site






                          *UNDER CONSTRUCTION*

<iframe src="https://global-mind.org/gcpdot/gcp.html" height="48" width="48" scrolling="no" marginwidth="0" marginheight="0" frameborder="0" ></iframe>

<canvas id="gcpChart" style="position: absolute; z-index: 1001; background-color: rgba(0, 0, 0, 0); top: 20px; left: 0px;" width="300" height="140"></canvas>
## Dogecoin Price Ticker

<iframe src="https://widgets.coingecko.com/coingecko-coin-price-chart-widget?coin_id=dogecoin&currency=usd" width="300" height="300" frameborder="0" style="border:0; margin:0; padding:0;" allowfullscreen></iframe>




