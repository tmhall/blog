Title: WWW::Tumblr 5.00
Date: 2013-08-28 00:27:19
Tags: perl,tumblr

<a href="http://damog.net/blog/www-tumblr.html">A few years ago</a>, back when
<a href="http://tumblr.com">Tumblr</a> had not been valued a billion dollars,
I wrote <tt>WWW::Tumblr</tt>, which was basically Perl bindings for their REST
API. Then I forgot about it for a long time, then Yahoo! bought them or something
like that. I ended up getting contacted by some Perl programmers, telling me that
they were using the Perl module. Great! Anyway, following the general rule on
Internet startups, Tumblr migrated most of their endpoints to OAuth and left a
bunch of other resources changed to use an API key and others not. Joy. I gotta
say that at this point I was no longer interested on Tumblr, in spite of having
a profile whose subscribed to a few interesting picture blogs, ifyouknowwhatimean.
But people was indeed interested on the module for their stuff and I got contacted
again a <a href="https://rt.cpan.org/Public/Bug/Display.html?id=86769">few</a> <a
href="https://github.com/damog/www-tumblr/issues/2">times</a>.

Anyway, my coworker Fernando brought it to my attention more and more and I
re-started working on my OAuth branch. A few weeks later, we now have <a
href="http://https://metacpan.org/module/WWW::Tumblr">WWW::Tumblr</a> 5.00
that supports all of the methods from the new Tumblr v2 API. During the development
phase, my colleage started testing it more and more, as well as <a
href="http://yeupou.wordpress.com/2013/08/08/managing-a-tumblr-posts-queue-locally-with-tags/">this
other project</a>, so I am very thankful for their help, since it took a while to
properly make the API work. Tumblr does not seem to have the most compliant OAuth
implementation of them all, and they seem to be quite unimpressed with questions
and inquiries on their development group, but what are you gonna do about it,
*sigh*.

Anyway, head to MetaCPAN to grab your copy today! And report bugs and stuff to
the <a href="http://github.com/damog/www-tumblr">GitHub repo</a>.
