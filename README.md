Multiply By Two
===============

**Warning, this module has malicious behaviour**

This is a demonstration module used in my [blog post] on malicious node modules.
If you import this module, it will return a function which multiplies a number
by two. Additionally, it will attempt to hijack express in a manner that adds
a malicious payload to every request which intercepts stripe's client side 
library. See the blog post for more details.

This code is explicitly designed to not be very copy-and-paste portable, and 
will likely fail when imported into a project that doesn't behave exactly the
same as the [companion repository] for this project.

[blog post]: https://fosterelli.co/stealing-credentials-with-a-malicious-node-module.html
[companion repository]: https://github.com/chrisfosterelli/node-stripe-membership-saas
