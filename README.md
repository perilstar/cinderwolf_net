[Photography & Graphic Design](https://digiulioem.myportfolio.com) • [GitHub](https://github.com/perilstar) • [Scratch](https://scratch.mit.edu/users/perilstar/) • [Steam](https://steamcommunity.com/id/perilstar/)

## Hi!

I'm Erica, but I also go by the usernames cinder, cinderwolf, peril, and perilstar. You can reach me on Discord by adding `@cinder.wolf`.

Here are some of my projects.

### Raycaster

Originally I created this project in Scratch as a challenge for myself. Then I decided I wanted to add new featues to it and make it more performant, so I re-wrote it in JavaScript. It uses the CPU only in a single thread to do all the rendering, and then throws the result to the GPU for a CRT post-processing shader. Be warned: The code is messy and uncommented as I ported it at a time I already had forgotten what the Scratch code did.

[![Raycaster](/assets/images/view.png)](https://cinderwolf.net/projects/raycaster)

### Time Tracker

This is a time-tracking web app that stores time entries in the browser's local storage. I didn't like how long it took me to enter time on my work's time reporting system, so I made this to compliment it as a sort of scratchpad. At the end of the week, I copy the data from the app to my work's time reporting system. Note: It looks terrible on mobile.

[![Time Tracker](/assets/images/view.png)](https://time-tracker.work)

### Virtual Bubble Wrap

We all get stressed out sometimes. Luckily, I've got a scientifically proven cure for anxiety right here, on this webpage.

[![Virtual Bubble Wrap](/assets/images/view.png)](https://cinderwolf.net/projects/bubblewrap)

### YT5S Bookmark Button

If you're as frustrated as I am with wasting precious milliseconds of your life every time you want to download a youtube video, this small bookmark script will help you.

It executes the following code when you click it:
```javascript
  if (/(\w+\.)*youtube.com/.test(window.location.host)) {
    window.open(`https://yt5s.com/en?q=${encodeURIComponent(window.location)}`, '_blank')
      .focus();
  }
```

[![YT5S Bookmark Button](/assets/images/view.png)](https://cinderwolf.net/projects/yt5s-bookmark-button)

### Easing Function Generator

I wanted a bezier curve easing function generator that output JavaScript code. So I made one!

[![BezierFn](/assets/images/view.png)](https://cinderwolf.net/projects/bezierfn)
