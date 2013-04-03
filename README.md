## Getting Started

* Clone and init working directory

		$ git clone git@bitbucket.org:continuum_chile/wistudi-layout.git
		$ cd wistudi-layout


* Create gemset and rvmrc

		$ rvm --create --rvmrc 1.9.3@middleman
		$ rvm rvmrc trust


* Install middleman gem:

		$ gem install middleman
		$ bundle install
		$ bundle exec middleman server
