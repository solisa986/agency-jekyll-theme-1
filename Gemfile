#after any changes to the Gemfile, execute bundle update!
source "https://rubygems.org"

gem "jekyll-remote-theme"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  # gem "github-pages" # https://github.com/github/pages-gem
  git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }
end

# Delete the following lines if not on Windows:
# Performance-booster for watching directories on Windows
gem "wdm", ">= 0.1.0" if Gem.win_platform?
gem "jekyll-agency"
gem "jekyll"
