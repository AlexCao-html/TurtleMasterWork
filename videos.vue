<template>
  <h1>Videos</h1>
   <section class="Videos">
    <a href="javscript:;" id="Given-video">Click on the one below that you want to learn about</a>

    <p id="Chosen-Video">I want to...</p>
    <a onclick="
    video$ = document.getElementById('Given-video');
    c$video = document.getElementById('Chosen-Video');
    video$.setAttribute('href', 'https://www.youtube.com/watch?v=n6QwnzbRUyA');
    video$.setAttribute('target', '_blank');
    c$video.innerHTML += 'learn about soap vs covid.';
    ">...learn how to lower your risk of getting covid.</a><br/>
    <a onclick="
    video$ = document.getElementById('Given-video');
    c$video = document.getElementById('Chosen-Video');
    video$.setAttribute('href', 'https://www.youtube.com/watch?v=FVIGhz3uwuQ');
    video$.setAttribute('target', '_blank');
    c$video.innerHTML += 'learn covid vs the flu.';
    ">...learn covid vs the flu.</a><br/>
    <a onclick="
    video$ = document.getElementById('Given-video');
    c$video = document.getElementById('Chosen-Video');
    video$.setAttribute('href', 'https://www.youtube.com/watch?v=r6ewlQs8CAQ');
    video$.setAttribute('target', '_blank');
    c$video.innerHTML += 'learn what the US did wrong about testing covid.';
    ">...learn what the US did wrong about testing covid.</a><br/>
    <a onclick="
    video = document.getElementById('Given-video');
    c$video = document.getElementById('Chosen-Video');
    video.setAttribute('href', 'https://www.youtube.com/watch?v=-LKVUarhtvE');
    video.setAttribute('target', '_blank');
    c$video.innerHTML += 'learn about soap vs covid.';
    ">...learn about soap vs covid.</a><br/>
<!--      -->
    <a onclick="
    video = document.getElementById('Given-video');
    c$video = document.getElementById('Chosen-Video');
    video.setAttribute('href', 'https://www.youtube.com/watch?v=O-3Mlj3MQ_Q');
    video.setAttribute('target', '_blank');
    c$video.innerHTML += 'learn about covid charts misleading us.';
    ">...learn about covid charts misleading us.</a><br/>
    <a onclick="
    video = document.getElementById('Given-video');
    c$video = document.getElementById('Chosen-Video');
    video.setAttribute('href', 'https://www.youtube.com/watch?v=421fmflQX0E');
    video.setAttribute('target', '_blank');
    c$video.innerHTML += 'learn about the look of covid.';
    " href="" target="_blank">...learn about the look of covid.</a><br/>
    <a onclick="
    video = document.getElementById('Given-video');
    c$video = document.getElementById('Chosen-Video');
    video.setAttribute('href', 'https://www.youtube.com/watch?v=v_kq8_Z4LXQ');
    video.setAttribute('target', '_blank');
    c$video.innerHTML += 'learn about soap vs covid.';
    ">...learn about the symptoms</a><br/>
    <a onclick="
    video = document.getElementById('Given-video');
    c$video = document.getElementById('Chosen-Video');
    video.removeAttribute('href');
    video.removeAttribute('target');
    c$video.innerHTML = '';
    ">？</a>
  </section>
</template>
<script>
</script>
<style>
  a{
    display: block;
    text-decoration: none;
    color: #8080ff;
    transition: all 0.3s cubic-bezier(0.93, 0.43, 0.66, 0.29);
    -webkit-transition: all 0.3s cubic-bezier(0.93, 0.43, 0.66, 0.29);
    -moz-transition: all 0.3s cubic-bezier(0.93, 0.43, 0.66, 0.29);
    -o-transition: all 0.3s cubic-bezier(0.93, 0.43, 0.66, 0.29);
    -ms-transition: all 0.3s cubic-bezier(0.93, 0.43, 0.66, 0.29);
    background-color: #000;
    margin: 5px;
    padding: 1vh 1vw;
    border-radius: 25%;
    -webkit-border-radius: 25%;
    -moz-border-radius: 25%;
    -o-border-radius: 25%;
    -ms-border-radius: 25%;
  }

  a#Given-Video

  a:hover{
    color: #bfbfff;
    border-radius: 0;
    -webkit-border-radius: 0;
    -moz-border-radius: 0;
    -o-border-radius: 0;
    -ms-border-radius: 0;
  }
</style>
