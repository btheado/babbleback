# BabbleBack

**BabbleBack** is a web page that continuously captures your audio and video,
then plays it back after a short, configurable delay.  Try it out:
[https://btheado.github.io/babbleback](https://btheado.github.io/babbleback)

## 🕰️ What’s the Idea?

It’s a simple feedback loop: you speak or move, and a moment later, you hear
and see yourself. This quirky tool can be surprisingly fun—and sometimes even a
little mind-bending.

## 📜 Origin Story

Back in 2003, inspired by [this piece from Win Wenger](https://winwenger.com/essays/winsights/part-27/),
I created the original *BabbleBack* using Tcl/Tk: [babbleback.sourceforge.net](https://babbleback.sourceforge.net).
My young daughter loved it.

Later, I got an audio + video version working on Linux with a FireWire camera
using a one-liner command: [Video babbleback machine](https://wiki.tcl-lang.org/page/Video+babbleback+machine)

More background here: [Win Wenger’s Babble Back Invention](https://winwenger.com/resources/inventions/babble-back/)

## 🤖 The Modern Take

Fast forward to today: browsers now support real-time audio and video. I was
curious how well Generative AI could recreate the BabbleBack experience.

Turns out, pretty well! After just three prompts to Claude Sonnet 3.7, I had a
working audio prototype. One more prompt (and a bit of manual troubleshooting
and fixing of a tricky bug), and video support was up and running.

## 🛠️ Built With

- HTML + JavaScript
- MediaDevices API for camera and microphone access
- Generative AI (Claude Sonnet 3.7) for rapid prototyping

