The antithesis:
## ChatOps

<!-- Note -->
I do want to mention one other thing for balance. There is a complete
alternative framework for distributed teams working together, and it’s
what people refer to as ChatOps.

To the best of my knowledge, the first company to run ChatOps on a
large scale _and talk about it publicly_ was GitHub, [back in
2013](https://youtu.be/NST3u-GjjFw) in a
[RubyFuza](https://www.rubyfuza.org/) talk by [Jesse
Newland](https://twitter.com/jnewland).


### ChatOps characteristics

Everything happens in chat <!-- .element class="fragment" -->

Bots do the heavy lifting <!-- .element class="fragment" -->

<!-- Note -->
If a distributed team operates on a ChatOps basis, the interactive
text chat is where absolutely everything happens. 

* Everyone lives in chat all the time, and all issues, alerts and events are
  piped into the chat.

  Everything is discussed in the chat, and everything is also
  *resolved* in the chat.

* Such a system relies on heavy use of chat bots. For example, if an
  alert lands in the channel, and the discussion then yields that the
  proper fix to the problem is to run a specific Ansible playbook,
  you send an in-chat bot command that kicks off that playbook, and
  then reports its result.

And this is of course very laudable, because it resolves a major issue
with using chat, which is the classic scenario of something being
discussed in a chat, someone else then going away for a bit and then
coming back saying “I fixed it!”, and nobody else actually
understanding what the problem was. 

If you make everything explicit and in-band, in becomes easy, in
principle, to go back to a previously-solved problem that reappears,
and replay the resolution.


### When does ChatOps make sense?

Here’s a hint: It’s called ChatOPS. <!-- .element class="fragment" -->

<!-- Note -->
So can this make sense? Yes, absolutely. Under what circumstances
though? I maintain that this is best suited for when your work tends
to be inherently linear with respect to some dimension. For example,
if your primary job is to keep a system operational versus the linear
passage of _time,_ ChatOps is an excellent approach.

And keeping complex systems operational over time is the definition of

* you guessed it, ops. So ChatOps may be a very suitable communication
  mode for operations, but it’s highly unlikely to be efficient as a
  generic mode of communication across distributed teams.

And even then I posit it’s difficult to get right, since you’ll have
to curb channel sprawl and threading and other things, but’s that’s a
whole ‘nother talk and indeed a talk for another *speaker,* because I
don’t lead an ops team.
