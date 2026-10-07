# Hyperblur

[Hyperblur](https://github.com/dan1165/hyperblur) is an open-source alternative frontend to Tumblr written in Go. No account, no tracking, no caching — and no configuration beyond an optional Tumblr token. A single Go binary with every asset embedded.

## Features

- **Browse without an account:** blogs, tags, search, and explore.
- **Explore:** trending, "today on Tumblr", and per-post-type feeds (text, photos, gifs, quotes, chats, audio, video, asks).
- **Search:** popular/latest sorting, time-range filters, and post-type filters. Blog search and blog tag browsing too.
- **Full NPF rendering:** text with inline formatting (bold, italics, strikethrough, small, colour, links, mentions), headings, quotes, chat and lists; images; link cards; audio; video (native + embeds); polls with live results.
- **Reblogs:** post trails with per-trail headers and reblog attribution, plus asks.
- **Notes viewer:** replies, reblogs (filterable) and likes, with paging.
- **Media:** image alt-text widget and one-click download for images/audio/video. Downloads are proxied through hyperblur.
- **NSFW:** community-labelled posts are shown directly, unblurred.
- **UI:** dark monochrome theme, system font (no web fonts or external CDNs), posts always fully expanded, and numbered pagination on blog pages.
- **Works without JavaScript:** navigation and media browsing need none; a small amount of JS adds live poll results.

## Optional Tumblr token

Hyperblur ships a default Tumblr API token. To use your own — for example, to open blogs that require logging in — provide it in the app settings as `HYPERBLUR_TUMBLR_API_TOKEN`.

## Notes

Media loads directly from Tumblr's CDN, so Tumblr can see the IP of anyone viewing it.
