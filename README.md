# YT-SH
select videos from yt channels file; watch or download

## Dependencies 
- `mpv`
- `yt-dlp`

## Install
- get the script

```sh 
wget https://raw.githubusercontent.com/felipepegoraro/yt-sh/main/ytsh
chmod +x ytsh
```

- modify the `subscriptions` file:

```sh 
url="https://www.youtube.com/c/"
path="/videos"
echo "${ulr}channel_name_here${path}   # channel name..." > ~/.subscriptions
```

- find some help!

```sh 
./ytsh --help
```

## Examples 
```shell
./ytsh -u -s -5
./ytsh -s -k -v
./ytsh -u -s -d
```
