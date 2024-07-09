## Install

```sh
npm install @zvonokcom/audio-player.js
```

## Usage

```html
<div class="audio ct-audio-player">
    <audio preload="none">
        <source src="..." type="audio/mpeg">
    </audio>
</div>

<script src="audio-player.js"></script>
<script>
    player = new CtPlayer(document.querySelector(".ct-audio-player"));
    player.initPlayer();
</script>
```

## Or with jquery
```js
$('.ct-audio-player').each(function() {
    player = new CtPlayer(this);
    player.initPlayer();
});
```

## Use regions plugin

```js
<script src="audio-player.js"></script>
<script>
    player = new CtPlayer(document.querySelector(".ct-audio-player"), true);
    player.initPlayer();
</script>
```
