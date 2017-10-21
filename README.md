# dccodecoffee.github.io
The Official DC Code &amp; Coffee Website.

### I want a site like this!
Feel free to fork or copy this repo :)

#### Update links & text in:
- header (navbar)
- banner
- footer
- `_config.yml`

#### Meetup Widget Setup
1. Get your Meetup API key from here: https://secure.meetup.com/meetup_api/key/
2. Get signed url, like the instructions here: http://www.meetup.com/meetup_api/auth/#keysign
  - Type into the browser, using your API_KEY and MEETUP_NAME: `https://api.meetup.com/2/events?key={API_KEY}&group_urlname={MEETUP_NAME}&sign=true`
  - copy out the `signed_url` from this response, like it says in the keysign article
  - example signed url: https://api.meetup.com/2/events?key=36464e5e766dd5a6a487f215b7e5614&group_urlname=alexandria-code-coffee&sign=true
3. Paste the signed url into `events.html`

#### Twitter Widget Setup
1. https://publish.twitter.com (https://twitter.com/settings/widgets)
2. Put in the url like twitter.com/alxcodecoffee
2. make the height ~800px or something like that

## Run locally

You'll need ruby installed.

1. Run `bundle install`
1. Run `jekyll serve`
1. Navigate to <http://127.0.0.1:4000/>
