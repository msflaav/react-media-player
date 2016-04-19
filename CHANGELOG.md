## CHANGELOG
### 0.3.3
Fixed seekbar not updating while scrubbing

Fixed range inputs showing full progress on initial load

Now checks if `onChange` is used in Seekbar and Volume components

Patched Youtube not getting proper duration when loading a new video

Reset duration when loading a new Youtube video

### 0.3.2
Allow better styling of `SeekBar` and `Volume` controls by passing background-size. Specifically for styling back fill color in Chrome

Workaround for [know bug](https://github.com/facebook/react/issues/554) with input ranges in <= IE11

### 0.3.1
Fixes bad reference to main file in package.json

### 0.3.0
Added `vendor` prop to allow explicitly choosing which component to render for the player. Useful for cases where we can't determine what type of file is trying to be played.

### 0.2.0
Complete rewrite, better API, use of context in place of spreading props.