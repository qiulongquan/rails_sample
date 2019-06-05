```

Ruby 中文文档
https://www.ruby-lang.org/zh_cn/documentation/


Getting Started with Rails    railsのチュートリアル
https://guides.rubyonrails.org/v5.1/getting_started.html


Ruby初学者のRuby On Rails 環境構築【Mac】
https://qiita.com/TAByasu/items/47c6cfbeeafad39eda07


安装 ruby
rbenv install --list  # 列出所有 ruby 版本
rbenv install 2.5.0     # 安装 2.5.0


列出版本
rbenv versions               # 列出安装的版本


设置版本
rbenv global 1.9.3-p392      # 默认使用 1.9.3-p392
rbenv shell 1.9.3-p392       # 当前的 shell 使用 1.9.3-p392, 会设置一个 `RBENV_VERSION` 环境变量
rbenv local jruby-1.7.3      # 当前目录使用 jruby-1.7.3, 会生成一个 `.rbenv-version` 文件


其他
rbenv rehash                 # 每当切换 ruby 版本和执行 bundle install 之后必须执行这个命令
rbenv which irb              # 列出 irb 这个命令的完整路径
rbenv whence irb             # 列出包含 irb 这个命令的版本


如何快速正确的安装 Ruby, Rails 运行环境
https://ruby-china.org/wiki/install_ruby_guide
------------------------------------------------------------
在ec2下面 安装 ruby2.4最新版本方法
To install ruby 2.4 do this, 
sudo yum install -y ruby24
And to make 2.4 the default version (the old version will still be there) do this, 
sudo alternatives --set ruby /usr/bin/ruby2.4


Debugging Rails Applications  
调试Rails应用程序方法
https://guides.rubyonrails.org/v5.1/debugging_rails_applications.html

```

# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


