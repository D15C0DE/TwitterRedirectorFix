# Twitter Redirector Fix
Configuration for the Firefox Redirector plugin that fixes Twitter with Enhanced Tracking Protection enabled.

# How to use
1. Install the plugin https://addons.mozilla.org/en-US/firefox/addon/redirector/
2. Use it to import the Redirector.json file.
3. Enjoy Twitter (FWIW)

# Background info
On 2024-05-17, Twitter started redirecting twitter.com to x.com, however it still pulls content from twitter.com, which runs afoul of Firefox' strict tracking protection which sees that as third party content. However by appending a parameter to the URL, it's possible to avoid the redirect in the first place. That's where the Redirector add-on comes in handy. Using it, we can force all URLs to twitter.com and thus fix the problem of x.com requesting twitter.com data.
