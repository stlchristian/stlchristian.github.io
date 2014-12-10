---
layout: post
title: Some Recent Improvements
categories: website
---
We recently made a couple small improvements to 
[SLCC's website](https://stlchristian.edu). These include a better way
to serve up the [Course Syllabi](https://stlchristian.edu/academics/course-syllabi)
from the academic office, and delivering some of our static content over
a CDN.

## Course Syllabi ##

This was one of our biggest pain points of our new website. This task
(distributing electronic syllabi for our students) was one that our old
website actually did reasonably well (one of the only things HA). When
we switched over to our [new Drupal website](https://stlchristian.edu),
this particular page was caught in the crossfire between complete functionality
and shipping our product by our deadline. In the end, this particular page,
which needs to be changed fairly regularly, was coded as a static page.

Obviously, this is less than ideal. Updating that page manually would take
a ton of time and training, and I didn't want to have to force anyone
(or myself, for that matter) to undergo such a trivial, mundane task so
many times over.

So, Tuesday, I sat down and dedicated myself to fixing this problem. The
solution isn't quite flawless, but it's a lot closer to automatic than it
was previously. If you're interested in the solution we came up with, you
can check out our [custom Drupal module here](https://github.com/stlchristian/academic_syllabi).
Hope you enjoy it.

What this means for our students is a faster, more reliable way for them
to have access to the freshest course information that the professor has
made available to them. In the end, that's a big part of what we're trying
to do here!

## Content Distribution Network ##

Our new website is hosted on [Pantheon](http://www.getpantheon.com), and
I LOVE IT!! The decision to host our site with them was probably one of
the smarter decisions we made throughout the entire web design process.
Among other things, Pantheon offers an amazing selection of Helpdesk
articles designed for people to take full advantage of some of the awesome
technology available out there.

One article that I recently read detailed (along with an awesome video)
how to integrate our Drupal site which is hosted on Pantheon with Amazon's
[CloudFront CDN](https://aws.amazon.com/cloudfront/) - 
[click here for the article](http://helpdesk.getpantheon.com/customer/portal/articles/1323605).
This seemed like a great way to optimize some of our resource delivery,
so I decided to give it a go.

One of the great things about Pantheon's [dev/test/live](http://helpdesk.getpantheon.com/customer/portal/articles/383609)
deployment workflow is that I could enable this on my dev and testing
sites without having to worry about any adverse consequences on our main
production website. Incidentally, I did momentarily jack up our test site
while I was working enabling the CDN on it, so their workflow saved my
butt!

Anyway, after a couple hours of working and testing, I was satisfied enough
to give it a go in the real world. Deployment was a snap, super-easy, and
worked exactly as advertised!

This is just one way we can show you that we're dedicated to serving up
a top-notch web experience for you. You can also take a peek at some of
the other performance improvements we're working on making. We're tracking
our progress [with this GitHub issue](https://github.com/stlchristian/stlchristian.edu/issues/51).

