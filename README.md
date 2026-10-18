# Odyssey Neo G9 thermistor (P301)

**Open the page: https://ivanifchen.github.io/odyssey-neo-g9-thermistor/**

This page is for people fixing the black-screen fault on a Samsung Odyssey Neo G9 who watched the repair videos and found that their T-con board does not match.

The videos show the original G9 T-con, where the thermistor THA1 sits on a slotted tab in the upper-left corner. Most Neo G9s use a newer T-con, printed `OSCAR_T_TCON_MNT` and `BN41-02934A`. On that board the thermistor is P301. It is in the top-right corner, just below the tape strip, directly above the gold `CN703` pad. It is the leftmost of four tiny parts and the only one with no printed code.

The page has a to-scale drawing of the whole board, a close-up photo with the part marked, and the steps to find it.

Once removed, P301 reads about 28 to 33 kΩ, not the 10 kΩ of THA1. Removing it permanently disables the T-con's overheat cutoff. Among owners who named this board, removal fixed 6 of 14 monitors.

## Credits

- [u/OccasionalBrat](https://www.reddit.com/r/AskElectronics/comments/1dyi62v/comment/lv5uecq/) posted the P301 photo and [pointed out that it is under tape](https://www.reddit.com/r/AskElectronics/comments/1dyi62v/comment/mavnzxl/).
- [u/Sblombliz](https://www.reddit.com/r/Monitors/comments/1o26wio/) photographed the BN95-08081A sticker that tied this board to the Neo G9.
- [u/alphanimal](https://www.reddit.com/r/AskElectronics/comments/1dyi62v/) published the original THA1 removal.
- [u/East_Development_126](https://www.reddit.com/r/ultrawidemasterrace/comments/17lqe5e/comment/k88fr5b/) first traced the fault to the thermistor.
- [danieljbk](https://github.com/danieljbk/samsung-odyssey-g9-black-screen) collected all of it in one report ([initial version, 6 October 2026](https://github.com/danieljbk/samsung-odyssey-g9-black-screen/tree/42f718f1f37c9ec7e443d149e312ebaff20cace8)).
