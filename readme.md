# RFC: Curling Generosity

[![10x sweeping](curlings-broom-boom.jpg '10x sweeping')](https://ca.sports.yahoo.com/blogs/eh-game/curling-s-broom-boom-leads-to-player-meeting-in-toronto--are-regulations-coming-022117902.html)

_Here are some thoughts about tipping on Brave. I'm a big fan of the project
and the team and I mean no disrespect. Please excuse any excessive candor._

## Recap

- React to tipping as matter-of-factly as Twitter reacts to a like
- Allow zero-click, action-based auto-contribute (tip-on-like, tip-on-RT)
- Set up browser-wide default tip amount, save when changed
- At most one-click tipping always
- Allow a comfortable (eg. monthly) window for undoing tips
- Enqueue all tips by default; make final or cancel on Rewards screen
- Enable offline tipping (comes for free with queueing by default)
- Enable tipping without funds ("adding to shopping cart")
- Give me full visibility into where my money is going (audit log)

## Tipping is not a big deal

It is the opposite of a big deal.

And it should be treated that way. Don't cover half my screen with a banner and
offer me to tweet and everything. Just get out of the way as soon as possible
so I can do it again.

Ideally, when I tip, the BAT triangle on the address bar (which I'm already
getting trained to glance at to see if a website is a verified publisher)
[unspoofably](https://twitter.com/BrendanEich/status/1132330327618117632) does
a little dance (like the sub-second Twitter heart animation) and _that's it_.

Tipping is like:

- Liking
- Faving
- Starring
- Clapping
- Upvoting

It's an **impulse** action that satisfies a need for gratitude / reciprocity /
gifting.

People do copy urls and tweet on their own when the situation affords it, no
need to add friction to enable that use case.

If you have to choose between making it easier to **tip again** vs _share the
fact that you tipped_, err on the side of more tipping.

**Let the happy publishers who are watching the
extra-money-due-to-reduced-friction come in be your loudspeaker.**

## _At most_ one action (click or keypress)

Tipping in places that already have their own appreciation / signal-boosting
mechanism should take **zero extra actions** if the user wants it so.

It shouldn't be the default, but I want to set up **action-based
auto-contribute**: "On twitter, by default, tip 1 BAT for every like I give. 10
for every RT."

This on top of the time-spent auto-contribute that already exists. Time-spent
doesn't work for apps with multiple publishers on the same page like Twitter /
Reddit / Hacker News / Stack Overflow.

And no need to indirectly infer intent when the user is making it explicit
already.

## At most _one_ action

Amazon sells high-value _physical goods_ that need shipping address, credit
card, billing information, deciding what kind of shipping you want, etc, etc.
It's a nightmare.

And yet, they go the distance and do eveything in their power to remove all
unnecessary action, avoid all repetition, save every detail _once_ and remove
all anxiety. One-click Ordering(tm) is genius.

Tipping is comparatively trivial and there's no excuse for it to ever take more
than 1 click or keypress.

When setting up the Brave Wallet, the user can define a **browser-wide default
tip amount** which can be changed on individual cases.

When the user changes the default for a specific tip, they can be given the
option to save that amount for future tips either _to that publisher_, on that
platform ("use this amount for every future RT"), or browser-wide.

Be like Bezos. (On this specific context. Do pay your employees well.)

## Forgive me for I have tipped

**Undoability** is the universally tried and true way to remove anxiety and put
the user in control. 30-day money-back guarantee, no questions asked.

Don't ask for confirmation. Let them undo it later.

Asking for confirmation on an impulse action is only going to get an (annoyed)
impulse confirmation. If they are going to think twice at all, they will do it
later when system-2 brain kicks in again.

You can undo a \$40,000.00 Tesla 7 days later. Tipping should be a no-brainer.

## Tipping in space (or, you know, in the developing world)

There is already a monthly queue for recurring tips and auto-contribute. This
can be extended to every kind of tipping.

After I zero-to-one-click tip someone, the tip goes into the queue and by
default stays there until the next monthly cycle.

If I want that transaction to be final sooner, I go to the Rewards screen and
click "send now."

If I change my mind, I click "cancel."

This is a critical enabling factor for allowing defaults safely and removing
obtrusive pre-tipping confirmation dialogs and post-tipping confirmation
banners.

It also enables
**[offline](https://interplanetarygatsby.com/foreword/ "there is such thing as 'online'")
tipping**, which is huge.

Currently, if I'm offline, Brave says my wallet balance is zero, says all tip
amounts are worth about 0.00 USD, and tells me "not enough tokens, please add
funds" when I try to tip even though I have a full wallet.

**Always-enqueue solves for anxiety, user control, and
[#asyncUX](https://twitter.com/search?q=%23asyncux 'asynchronous user experience')
all at once.**

## Tipping without funds

Oh yeah, another win for queues: I don't have to have funds to tip. I can go
around tipping, maybe get a little warning when funds run out, but keep
enqueueing tips nonetheless.

When I look at my rewards screen, I see **how much I need to add to my wallet
for pending tips to go through**. That is a very good incentive to fill up!

It's like adding books to a wishlist or items to a cart. You can figure it out
later.

## Full (private) transparency

I want to see a log of every tip to every publisher ever, regardless of whether
it came from deliberate tipping, time-spent auto-contribute, action-based
auto-contribute. Ideally, I can see a snapshot of what the tab looked like when
I did it, how many BATs I gave, how much they were worth in USD at the time,
etc., etc.

---

That's all I have to say about that :)

## PS: I want Brave to succeed

And I think some of these things could help. I don't have the full picture and
I'm probably wrong about some things, but if you made it this far I'm very
grateful for your time and for taking these thoughts into consideration.
