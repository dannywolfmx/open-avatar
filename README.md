# open-avatar

It's a simple proyect to animate an image when you speek to your microphone, just need to open the "microfono.html" with your browser and it will works.

# OBS Setup

You can use it with the browser feature in OBS but by default it will not activate the microphone capabilities, so you need to use a flag when you run the OBS like this:

```
obs --use-fake-ui-for-media-stream
```

or in flatpak
```
flatpak run com.obsproject.Studio --use-fake-ui-for-media-stream
```
