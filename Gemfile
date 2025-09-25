source "https://rubygems.org"

# 指定 Jekyll 版本
gem "jekyll", "~> 4.3.4"
gem "minimal-mistakes-jekyll"


# 需要明确声明 Ruby 3.4 的默认 gem
gem "csv"
gem "base64"

# Jekyll 插件统一写到 jekyll_plugins 分组
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-paginate-v2"
  gem "minimal-mistakes-jekyll"
  gem "jekyll-archives"
  gem "jekyll-sitemap"
  gem "jekyll-include-cache"
 
end

# Windows平台相关依赖（更新为新写法）
platforms :windows do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1"
end
