# emailfed

**Revolutionizing email address portability with a federated standard**

emailfed aims to solve a core problem of web users: When you want to change your email address, this is super tedious and many services don't even allow you to change your email address. This implicitly makes users "stuck" at one email provider, even if they would actually want to switch to another one completely, because they have to retain the old email address for some important accounts.

emailfed is a centralized gateway with a decentralized, federated architecture which aims to establish a **network** which propagates your email address changes to all services which implement and run the emailfed standard.

emailfed doesn't exist yet. But if you already say "hell yeah", then skip right to the bottom.

## What is emailfed?

A standard: Similar to the [Swedish eID framework](https://docs.swedenconnect.se/technical-framework/latest/00_-_Swedish_eID_Framework_-_Introduction.html), emailfed provides a standard: How should you retrieve emails in your code, how should you store them in your database, etc. It is the technical standard that software has to adhere to, in order to make emailfed usable with that software. Maybe it even makes sense to write an RFC, but I'm not entirely sure whether that would make sense for emailfed.

A certification: Similar to how ISO 27001 is a standard, emailfed will also need an audit. During such an audit, the service provider must illustrate that their service respects the changes performed in any of the emailfed frontends in *all* its functionality.

Reference implementations: emailfed will publish for example an NPM package, a Rust crate, or a Java library, but also plugins for entire frameworks such as plugins for Wordpress or FusionAuth, apps for Shopify etc., which can be used to "retrofit" this standard onto an existing software project easily and rapidly. At the same time, improvement suggestions will be brought into all these projects to support emailfed natively, given that handling email addresses is a core functionality of a server.

Not an email provider: emailfed isn't an email server, i.e. doesn't forward emails by itself, but it is only responsible for propagating *email address changes* through the network. It does this using a peer-to-peer network (i.e. no emailfed relay server has more power than another), in a *push* manner, similar to webhooks, i.e. where one of the servers of the "peer-to-peer federated email identity provider" (which are  contacts the server

Self-hosted and with a federated network architecture: To adhere to the distributed architecture of email itself, emailfed must also be organized decentrally. From the software side, it therefore contains mostly the backend part, i.e. the decentralized network itself, but reference implementations for frontends are also relevant. 

Ambitious: We understand that "making it easier for me to change my email address" is just the start of the global network for the propagation of personal data (imagine having the same like emailfed, but for an official name or gender change! Essentially what countries like Sweden have already, but many web services don't have that, at least not in a globally unified way.)

Not a centralized hub: Because, who would pay for that? We need an architecture through which this can become *public* infrastructure, whose architecture cannot be controlled by a select few by design. A bit similar to the protocols of e.g. bitcoin.

## Why this repository?

Currently this is only an idea, but I don't have the time right now to pick up this project, so I'm giving it away. If you want it (i.e. become admin of this repository), take it up. Write to synergies@hermesloom.org and mention your GitHub username if you're interested. If you like (i.e. in case you don't want to rename the project), you can also get the domain emailfed.org, which I already registered.

Deadline: February 15th.
