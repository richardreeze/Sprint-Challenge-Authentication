<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
- Middleware: Software that runs after a request is received, but before a response is sent back (hence why it's called Middleware).

- Sessions: When a user logs into a site for the first time, they create a session ID that is unique to that user. A session ID tracks how many times the user has logged in to the site.

- bcrypt: A password hashing tool.What I just learned is that it's the default password hash algorithm for OpenBSD (thanks Wikipedia). That's pretty cool!

- JWT (JSON Web Token):Basically a string that contains a header, a payload, and a signature. Once a user logs into a service, the server provides them with a JWT and then uses that token to confirm the user is making all the requests they say they are.

1.  What does bcrypt do in order to prevent attacks?
- First, it hashes our password (which means it turns it into a long complicated random string). Second, it adds some salt (so now the long, complex string is longER and MORE complex). Third, it does all this stuff slowly(which sounds bad, but is actually good because it means it would take hackers way too long to decrypt our passwords, so it's not worth it for them and they give up).

1.  What are the three parts of the JSON Web Token?
- Header, payload, and signature.
