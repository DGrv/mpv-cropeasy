## easycrop

A simple mpv script for manually croping and reencoding a video.

Based on [mpv-easycrop](https://github.com/aidanholm/mpv-easycrop).
Based on [mpv-easycrop](https://github.com/aidanholm/mpv-easycrop).
Based on [mpv-easycrop](https://github.com/aidanholm/mpv-easycrop).

- will create a new file 

### Installation

Place `cropeasy.lua` in your `~/.mpv/scripts` or `~/.config/mpv/scripts` directory.

Install ffmpeg:

- via their website
- with chocolatey

```sh
choco install ffmpeg
```

### Usage

Press `C` to begin the cropping. Click at one corner of the desired cropping
rectangle, and click a second time at the opposite corner.

ffmepg will then rename the original video with "_old" suffix and create a new cropped video with the original name

If you wish to use a key other than `C` to blur, the keybind `cropeasy` can be
changed in the lua script:

```sh
mp.add_key_binding("C", "cropeasy", cropeasy_activate)
```

### Example 

**Input:**

![](/assets/input.gif)

**Output:**

![](/assets/output.gif)

### License

GPLv3
