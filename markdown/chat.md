# Text chat

<!-- Note -->
So. Let’s talk about text chat. These days, that frequently means
[Slack](https://slack.com/), but what I am talking about also and
equally applies to
[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat),
[Mattermost](https://mattermost.com/), [Riot](https://riot.im/), and 
anything similar.

Is text chat universally useful? No. Is it universally bad? Not that,
either. There is a very specific type of situation in which text chat
is a good thing:


Use **chat** for collaboration that requires  
**immediate, interactive mutual feedback.**

<!-- Note -->
Using interactive chat is a good idea for the kind of communication
that requires immediate, interactive mutual feedback from two or more
participants. If that is not the case, chat is not a good idea.

This means that the only thing that chat is good for is communication
that is required to be *synchronous,* and remember, in a distributed
team *asychronicity* is the norm. So using interactive chat for
communications needs to be an *exceptional* event for a distributed
team; if it is instead a regular occurrence you’ll make everyone on
the team miserable.

For any interaction that does *not* require feedback that is *both*
immediate and interactive, email, a wiki, or an issue tracker are *far
superior* modes of communication.


The only reason to use **DMs** for collaboration  
is a need for immediate, interactive mutual feedback  
**and confidentiality.**

<!-- Note -->
Using chat direct messages (DMs) as the *default* means of
communication is utterly braindead. In order for a chat DM to be
useful, there is precisely one clearly delineated confluence of events
that must occur:

* You need immediate feedback from the other person,
* you need mutual back-and-forth with the other person,
* you don’t want others to follow the conversation.

I can’t emphasize enough that this combination is perfectly valid —
but it is *exceedingly rare.* If you want just a private exchange of
ideas with someone, encrypted email will do. If you want to work on
something together with one person before you share it with others,
restricted view permissions on a wiki page or an issue tracker ticket
will work just fine.

If you don’t need confidentiality but you do need interactive and
immediate feedback, chances are that you’re working on something
urgent, and it is far more likely you’ll eventually need to poll other
opinions, than that you won’t. So just use a shared channel from the
get-go, that way it’s easier for others to follow the conversation if
needed — and they might be able to point out an incorrect assumption
that one of you has, before you end up chasing a red herring.


#### A chat ping is a shoulder tap.

<!-- Note -->
“Pinging” someone in a chat (that is, mentioning their username, which
usually triggers a visual or auditory notification), is exactly like
walking up to a person, interrupting what they are doing, tapping them
on the shoulder, and asking them a question.

**No matter whether it is your intention or not,** they will feel
compelled to answer, relatively promptly (the only exception is when
you’ve done this so often that you have conditioned your colleagues
to ignore you — congratulations).

This means that you’ve broken their train of thought, yanked them out
of a potentially complex task, forced them to redo what they did
pre-interruption, or actually have them commit a mistake.

So pinging someone in a chat is something you should only do if you
are aware of exactly this risk, *and* you are convinced that whatever
you’re pinging about is more important. Otherwise, to be very blunt,
you’ll be seen as the asshole.


#### Want people to hate you? Send naked pings.

<!-- Note -->
A “naked ping” is the action of sending someone a message consisting
only of their username and a marker like “ping”, “hi”, “hey” or
similar.


```
14:00:02Z johndoe: florian: ping
[...]
15:56:17Z florian: johndoe: I hate you
```
Don’t. Just don’t.

<!-- Note -->
Any person who is versed in the use of chat communications will, when
subjected to this behavior, be inclined to flay you alive. Infinitely
more so if it’s a DM. **Do not do this.**


```
14:00:02Z johndoe: florian: can I get your eyes on PR #1422?
[...]
15:56:17Z florian: johndoe: done! 
                   (was afk for a bit – sick kiddo)
15:56:58Z johndoe: florian: np, ty
```

<!-- Note -->
Instead, always provide context. Always always always. Don’t say “can
I ask you a question, instead, *ask the question.* If something isn’t
urgent, say something like “no urgency.” 

It should be self-evident why this is better than naked pings, but if
to you it is not, then please read [Naked
Pings](https://blogs.gnome.org/markmc/2014/02/20/naked-pings/),
courtesy of Alan Jackson and Mark McLoughlin.
