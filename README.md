# Future Astronauts

A collection of handcrafted [CUE sheets][cue] for the [Future Astronauts Episodes][fa].

[cue]: https://en.wikipedia.org/wiki/Cue_sheet_(computing)
[fa]: https://futureastronauts.net

## Podcast (Soular Order)

[![Future Astronauts Podcast Banner]][cn-podcast]

[On CueNation][cn-podcast].

* [#139](https://git.io/JvqMb)
* [#144](https://git.io/JvqMF)
* [#145](https://git.io/JvqMd)
* [#146](https://git.io/JvsYn)
* [#147](https://git.io/Jv8vF)

[Future Astronauts Podcast Banner]: ./cuenation-banners/Future-Astronauts-Podcast.jpg
[cn-podcast]: http://cuenation.com/?page=cues&folder=futureastronautspodcast

## Horizons (100 day delay)

[![Future Astronauts Horizons Banner]][cn-horizons]

[On CueNation][cn-horizons].

[Future Astronauts Horizons Banner]: ./cuenation-banners/Future-Astronauts-Horizons.jpg
[cn-horizons]: http://cuenation.com/?page=cues&folder=futureastronautshorizons

* [#054](https://git.io/JvqM5)
* [#055](https://git.io/JvqMi)
* [#056](https://git.io/JvqMo)
* [#057](https://git.io/Jvckl)
* [#058](https://git.io/JvEtZ)

## Transmissions (Orloe)

[![Future Astronauts Transmissions Banner]][cn-transmissions]

[On CueNation][cn-transmissions].

* #001
* #002
* [#003](https://www.patreon.com/posts/future-003-33614453) (comment on the Patreon page)

[Future Astronauts Transmissions Banner]: ./cuenation-banners/Future-Astronauts-Transmissions.jpg
[cn-transmissions]: http://cuenation.com/?page=cues&folder=futureastronautstransmissions

---

Images were optimized via cmdline:

```console
$ fd .jpg -x jpegtran -copy none -optimize -outfile {.}_opt.jpg {.}.jpg
```

* [`fd`](https://github.com/sharkdp/fd)
* [`jpegtran`](https://en.wikipedia.org/wiki/Libjpeg)