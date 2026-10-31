# feintech-sw411-firmware
A reverse engineered, custom firmware for the Feintech SW411 HDMI switch.

**AI disclosure:** This project was primarily worked on with Fable 5.1

## What is this about?

The FeinTech SW411 is an HDMI 2.1 switcher (4 inputs, 1 output) that supports 8K@60Hz and 4K@120Hz video with advanced features like VRR, ALLM, and Dolby Vision. It also acts as an audio extractor featuring dedicated HDMI Audio-Only, Toslink, and 3.5mm AUX outputs, plus full eARC/ARC pass-through for formats like Dolby Atmos.

While the device is well designed and the hardware is very capable, the firmware is (in my opinion) not. There are quite some bugs that can lead to annoying issues in some setups. While Feintech was very helpful and tried to provide fixed firmwares to me, they ultimately did never work as intended. I understand that small companies don't have limitless resources to spend on such things, so I fully understood and respected when one day, they told me they can't do anything more for me. I asked for the source code / SDK to work on it by myself, which was not possible for them to provide. Nevertheless, their customer service was very good and friendly, so no offense intended. They are a great company.

So there I was, with a OK-working setup but still bugged by the occasional issues. Luckily, I got my hands on unlimited Fable 5.1 access. I never had done a reverse engineering project using AI, so I figured this was a perfect, advanced use case to try it. I had some experience with reverse engineering firmwares, but to be totally honest: this project went over my head on day 1 when it comes to complexity. If I did this manually, it would have taken me 2+ years. Using Fable 5.1, it took me 10 days for a first working basic firmware, 14 days for feature parity and 18 days for a firmware that works better than the original and has additional features.

The token cost spent on this project exceeded 12k €.

## The source code and build instructions will be provided soon.
