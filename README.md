# signal-mod-tools
Better group chat vibes

## The Catalyst

**Friend asks:** Wanna be a co admin of $one_of_our_signal_group_thread?

**My reply:** Not especially… but I am interested in building decentralized moderation tools for signal

**Them:** That sounds interesting

## My feeling is signal groups struggle with two possibilities:

Either: a) No one does much moderation — individuals are unclear if others are as bothered, maybe afraid of seeming too controlling — and so one or two people struggle to read the room, send a bunch of non-stop obnoxious messages, the majority of other people build up silent resentment, and the quality of the group vibes falls off hard.

Or: b) one or maybe two people do take it upon themselves to be the room’s (hopefully) benevolent dictator, and decide to call out the obnoxious offenders for their shitty messages. But then sometimes maybe the power goes a little to their head, or they just make questionable decisions that aren’t actually widely supported, kick people because their personal feelings were hurt in an argument, etc.

<p align="center">
<img src="https://github.com/user-attachments/assets/cedbe8ec-b44c-4a55-a196-be91fa586283" />
</p>

Case (A) is like the “wiser” people too full-of-doubt to take unilateral action.

Case (B) is someone decides enough is enough, but ruins the channel with too strong actions, kicking people a little unjustly, which has its own negative chilling effect.

## So, what I’d personally really like is basically two solutions:

1) Easy-to-use ways to give offenders “time-outs”. Not perma kicks, but like:
    > “hey, you can stay in the room to read but refrain from posting anything for ${duration}, or else you’ll be auto-kicked. After ${duration} you can post again like normal and you’ll be invited back if you were kicked.”
    
    Where `$duration` can be escalating times like 10 min, 4 hours, 24 hours, 4 days, 2 weeks, 1 month, 1 year.

2) Ways for group members to cast secret votes, on whether the accused deserves the punishment or not. Secrecy lets people really vote their conscious, not be afraid of the offender getting pissed at them.

With all the rules clearly visible, possibly configurable by admins.

Unfortunately my sense is Signal-the-org is pretty reluctant to add first party support for such tools directly into the app, but I think it’s all still possible to implement with chatbots, then rooms can choose to add the moderation bots whenever they want.

If we could show that it’s a useful addition even in the worse UX of chatbots, it could eventually “graduate” to proper first party support.

It’s basically the millennia long struggle of social group theory, runaway dictatorships, coordination problems, and democratic innovations — like ancient [Athenian Ostracism](https://en.wikipedia.org/wiki/Ostracism) — reinvented for cyberspace

