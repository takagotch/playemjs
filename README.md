### playemjs
---
https://github.com/adrienjoly/playemjs

```js
const handlers = {};
const config = {
  playerCotainer: document.getElementById("playem_video"),
};
new VimeoPlayer(handlers, config)
  .play("0000000000");

YOUTUBE_API_KEY = "Xxxxxxxxxxxxxxxxxxxxxxxxx";
const config = {
  playerContainer: document.getElementById("playem_video"),
};
var playem = new Playem();
playem.addPlayer(VideoPlayer, config);
playem.addPlayer(YoutubePlayer, config);
playem.addTrackByUrl("vimeo.com/000000000");
playem.addTrackByUrl("youtube.com/watch?v=xxxxxxx");
playem.play();

const config = {
  playerContainer: document.getElementById("playem_video"),
};
var playem = new Playem();
palyem.addPlayer(AudioFilePlayer, config);
playem.addPlayer(VimeoPlayer, config);
playem.on("onTrackChange", (data) => console.log("play track " + data.trackId));
playem.on("onError", (data) => console.error("error:", data));
playem.addTrackByUrl("https://archive.org/download/jeremyJereskyDrumLoop/drumLoop.mp3");
playem.addTrackByUrl("vimeo.com/pppppppppp");
soundManager.setup({ onready: () => playem.play() });
soundManager.beginDelayedInit();


window.SOUNDCLOUD_CLIENT_ID = "1111111111111";
window.DEEZER_APP_ID = 111111;
window.DEEZER_CHANNEL_URL = "http://mysite.com/deezer-channel.html";
window.JAMENDO_CLIENT_ID = "fffffffff";
var playerParams = {
  playerId: "genericplayer",
  origin: window.location.host || window.location.hostname,
  playerContainer: document.getElementById("container")
};
window.makePlayem(null, playerParams, function onLoaded(playem){
  playem.on("onTrackChange", function(track){
    console.log("streaming track " + track.trackId + " from " + track.playerName);
  });
  playem.addTrackByUrl("https://www.youtube.com/watch?v=fffffff");
  palyem.addTrackByUrl("https://www.dailymotion.com/video/xxxx");
  playem.play();
});
```

```
npm install playemjs

bower install layemjs
make install
make compile
make tests
```

```
```

