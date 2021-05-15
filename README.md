`slicing-copy-copy.lua` is a Lua script which is forked from [snylonue/mpv_slicing_copy](https://github.com/snylonue/mpv_slicing_copy) which is a lua script forked from [Kagami/mpv_slicing](https://github.com/Kagami/mpv_slicing).
The script is for mpv to cut fragments of the video and reencodes copies everything including fonts and also maybe reencodes them idk

#### Usage

Make sure you have FFmpeg installed. Put `slicing_copy_copy.lua` to `~/.config/mpv/scripts/` or `~/.mpv/scripts/` directory to autoload the script or load it manually with `--script=<path>`.

Press `c` first time to mark the start of the fragment. Press it again to mark the end of the fragment and write it to the disk. Press `C` to clear the fragment. Press `a` to toggle audio capturing (default on).

Logs can be found in console (press `~` to open and `esc` to close by default), which might contains something useful.

You could change key bindings and all parameters of the output video by editing your `input.conf` and `script-opts/slicing_copy.conf`, see [slicing_copy.lua](slicing_copy.lua) and [mpv manual](https://mpv.io/manual/master/#lua-scripting-on-update]]\)) for details.

#### Limitation

If `--merge-files` is passed to mpv, the script won't work.

something lame was here idc

#### License

mpv_slicing_copy_copy - Cut video fragments with mpv

Written in 2015 by Kagami Hiiragi <kagami@genshiken.org>

Modified in 2019 by Snylonue <snylonue@gmail.com>

dm4uz3 modified slightly to their liking hehehe :3

To the extent possible under law, the author(s) have dedicated all copyright and related and neighboring rights to this software to the public domain worldwide. This software is distributed without any warranty.

You should have received a copy of the CC0 Public Domain Dedication along with this software. If not, see <http://creativecommons.org/publicdomain/zero/1.0/>.
