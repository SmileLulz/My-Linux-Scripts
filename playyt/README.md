# Dependencies

- `playyt` requires `yt-dlp` , `mpv` and `mpv-mpris` to work

- ```
  pip install yt-dlp
  ```
- ```
  sudo dnf install mpv mpv-mpris
  ```

# Usage and Arguments

- Play a song or audio:

  - ```
    playyt song_name
    ```
  - ```
    playyt "song name"
    ```

- Arguments:
  - `-v 30` or `--volume 30`  (set volume; even if audio is already playing)

  - `-s` or `--stop`          (stop playback)

  - `-m` or `--music`         (force search 'music')

  - `-l` or `--loop`          (loop the track)
