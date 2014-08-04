
RHoK Brisbane website
---------------------

[http://rhokbrisbane.org](http://rhokbrisbane.org)

One-pager for the Brisbane chapter of Random Hacks of Kindness. This project is a simple static site builder and it handles deployment to GH pages.


**Setup & Development**

This projects uses [Middleman](http://middlemanapp.com/). You will need ruby installed on your machine.

	bundle install	
	
	# To run the server
	bundle exec middleman


**Deployment:**

    rake build;
    rake publish
