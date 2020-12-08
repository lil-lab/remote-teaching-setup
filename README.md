# Remote Teaching Setup - Spring 2021

This document is inspired by Sasha Rush's [setup document](https://github.com/srush/VirtualTeaching) and follows up on my [Spring 2020 setup post](). The setup is inspired by Sasha Rush and Harald Haraldsson.

## Constraints

- Interactive teaching.
- Very small space.
- Moderate budget.

## Equipment

- Webcam: [Logitech Brio](https://www.logitech.com/en-us/product/brio)
- Webcam arm: [Flexible gooseneck Tripod](https://www.amazon.com/Webcam-Scissor-Adjustable-Flexible-gooseneck/dp/B08B5GSS7Z/)
- Microphone: [Blue Yeti Nano](https://www.bluemic.com/en-us/products/yeti-nano/)
- Headphones: [Bose Headphones 700](https://www.bose.com/en_us/products/headphones/noise_cancelling_headphones/noise-cancelling-headphones-700.html) (wired connection to mic)
- OBS control: [Elgato Stream Deck Mini](https://www.elgato.com/en/gaming/stream-deck-mini)
- Light: [Elgato Key Light Air](https://www.elgato.com/en/gaming/key-light-air)
- Green screen: [Angler PortaScreen (Chroma Green)](https://www.bhphotovideo.com/c/product/1502655-REG/angler_pbb_cg57_background_porta_screen_chroma.html?fromDisList=y)
- Laptop: Macbook Pro 13''
- External monitor: Dell 27''
- Two iPads

Overall cost is likely slightly $600-700, except items that I already had like headphones, display, iPads and laptop.

<img src="teaching-space.png" width=600px>

## Streaming

I stream the class via Zoom, which also takes care of the recording. I use [OBS](https://obsproject.com/) to produce the video. OBS is not as optimized for Mac as it is for Windows/Linux, so I had to tinker with it to get it to run properly. I found restricting the webcam and output resolutions to be the most important tweak. The BRIO can go up to 4K, which looks, but is not streamable via Zoom, so doesn't really matter.

I experimented with several options to pipe OBS output into Zoom, including screen sharing and using OBS' virtual camera either as the main camera or a secondary camera. Screen sharing has high resolution but low frame rate. The choppy output seems too cognitively tiring. Sharing as a secondary camera also gave high resolution, but at the price of very high CPU usage and relatively low frame rate. I ended up using the virtual camera as my main camera.

You will need to set the output resolution in OBS to something reasonable, ideally as high as your Zoom is likely to transmit. You can view Zoom transmission statistics in its settings window. You will also need to add a chroma filter to get the green screen working. This works well with good lighting. I find the Key Light Air sufficient for good-to-low light conditions, but chroma quality suffers with near-to-complete darkness.

The Stream Deck switches between pre-programmed scenes in OBS.
