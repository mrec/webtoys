This repo contains various small web-based apps, experiments, bug demos and the like. There's no overarching theme, 
it's just somewhere to put them. Anything that might be interesting will be linked from somewhere else, e.g. a blog
post, so there's no catalogue listing here as yet.

I'm quite fond of the hashbang pattern for this sort of thing: reflecting persistent page state in a URL fragment 
so that it'll survive reload and can be captured in simple hyperlinks, and populating from that fragment at load. 
I'm aware of the criticisms levelled against the pattern, but I don't think they apply here. The pages that use it 
are fundamentally reliant on JavaScript, and the state isn't something that'd belong in referrer headers even if 
anyone still sent referrer headers.

Everything is dual-licensed under MIT and Apache-2.0 unless explicitly stated otherwise.
