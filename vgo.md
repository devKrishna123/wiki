# VGO

## Table of Contents

* [Initial reference paper](#initial-reference-paper)
* [Issue tracker](#issue-tracker)
* [Comment Threads](#comment-threads)
* [Blog posts](#blog-posts)
* [Videos](#videos)
* [Questions](#questions)

This document collects thoughts and notes about vgo from the Gophers [#vgo](https://gophers.slack.com/messages/vgo) channel. Invites to Gophers Slack from [here](https://invite.slack.golangbridge.org/).

### Initial reference paper

The initial paper can be read here [https://research.swtch.com/vgo](https://research.swtch.com/vgo).

The reference implementation is done here: [https://github.com/golang/vgo](https://github.com/golang/vgo).

### Issue tracker

The [Go issue tracker](https://golang.org/issues) will be used to track bugs / feature requests for vgo. The issues will need to start with ` x/vgo ` for now. You can read the [existing issues here](https://golang.org/issues?q=is%3Aopen+is%3Aissue+milestone%3Avgo).

### Comment Threads

These are threads that have been created from the initial reference manifest for vgo:

- **golang-nuts ML:** [https://groups.google.com/forum/#!topic/golang-nuts/jFPz5yZCPcQ](https://groups.google.com/forum/#!topic/golang-nuts/jFPz5yZCPcQ)
- **golang-dev ML:** [https://groups.google.com/forum/#!topic/golang-dev/MNQwgYHMEcY](https://groups.google.com/forum/#!topic/golang-dev/MNQwgYHMEcY)
- **HackerNews posts:** https://news.ycombinator.com/from?site=swtch.com
- **Reddit:** https://www.reddit.com/domain/research.swtch.com/

***

### Blog posts

- [Thoughts on vgo and dep](https://sdboyer.io/blog/vgo-and-dep/)
- [Semantic Import Versioning in the wild](http://blog.ezyang.com/2018/02/semantic-import-versioning-in-the-wild/) (blogpost).

***

### Videos

[Building Predictability into Your Pipeline](https://www.youtube.com/watch?v=sbrZfPgNmfw) With Russ Cox, Jess Frazelle, Sam Boyer, Pete Garcin.

***

### Questions

| Question | Answer |
| ------------- | ------------- |
| Hitting GitHub API rate limits? | Create a token and add it to .netrc, see [related issue](https://golang.org/issues/23955) |
| How does vgo handles dependencies of older, discarded versions [https://gophers.slack.com/archives/C9BMAAFFB/p1519493604000033](https://gophers.slack.com/archives/C9BMAAFFB/p1519493604000033) | [https://github.com/zeebo/vgo-test-version-selection](https://github.com/zeebo/vgo-test-version-selection) |