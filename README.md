# commitlog

> An idea I had while walking down a park on a Sunday.

* Periodically poll the activity feed: https://github.com/{username}.atom
	* Filter and get only pushes: `<entry><title>` contains `{username} pushed`, `<entry><content>` contains `<time>` and `<ul>` with commits (title etc)
	* If there are new pushes since the last poll, post to twitter as individual status
	* Store last poll time, last push time
