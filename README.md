midiarp.lv2 - MIDI arpeggiator
==================================

midiarp.lv2 is a MIDI arpeggiator.

Install
-------

Compiling midiarp requires the LV2 SDK, gnu-make, and a c-compiler.

```bash
  git clone https://github.com/larspelz/midiarp.lv2.git
  cd midiarp.lv2
  make
  sudo make install PREFIX=/usr
```

Note to packagers: The Makefile honors `PREFIX` and `DESTDIR` variables as well
as `CFLAGS`, `LDFLAGS` and `OPTIMIZATIONS` (additions to `CFLAGS`), also
see the first 10 lines of the Makefile.
