

## Allen's tmux foo.


Daniel Crisman (https://github.com/crisman) slipped me a sweet sweet
dose of TMUX, and like a responsible adult, I rolled in it.



### What am I doing?

I'm taking lists of hosts, feeding them into shell scripts that
reformat them so, e.g. a list 8 items long will be arranged into a
tmux grid like so  (evidently you need headers for Github Markdown to
decide to table your tables).


|1|2|
|-|-|
|3|4|
|5|6|
|7|8|


Or maybe like

|1|2|3|4|
|-|-|-|-|
|5|6|7|8|


There are several repositories of lists of hosts in well defined
locations w.r.t. this directory.  You don't care about the lists of
hosts, you just care about what I'm doing with them.


So I've got scripts like '8up' or '8upw' which spit put tmux commands
to SSH to the various named hosts, and they wind up looking rational
when they're done.

I also add a token to each tmux config so it'll get stuck in a
distinct session.  I have two landscape monitors I use for this, so I
have a convention for a '(l)eft' and '(r)ight' iteration for many of
the configs.  I usually have a passel of NMONs in the left side, and a
corresponding grid of shells in the right side.


I'd just like to say that tmux plus xmonad is a whole additional
dimension of tiling.  Thanks.



