# halflife
[Valvesoftware's halflife repository](https://github.com/ValveSoftware/halflife) only has the bare minimum.

We needed past versions of the sourcecode too, to clearly see which changes were made while doing the mod.

We thought other people could need them too, in a way that allows easier diff/merging to help you update old
code to a more recent codebase.

If you based your code upon the "Multiplayer Source" at or before SDK 2.3, you'll have to carefully merge
your changes to the "Single-Player Source" folder of v2.3 before going further, as "both" are distributed in
the same folder afterwards (they are very similar anyway).

Each SDK listed below has its own tag/release.

# SDK 1.0
Multiplayer Source, copyright "1999, Valve LLC."

# SDK 2.1
Multiplayer Source, copyright "1999, Valve LLC." or "1999, 2000 Valve LLC."

# SDK 2.2
Multiplayer Source, copyright "1996-2001, Valve LLC."

# SDK 2.3
Multiplayer Source + Single-Player Source, copyright "1996-2002, Valve LLC."

# GitHub seed (201308)
Single-Player Source, copyright "1996-2001, Valve LLC." or "1996-2002, Valve LLC." (but still based upon SDK 2.3)

# GitHub master (201906)
Single-Player Source, same as above but with bugfixes and support for Visual C++ 2010 Express

# Future ?
Because the official repository isn't very active, you may find useful to fetch more recent forks or
pull requests, with support for even more recent compilers, like this compatibility PR for
[Visual Studio 2015 and later](https://github.com/ValveSoftware/halflife/pull/1784).

But this particular repository limits itself to official (or Valve-approved) SDK changes, so go find good forks by yourselves.
