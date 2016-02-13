Curl-to-PHP
===========

Curl-to-PHP is a tool to instantly convert [curl](http://curl.haxx.se) commands to PHP code in the browser. It does *not* guarantee high-fidelity conversions, but it's good enough for most API docs that have curl samples.

This is a derivitive of [curl-to-Go](http://mholt.github.io/curl-to-go/), which converts curl to a Go.


### Try it

**[Check it out!](https://incarnate.github.io/curl-to-php)** It works inside your browser. Just give the code a once-over since you may want to improve the error handling.


### FAQ

#### Does any curl command work?

Any curl command should work, but only certain flags are understood and converted into PHP code. The rest of the flags will be ignored.

#### Which kinds of curl commands are understood?

Mostly simple HTTP commands (headers, basic auth, body, etc).

#### Will you consider supporting *this-or-that* flag?

curl has like a bajillion options, so don't expect all of them to be implemented; just the most common/important ones to stub out code from API samples and docs, etc. But feel free to open an issue or submit a pull request!



### Credits

Curl-to-PHP is brought to you by John C ([@incarnated](https://twitter.com/incarnated)), based on the work of Matt Holt ([mholt6](https://twitter.com/mholt6)).
