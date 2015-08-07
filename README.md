# StarTrekFortuneCookie
A database of Star Trek quotes for the Unix fortune cookie

I like having my login shell graced with a good Star Trek quote,
and I'm not very fond of the Star Trek fortune cookies that come
pre-installed on most Unix systems.  The one which ships with most
Linux distros is complete and utter shit, consisting of several unfunny
jokes mixed in with a few lame quotes which are neither thought-provoking
nor humorous.   The one that the BSDs use is a lot better, but it's really
short and it only covers the original series (they don't even have any quotes
from the movies!).

This database will surpass both of them by only including quotes (and only good
quotes) from all 6 Star Trek series and all 12 films.  I'll even include quotes
from the JJ Abrams movies if there's actually anything intelligent in them.

USAGE:
$ make
$ fortune startrek-all

If you're a really cool kid, you'll add this to the end of your bashrc so you
can start every shell session with the captain and his crew:

fortune /path/to/startrek-all
