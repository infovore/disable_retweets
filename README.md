# disable_retweets

Disable retweets from one user or from many. This may or may not help your sanity.

## Installation

You'll need Ruby, probably 1.9+.

Run `bundle install` from inside the directory you've downloaded or checked out.

You'll need the usual credentials for a Twitter app. You can make them at apps.twitter.com - you'll need to mae an app, give it read/write privileges, and then generate an access token for the app.

Then, stick your TWITTER_API_KEY, TWITTER_API_SECRET, TWITTER_ACCESS_TOKEN, and TWITTER_ACCESS_TOKEN_SECRET into `.env` . A sample .env file is included.

## Usage

	./disable_retweets.rb all

To disable retweets from everyone you follow. This may take a while, but it'll set there just waiting not to time out.

	./disable_retweets.rb @infovore
	
To disable retweets from a single user (in this case, `@infovore`).

