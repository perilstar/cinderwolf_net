## Hi!

I'm Erica, but I also go by the usernames cinder, cinderwolf, peril, and perilstar.

Here are some of my projects.

### Raycaster

Originally I created this project in Scratch as a challenge for myself. Then I decided I wanted to add new featues to it and make it more performant, so I re-wrote it in JavaScript. It uses the CPU only in a single thread to do all the rendering, and then throws the result to the GPU for a CRT post-processing shader. Be warned: The code is messy and uncommented as I ported it at a time I already had forgotten what the Scratch code did.

[![Raycaster](/assets/images/view.png)](https://cinderwolf.net/projects/raycaster)

### YT1S Bookmark Button

If you're as frustrated as I am with wasting precious milliseconds of your life every time you want to download a youtube video, this small bookmark script will help you.

It executes the following code when you click it:
```javascript
  if (/(\w+\.)*youtube.com/.test(window.location.host)) {
    window.open(`https://yt1s.com/en?q=${encodeURIComponent(window.location)}`, '_blank')
      .focus();
  }
```

[![YT1S Bookmark Button](/assets/images/view.png)](https://cinderwolf.net/projects/yt1s-boomkark-button)