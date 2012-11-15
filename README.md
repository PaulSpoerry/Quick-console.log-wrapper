Quick-console.log-wrapper
=========================

Quick console.log wrapper


Today I was debugging an issue for a client and needed a way to debug without breaking their site. Sadly, there was no prior testing done (despite them having a test environment) so I was debugging directly on the live site. If you’ve done any front-end web work recently you likely know about the console and console.log. Firebug, Chrome Developer Tools, and even IE now support the console. Console.log is quick and dirty debugging. I needed the ability to splash a boatload of log messages out but wanted to be able to control when they displayed. There are tons of libraries out there to do this, and of course jQuery supports it but using a third party utility (no, jQuery isn’t currently in use) wasn’t an option. So here’s a simple console.log wrapper.