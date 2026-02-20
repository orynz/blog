source "https://rubygems.org"

# 버전 숫자를 빼고 이름만 적으면 최신 호환 버전을 알아서 찾습니다.
gem "jekyll", "~> 4.3"
gem "minimal-mistakes-jekyll"
gem "liquid" # 버전 제약 제거

group :jekyll_plugins do
  gem "jekyll-remote-theme"
  gem "jekyll-include-cache"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jemoji"
end

# Ruby 4.0 호환성용 필수 젬
gem "webrick"
gem "csv"
gem "bigdecimal"
gem "base64"
gem "mutex_m"

gem "wdm", ">= 0.1.0" if Gem.win_platform?