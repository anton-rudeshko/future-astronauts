# Future Astronauts

A collection of handcrafted [CUE sheets][cue] for the [Future Astronauts Episodes][fa].

[cue]: https://en.wikipedia.org/wiki/Cue_sheet_(computing)
[fa]: https://futureastronauts.net

## Podcast (Soular Order)

[![Future Astronauts Podcast Banner]][cn-podcast]

[On CueNation][cn-podcast].

[Future Astronauts Podcast Banner]: ./cuenation-banners/Future-Astronauts-Podcast.jpg
[cn-podcast]: http://cuenation.com/?page=cues&folder=futureastronautspodcast

## Horizons (100 day delay)

[![Future Astronauts Horizons Banner]][cn-horizons]

[On CueNation][cn-horizons].

[Future Astronauts Horizons Banner]: ./cuenation-banners/Future-Astronauts-Horizons.jpg
[cn-horizons]: http://cuenation.com/?page=cues&folder=futureastronautshorizons

## Transmissions (Orloe)

[![Future Astronauts Transmissions Banner]][cn-transmissions]

[On CueNation][cn-transmissions].

[Future Astronauts Transmissions Banner]: ./cuenation-banners/Future-Astronauts-Transmissions.jpg
[cn-transmissions]: http://cuenation.com/?page=cues&folder=futureastronautstransmissions

---

Images were optimized via cmdline:

```console
$ fd .jpg -x jpegtran -copy none -optimize -outfile {.}_opt.jpg {.}.jpg
```

* [`fd`](https://github.com/sharkdp/fd)
* [`jpegtran`](https://en.wikipedia.org/wiki/Libjpeg)