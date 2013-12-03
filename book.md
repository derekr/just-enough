Software is complicated.

It also kind of sucks!

It's also kind of great! Not so much the software itself is great, but the 
problems it can solve are great. The delight it can bring to someone is great. 
The act of creation is great.

I've written a lot of bad software in my seven years as a professional 
(relative term) and am only just now starting to return the basics and really 
beginning to learn.

I'm a strong believer in honest concepts. Ideas that are so rooted in 
fundamentals and that just *feel* right. These honest concepts have 
been popping up more and more as I've started developing software in node. 
While not perfect the practices and community that have built up around node in 
the past few years come the closest to what I feel are honest. Most importantly 
I can build cool shit without much getting in the way.

This isn't meant to be an a-z guide on developing web apps in node, but more of 
a journal of writing minimal software using tools that are available today. 
With any luck this writing will be rendered obsolete within a few years.

# About This Book

Writing this book is somewhat arbitrary. I woke up at three in the morning 
some night and immediately feel in to a nerd nightmare. At the end of it came 
my ah-ha moment: write a book! Not fully sure of what the book would be about 
only vague notions of talking about node web apps and 
simple frontend architecture.

** Node **
# Just Enough
# Modules
# Services/Servers
# Request/Response/Middleware

** Frontend **
# Builds
# Routing/Pipeline
# Views
# API/CORS

# Modules
## Substack Pattern
## Singleton

# Services and Utilities
## Web services
## Data services
## UI modules

* Break up your app in to smaller services/modules
* Common in almost all web based apps
  - www
  - api
* Consider breaking out things even more
  - styles
  - components (dropdowns, popovers, modals, sliders...)
  - email (email templates/styles)
  - admin (any supplementary tools to your app)
* Smaller services are easier to deploy and maintain (if there is a bug in one you don't experience the burden of deploying all of your code)
