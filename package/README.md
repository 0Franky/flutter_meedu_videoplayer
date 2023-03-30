# flutter_meedu_videoplayer

### Cross-platform video player
- For Android, Ios and Web we are using video player
- For Windows and Linux and macos we are using media_kit.
<table>
  <caption><h4>Demo</h4></caption>
  <tbody>
    <tr>
      <td rowspan="2"><img src="https://zezo357.github.io/flutter_meedu_videoplayer/assets/q2.gif" alt="meedu_player" width="160" /></td>     
      <td><img src="https://zezo357.github.io/flutter_meedu_videoplayer/assets/full.gif" alt="meedu_player" width="300" /></td>      
    </tr>   
    <tr>
      <td><img src="https://zezo357.github.io/flutter_meedu_videoplayer/assets/playing_video.png" alt="meedu_player" width="300" /></td>     
    </tr>  
  </tbody>
</table>


| Features  | iOS | Android | windows | linux | macos | web|
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Videos from Network  | ✅  | ✅ | ✅ | ✅ | ✅ | ✅|
| Videos from Assets  | ✅  | ✅ | ✅ | ✅ | ✅ | ✅|
| Videos from local files  | ✅  | ✅ | ✅ | ✅ | ✅ | ✅
| Looping  | ✅  | ✅ | x | x | x | x
| AutoPlay  | ✅  | ✅ | ✅ | ✅ | ✅ | ✅
| Swipe to increase and decrease Sound  | ✅  | ✅ | keyboard arrows | keyboard arrows | ✅ | keyboard arrows |
| Swipe to seek in video | ✅  | ✅ | keyboard arrows | keyboard arrows | ✅ | keyboard arrows |
| FullScreen  | ✅  | ✅ | ✅ | ✅ | ✅ | ✅ |
| Launch Player as FullScreen  | ✅  | ✅ | ✅ | ✅ | ✅ | ✅ |
| Playback Speed  | ✅  | ✅ | ✅ | ✅ | ✅ | ✅ |
| fastForward / Rewind  | ✅  | ✅ | ✅ | ✅ | ✅ | ✅ |
| srt subtitles  | ✅  | ✅ | x | x | x | x
| Customize  | partially  | partially | partially | partially | x | partially

---



## Initialize
```dart
void main() {
  initMeeduPlayer();
  runApp(MyApp());
}
```


# Setup

### Windows

Everything ready.

### Linux

System shared libraries from distribution specific user-installed packages are used by-default. You can install these as follows.

#### Ubuntu / Debian

```bash
sudo apt install libmpv-dev mpv
```

#### Packaging

There are other ways to bundle these within your app package e.g. within Snap or Flatpak. Few examples:

- [Celluloid](https://github.com/celluloid-player/celluloid/blob/master/flatpak/io.github.celluloid_player.Celluloid.json)
- [VidCutter](https://github.com/ozmartian/vidcutter/tree/master/_packaging)

### macOS

Everything ready.




👋 👉 <b>[Complete documentation here](https://zezo357.github.io/flutter_meedu_videoplayer/)</b>



