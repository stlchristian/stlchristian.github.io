---
layout: post
title: "[Tech Tip Example] Phishing in the Wild"
categories: techtip example
---

In our first Tech Tip, we talked about [Skepticism when it comes to emails/websites/phone calls]({% post_url 2014-12-11-a-healthy-dose-of-skepticism %}).
It just so happens that this week, I received a real-life phishing email,
and I wanted to share it with the class! Pasted below is the exact email:

<pre>
Attn:  E-mail  User,
 
Your email account will soon be suspended (Reason: Quarterly quota
maintenance). To update your email account, please Click this link
Here    http://systadmindpt.nazuka.net/     and fill the form immediately
for the reactivation of your Web-Mail Account.
 
This message is from Webmail Administrator Messaging Center to all
Webmail Account Owners. Please follow instruction on this message and
your account will be updated within 24 hours. We sincerely apologize
for this unusual problem.
 
Thank you for using our online services.
Webmail Administrator..
</pre>

I thought it might be helpful if I dissect some of the reasons that this
particular message is ultra-sketchy.

1. It's not apparent in the copy/paste above, but the email came with a
   blank **To:** address. This tells me that I'm not the only one who
   received this email, and it also tells me that the sender probably put
   a bunch of emails in the **BCC:** field.
   
   **Reputable senders don't generally use this technique.**

1. The email doesn't contain my name. Even if a legit system automatically
   generates a message like this, they will address it to your actual,
   real name, not "E-mail User." This is a dead giveaway that this isn't
   really coming from my email provider.
   
   **Reputable senders know your name.**

1. The danger they are presenting (losing acess to my email account) is
   presented inconsistently. Here are the various things that might take
   place if I don't do what the email asks me to do:
   
   - My account will soon be suspended.
   - My account is already deactivated, and filling out the form on the
     sketchy web address (more on that later) will reactivate it.
   - My account simply needs to be updated.
   
   If a real email hosting company has to send out a notice like this,
   they will use very clear, unmistakable language to convey to you what
   might come about as a result of your inaction. This email doesn't
   convey what will hapen with any level of certainty.
   
   **Reputable senders are clear when they need you to take some action.**

1. The email contains an ultra-sketchy link. Please, for the love of God,
   do not visit this website! Not only have you never heard of this website,
   it's URL doesn't even make any sense! The website kinda has some techno
   sounding words in it, but at the end of the day, it means nothing to
   you. You've (hopefully) never visited this site before, so the unfamiliar
   domain name should be enough to scare you off for good.
   
   **Reputable senders will direct you to a familiar, sensible website.**

1. The website is even-more-ultra-sketchy. If you didn't listen to my
   advice from the last point, and you clicked on the link, shame on you.
   That said, you'll already know that the website doesn't look like any
   you've ever visited before. Here's a screenshot:
   
   [![Phishing email in the wild](/img/phishing-email.png)](/img/phishing-email.png)
   
   Several things about this don't look right:
   
   - The error message at the top of the screen shouldn't be there.
   - Now, you're being asked to verify your webmail address rather than
     reactivate, save, update, or whatever-the-heck else they told you to
     do.
   - They use word "key-in." Small thing, I know, but **nobody** says that
     anymore! What year is it? 1993?
   - Not to mention that you **still** don't know what company this is!
   
   I know that none of these are enough to stop you in your tracks, by
   themselves. However, given the evidence we've gone through, each of
   these small items should be sufficient enough to hammer in a final nail
   in the coffin of dear old Webmail Administrator.
   
   **Reputable senders will usually have a more polished, consistent website
   that they've directed you to.**

All this effort has gone into trying to trick you. You should be offended
that they think so little of you! They think it's that easy to fool you!

They want to steal your legitimate email address and password, and then
they'll have access to your inbox (and all the sensitive information that
it contains), contacts, sent mail, and they'll even be able to send out
email as if they're you.

I hope that this example has taught you a little more about the anatomy
of a phishing attempt.

Good luck out there!
