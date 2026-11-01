---
layout: default
title: Support
description: Help with setting up and using SteadyPulse on Apple Watch.
---
# SteadyPulse Support

Need a hand? Start here. If your question isn't answered below,
[open an issue on GitHub](https://github.com/johnreine/steadypulse/issues/new)
(a free GitHub account is needed) and we'll get back to you.

New to SteadyPulse? The [How to Use guide]({{ '/guide.html' | relative_url }}) walks
through every screen with large pictures.

## Getting started

1. **Install SteadyPulse** on your iPhone. The watch app installs with it. If it
   doesn't appear on your watch, open the **Watch** app on your iPhone, scroll to
   **Available Apps**, and tap **Install** next to SteadyPulse.
2. **Open SteadyPulse on your Apple Watch** and allow access to **Heart Rate** when
   asked.
3. **Turn on Silent Mode** on your watch (open Control Center and tap the bell) so
   the pulse is a tap you feel, without a sound.
4. **Wear your watch snugly.** SteadyPulse starts by itself: it listens to your heart
   rate for one minute, then begins the pulse.

## Using SteadyPulse

Turn the Digital Crown or swipe up and down to move between pages:

- **Heart rate:** your current heart rate in large numbers. Below it you'll see
  **Listening** with a countdown and your **Average pulse** during the first minute,
  **Variable** and the pulse rate once it's running, **Manual** and the rate in Manual
  mode, **No heart rate** if the watch can't read your heart rate, or **Buzz off** when
  stopped.
- **Start and Stop:** Start Variable begins the pulse paced to your heart rate. Start
  Manual plays a fixed rate you choose. Stop Variable or Stop Manual ends the session.
- **Vibration Type:** the feel of each tap, such as "Strong triple tap" or "Heartbeat:
  firm, then light". When the pulse is stopped, changing this plays a sample.
- **Manual BPM:** the rate used in Manual mode.
- **Variable Offset:** how many beats per minute below your heart rate the pulse sits.
  The default is 5.
- **Variable Min:** the lowest rate the pulse will go. The default is 60.
- **Variable Max:** the highest rate the pulse will go. The default is 120.

## How the pulse rate is set

In Variable mode, SteadyPulse listens for a minute, then sets the pulse to your average
heart rate minus the Variable Offset, kept between the Variable Min and Variable Max.
While it runs, if your average heart rate eases down, the pulse eases down with it. If
your heart rate goes up, the pulse stays where it is.

## Troubleshooting

**No heart rate is showing.**
Make sure your watch is snug on your wrist. On your iPhone, go to **Settings →
Privacy & Security → Health → SteadyPulse** and turn on **Heart Rate**.

**The pulse makes a sound.**
Apple Watch plays a short sound with each tap unless Silent Mode is on. Open Control
Center on your watch and tap the bell.

**SteadyPulse isn't on my watch.**
Open the **Watch** app on your iPhone, scroll to **Available Apps**, and tap
**Install** next to SteadyPulse.

**The pulse keeps going after I lower my wrist.**
That's expected. A session keeps running until you open SteadyPulse and tap **Stop**.
Like a workout, a running session uses more battery than usual.

**What happens when I take my watch off?**
After about 30 seconds without a heart-rate reading, the pulse stops and the screen
shows **No heart rate**. Put the watch back on and SteadyPulse starts listening again
by itself. If the watch stays off for more than 10 minutes, the session ends to save
battery; open SteadyPulse again and it starts by itself.

**I see a "Mind and Body" workout in Health or Fitness.**
SteadyPulse runs each session as a Mind and Body workout so it can read your heart
rate continuously, and saves it to Apple Health. You can delete it in the Health app.

## Requirements

Apple Watch with watchOS 26 or later, paired with an iPhone running iOS 26.5 or later.

## Contact

[Open an issue on GitHub](https://github.com/johnreine/steadypulse/issues/new) with
your question. See also the [privacy policy]({{ '/privacy.html' | relative_url }}).
