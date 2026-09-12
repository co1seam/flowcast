# Vision

I don't yet know what this will turn into. I'm starting with what's interesting and seeing where it goes.

It's a small service for short clips — up to 3 minutes, 720p. You upload a video, it gets transcoded and segmented, it plays in the browser with adaptive streaming, and the system collects viewing data. That's it.

Uploading and watching is easy. The part in between — and the part after — is where it gets messy. That's what interests me most.

Transcoding, segmenting, adaptive bitrate switching, buffering, playback. And somewhere in all of that, someone wants to know how many people actually watched, for how long, and whether any of it worked. The streaming side and the analytics side rarely talk to each other in a way that makes either easy to trust.

This project isn't a platform or a startup. It isn't meant to scale and isn't meant for your videos. The constraints are deliberate — they keep the problem small enough to hold in your head. Bigger would be a different project.

There's no code yet. Just the shape of the system being written down and a list of questions worth answering.

