# The new podcast namespace
**`<rss version="2.0" xmlns:podcast="https://podcastindex.org/namespace/1.0">`**
- - -
Since the [first podcast](https://blogs.harvard.edu/lydondev/2003/07/09/spoken-word-a-few-good-bloggers/) in 2003, the medium has been evolving. Apple added [their own iTunes podcast namespace in 2005](https://podcasters.apple.com/support/823-podcast-requirements), extending the RSS specification to specify things like podcast artwork, categories and other elements. In 2020, the new podcast namespace was first worked on by a wide number of interested people, aided and encouraged by Adam Curry and Dave Jones from [The Podcast Index](https://podcastindex.org/).

**The new podcast namespace is a set of new tags that are 100% backwards compatible with existing podcast feeds.** Like the Apple iTunes podcast namespace, the new podcast namespace adds additional features, like transcripts, locations, alternate audio files, and many more benefits for the open podcast ecosystem. You can spot these tags by looking for those that start `<podcast:` in the RSS feed.

Individual tags are now supported by a growing number of [podcast hosting companies](https://podcastindex.org/apps?appTypes=hosting) and [podcast apps](https://podcastindex.org/apps?appTypes=app).

## All the base tags

From [the specification document](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md):
* [podcast:alternateEnclosure](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#alternate-enclosure) - different bitrates, video versions, etc
* [podcast:block](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#block) - creator requests not to be included in a directory
* [podcast:chapters](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#chapters) - independently editable chapters
* [podcast:episode](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#episode) - episode numbers and names
* [podcast:funding](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#funding) - links to donate or fund a show
* [podcast:guid](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#guid) - a unique, global identifier for a podcast
* [podcast:images](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#images) - multiple image resources for podcasts
* [podcast:license](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#license) - define the license applied to a podcast
* [podcast:liveItem](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#live-item) - deliver live shows to apps
* [podcast:location](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#location) - "where is this podcast about?"
* [podcast:locked](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#locked) - require permission to import a feed
* [podcast:medium](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#medium) - a description of the type of content in a feed
* [podcast:person](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#person) - credits for hosts and guests
* [podcast:season](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#season) - named seasons/series
* [podcast:socialInteract](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#social-interact) - comments for podcast episodes
* [podcast:soundbites](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#soundbite) - suggested clips
* [podcast:trailer](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#trailer) - specify a trailer (per season)
* [podcast:transcript](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#transcript) - captions and transcripts for podcasts
* [podcast:value](https://github.com/Podcastindex-org/podcast-namespace/blob/main/docs/1.0.md#value) - a payment layer for podcasts

## This website

This website will be a place to give full examples of how to use the new podcast namespace tags. It is editable by the community; and you will also be able to use this to [ask questions](https://github.com/jamescridland/podcastnamespace.org/discussions) about implementation.


### As an example...
* [podcast:funding](https://podcastnamespace.org/tag/funding), a way to link to donation payment links for your podcast

It's edited by James Cridland, the Editor of [Podnews](https://podnews.net); but anyone can submit their edits to make this resource better, using the Github link in the bottom right. Alternatively, please contact James at james@crid.land
