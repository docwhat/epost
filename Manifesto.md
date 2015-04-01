# Introduction #
I am sick of Mailman and its lesser cousins; listserv, majordomo, etc.
n

They are horrible to use.  Both from an administrators point of view and the users point of view.

# Expected Experience #
I decide I'm going to subscribe to mailing list foo.  I go to http://example.com/lists/foo

I'm presented with two choices:
  * login
  * signup

I decide to sign up.  I enter all the email addresses I expect to post with.

It sends emails to all those accounts, but then asks which account I want to receive updates to.  I can select none if I want.

I select one, and select continue.

I check my mail and my confirmation emails are there.  I click on one and it tells me how many more addresses are still left to confirm.

I can now turn off the emails or change the account that gets the messages (or add more, if I want dups for some reason).

I can also manage all other mailing lists that this system knows about.

Unsubscribing is also done similarly.  It understands I have multiple emails and can tie them all together and let me unsubscribe at once.

# Administration Experience #
From the user administration view, I expect the following:
  * I can designate an email account as "read/write" or "read-only".

# Conclusion #
That's it.

Everything else will be plugins or additional software.
  * Want digests?  It's a plugin.
  * Want spam filtering?  It's a plugin.
  * Want bounces to auto-unsubscrie?  It's a plugin.
  * Want archiving? It's a plugin.

The goal is to focus on the main experience of subscribing and getting mail from a mailing list.  Everything else is separate.

Ciao!