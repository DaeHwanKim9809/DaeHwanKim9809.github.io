source "https://rubygems.org"

# GitHub Pages 지원 버전의 Jekyll 및 모든 필수 플러그인 포함
gem "github-pages", "~> 231"

# 필요한 경우 추가적인 의존성 추가
gem "faraday-retry" # Faraday v2.0+와 함께 사용하기 위해 추가

# Windows에서의 특정 설정 (필요시)
#install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
#  gem "tzinfo", "~> 1.2"
#  gem "tzinfo-data"
#end

# Windows 성능 향상을 위한 설정
#gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

# 로컬 테스트용 HTTP 서버
gem "webrick", "~> 1.7"