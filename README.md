erlang-email-address
====================

An email address validator in Erlang

So far, this is a simple email validator in Erlang and can be included in your project using rebar. For instance,
add these lines to your rebar.config:

    { 
      deps, [
       { email_address, ".*", 
	       { git, "git://github.com/mswimmer/erlang-email-address.git", "master"}}
	    ]
    }.

Once included, you can use it in your code like:

    email_address:is_valid(EmailUnderTestHere).

It returns true or false.

TODO: Don't get me started! This code has a long way to go still.
