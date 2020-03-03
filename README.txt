               **** STATUSD [pending imminent rename] ****
                        a social media backplane

STATUSD is the /spiritual successor/ to Rustodon, a project with a very
constricting name. over the course of many conversations with ashkitten,
ninjawedding, cosine, and puckipedia, i've gradually decided that Rustodon was a
project which, while exploring new territory at the time, didn't ultimately
follow my goals as a designer. it offered some fun engineering challenges,
but they were ultimately sidelining the original goal: offering a fediverse
software which implicitly acknowledged users' ability to shape their own world.

*to effectively decentralize*, we must allow users to diversify. *to form a
federation* as a feasible alternative to the financial and technical barriers
of /full decentralization/ as in SSB, we must allow inhabitants of nodes
to shape their world independent of administrators, in the way that Wikipedia
userpages and Tumblr themes have fostered blossoming spaces.

USER AGENTS are tools that interface you with their VIRTUAL WORLD,
speaking to the SERVER, the host of that world, on their behalf. in
long-standing tradition, the USER AGENT is your browser, while the SERVER
contains the entirety of the VIRTUAL WORLD. for instance, browsing Tumblr, one
server – or cluster of servers – is the entire world, while your browser simply
talks to them.

however, when using mastodon or other fediverse software, your browser's
standing as the USER AGENT is shared with the mastodon frontend; it interfaces
with the world of the fediverse on your behalf. nor does the SERVER play a
typical role; the SERVER is only a shard of the VIRTUAL WORLD you might be
exploring, even as it valiantly struggles to maintain the appearance of a
coherent whole by fetching data from other SERVERS.

maintaining this illusion is a core tenet of many FEDIVERSE SERVICES. this is
where STATUSD diverges; it does not try to be your USER AGENT, actively
*divesting itself* of responsibility for presenting content. it instead focuses
on integrating itself smoothly into a constellation of servers and sharing
data cleanly and efficiently. STATUSD itself is an affordance for accessing the
VIRTUAL WORLD, not a way to display it.
