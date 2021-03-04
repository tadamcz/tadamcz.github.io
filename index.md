---
layout: default
---
<img border="0" src="/images/taphoto.webp" width="300" />

<link rel="stylesheet" href="balloon.min.css">

<link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">

Hi, I'm <span id='name' aria-label="Thomas Maxime Klaus Adamczewski" data-balloon-pos="right">Tom</span>. Here are some links about me.

<style>
#name {
    cursor: default;
    text-decoration-style: dotted;
    text-decoration-line: underline;
}

.material-icons {
    font-size: 1em;
    vertical-align: text-top;
}
</style>


<b>[GitHub](https://github.com/tadamcz) • [blog](https://fragile-credences.github.io/) • [email](mailto:tmkadamcz@gmail.com)</b>

[How to pronounce 'Adamczewski'](javascript:showPronounciationLinks())
<span id="PronounciationLinks" style="display: none"> -- [<span class="material-icons">volume_up</span>Voice 1](javascript:document.getElementById('audio1').play()), [<span class="material-icons">volume_up</span>Voice 2](javascript:document.getElementById('audio2').play())</span> 

<script type="text/javascript">
    function showPronounciationLinks() {
        element = document.getElementById('PronounciationLinks')
        element.style.display = (element.style.display == 'none') ? 'inline-block' : 'none'
    }
</script>

<audio id="audio1">
  <source src="/pronunciation_pl_adamczewski.mp3" type="audio/mpeg">
</audio>

<audio id="audio2">
  <source src="/pronunciation_de_adamczewski.mp3" type="audio/mpeg">
</audio>
