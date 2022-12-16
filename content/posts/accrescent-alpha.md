---
title: "Accrescent has reached public alpha!"
date: 2022-12-16
draft: false
---

As some of you may know, I've been working on building a new Android app store called [Accrescent]
for [almost a year now]. My goal was to solve the inherent security, privacy, and usability issues
of existing Android app stores by designing a new store from the ground up to address them. Today,
I'm proud to announce that Accrescent has entered public alpha! You can try it out yourself today by
downloading it from [our website] or from our [GitHub releases].

### What is Accrescent?

For those who don't know, Accrescent is an open-source Android app store designed from the ground up
to be secure, private, and usable by default. It has first-class support for split APKs without
requiring developers to give up exclusive control of their app signing keys, meaning users get the
size saving benefits of split APKs while developers can rest assured that their keys can't be lost
or abused by Accrescent.

Accrescent builds off this feature further by pinning developers' app signing certificates in signed
metadata so that first-time app installs are always verified. This means that even if Accrescent's
servers were compromised, an attacker wouldn't be able to swap out a legitimate app for a malicious
one. Accrescent will simply refuse to install it.

Accrescent also has full support for unprivileged, unattended updates. This means that when app
updates arrive, you won't need to manually approve each one. They happen silently in the background
when you're not using your device, so you don't even need to think about them. This doesn't require
rooting or a special OS - it just works.

Of course Accrescent has other distinguishing features with many more to come. If you're curious
about how Accrescent works and how it stands out from other Android app stores, check out [our
website].

### What does this mean?

Whitelisted developers can now submit their apps to Accrescent through the [developer console].
Accrescent is still in the early stages, but this alpha release is a major milestone toward
Accrescent becoming a competitive alternative in the Android app ecosystem.

Accrescent was built to maintain backwards compatability even across major changes, so even though
this release is alpha, no breaking changes are anticipated at this time. If a breaking change
becomes necessary, there will most likely be a transition period for people to update so that most
won't experience breakage.

### What's next for Accrescent?

We have a [long roadmap] ahead of us. Some of the first priorities are adding app descriptions and
developer information to the store, improving the user experience of the submission process,
displaying app icons, and installing language packs on-demand. If there's a feature you want to see
or a bug you want to report, don't hesitate to create an issue or pull request on our [GitHub]. We'd
love to hear your feedback so that we can make Accrescent a more pleasant and feature-rich user
experience for everyone. We're excited to see Accrescent grow into the flourishing app store we
envision.

Here's to the future!

[Accrescent]: https://accrescent.app
[almost a year now]: https://twitter.com/lberrymage/status/1475307653089792003
[developer console]: https://dev.accrescent.app
[long roadmap]: https://github.com/orgs/accrescent/projects/2
[our website]: https://accrescent.app
[GitHub]: http://github.com/accrescent
[GitHub releases]: http://github.com/accrescent/accrescent/releases
