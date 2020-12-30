# thinkpad-l13-yoga-hackintosh
Trying to get macOS Big Sur to run on a i7-10510U Thinkpad L13 (Yoga)

## Working

- OpenCore is booting

## Not Working

- anything else

I'm currently stuck at ```AAPL: [EB|#LOG:EXITBS:START]```

It seems to be related to there not being a bios-option to disable cfg-block and the associated kernel-parameters not working on comet lake CPUs.
There currently is no solution to get macOS to run on a Thinkpad with a CometLake CP
See: https://github.com/bomdurup/x1c7_2020_hacintosh
And: https://www.hackintosh-forum.de/forum/thread/48908-lenovo-thinkpad-e15-ist-der-laptop-hackintosh-tauglich-fazit-nein-ist-es-nicht/?pageNo=2 (german)
