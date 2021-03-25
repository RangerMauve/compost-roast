# compost-roast
Roast of Compost Magazine and Decentralized Press

## Roast

I wanna preface this with saying that I love all the folks that worked on this project and it's been genuinly exciting to see this unfold as it's a big step in making the decentralized web usable and sustainable.

That said, it can help to see where the next steps can be.

## So how does it hold up?

Compost was pretty ambitious with publishing to not only the web, but also two peer to peer protocols in tandem using Hypha's Distributed Press API.

Let's see if those protocols actually work!

https://one.compost.digital
ipns://one.compost.digital
hyper://one.compost.digital

Cool!

Now lets see if the APIs that Distributed Press provides for Monetization actually load.

https://api.compost.digital/v0/monetization/balances.json
ipns://api.compost.digital/v0/monetization/balances.json
hyper://api.compost.digital/v0/monetization/balances.json

Options:
- Whoops, doesn't look like that actually loads.
- Jeeze, it finally loaded, but it seems kinda slow
- Hmmm, now I wonder if this would load in stock Safari on an iPhone?

## Principles

So now we know whether it actually works.

But how does it stack up against the Decentrealized Principles we just talked about?

## Technology for Human Agency

First let's talk about how technology should be used for human agency, and where we might need a bit more attention to increase it.

Tracking:

So, technology should respect people's privacy, and Compost's first issue is completely free from any third party tracking from what I saw in the console.
However, the distributed press website isn't as free from tracking.

https://distributed.press/

Like many websites, it uses Google's handy content delivery network for loading some JavaScript APIs and some fonts.
This means that Google gets to know everyone that's interested in looking up what this Distributed Press thing is all about so they can further analyze us and give us relevant advertisements without us being strictly aware that that's happening.
That goes to show that Google and it's tracking has a grip on the web even in corners that are trying to do their best to avoid it.

https://www.digitalocean.com/

Of course, if you want to go the full mile and set up your own Distributed Press instance, you'll get even more tracking curtosy of Digital Ocean which phones home to not just Google, but also Twitter, Facebook, and a bunch of other analytics URLs.

Speaking of setup.

Distributed press is pretty cool in that it uses peer to peer tech, however it isn't itself decentralized.
In order to set it up you need to be on the more advanced side of tech literacy.
In addition to making cool content, you need to find some nerds which will set up a virtual machine, know what an Ansible is, and how to actually use them together.
Their guide also assumes you have a bank account to pay for a domain and for Virtual Machine hosting, in addition to the technical know-how for what those things even are.
It'd be nice if setting something like this up used peer to peer software, or better yet didn't require servers or banks at all.

## Ecological Awareness

Now, Compost's first issue has a lot of good feelings in it regarding communities and the environment.
How does the rest of it fare with regards to ecological impact?
Compost and Distributed Press in general is using this cool new standard called Web Monetization which transfers bits of money to pages that you visit using a browser extension and some opt-in from website authors.
Monetization is good, and content creators being paid is something we should see more of.
However we could watch out for how we make those payments happen when web monetizations are largely backed by large banks and energy hungry blockchains.

https://api.compost.digital/v0/monetization/balances.json

Acually, we can see the ecological impact of compost by checking out their balances.json file and seeing all the etherium that they've got.

It seems that the real roasting going on is the heat from the GPUs that were used to process those transactions.
Eventually things like Etherium promise to have a smaller carbon footprint with stuff like Proof of Stake, but then we'll have a whole other set of considerations.

## Conclusion

Compost looks amazing, and from a technical point of view it's very novel and usable.

However, I hope it looks like there's still space for improvement and I'm sure that the small things I brought up today will be less relevant as everyone iterates and grows together.
