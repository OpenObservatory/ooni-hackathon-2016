# OONI Hackathon 2016

Interested in exploring (and exposing) internet censorship? Join the Open
Observatory of Network Interference (OONI) hackathon in Berlin!

**When?**
Friday, 11th November & Saturday, 12th November 2016

**Where?**
The OnionSpace (Gottschedstraße 4, 13357 Berlin, Germany)

**What time?**
10 AM onwards

On this page you can see some of the projects that you could pick up to hack
on, but feel free to pick also something else!

# Projects

## Add support for testing reachability of Tor bridges

Speak to: @hellais
Difficulty: easy-medium
Languages: python

Tor bridges are used by people to circumvent censorship in places where tor is
blocked. Currently there are tests as part of ooniprobe that support testing
tor bridges, but they are not run automatically.

As a first step in doing this it would be neat to just extend the current tor
test deck to also test for reachability of some set of Tor bridges (using the
ooniprobe `tcp_connect` test) see:
[ooni-probe/652](https://github.com/TheTorProject/ooni-probe/issues/652)

## Integrate tor related date into tor metrics

Speak to: karsten, @hellais
Difficulty: easy-medium
Languages: java, python

Some data that is being collected by OONI is related to the tor network and it
would be useful to have it integrated inside of [tor
metrics](https://metrics.torproject.org). In particular it would be useful to
export all `vanilla_tor` test results in a way that is ingestible by tor
metrics or write a layer of integration of it inside of the metrics data
pipeline.

See: [ooni-pipeline/13](https://github.com/TheTorProject/ooni-pipeline/issues/13)

# Useful information

There is a local copy of all the OONI reports in case you want to download them
and use them during the hackathon.
It can be accessed via:

XXX fill me in
