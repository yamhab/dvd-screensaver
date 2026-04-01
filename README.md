# dvd-screensaver

*A DVD screensaver animation program for the terminal using the awesome
[termbox2](https://github.com/termbox/termbox2) library*

![Video demo of the program](demo.gif)

---

I made this mainly as an activity to learn [termbox2](https://github.com/termbox/termbox2) (it's
amazing!), so expect problems (I'd be surprised if anyone uses this, if not sees this). You just run
it and watch, and you can quit by pressing `q`.

---

## Build/Install

To build this, you must have [termbox2](https://github.com/termbox/termbox2) installed and the
Make build system. You should also be sure to have a valid C compiler in `$PATH` that Make can use.

```sh
git clone https://github.com/yamhab/dvd-screensaver.git # Clone the project onto your computer
cd dvd-screensaver # Move into the project directory
make # Build the program
```

The `dvd` executable can then be found in the `build/` directory.
