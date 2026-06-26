+++
title = "Shortcodes and Media"
date = 2017-03-11
+++

Shortcodes should cover the practical stuff.
No component empire.
No fake widget gallery.
Just enough markup to avoid repeating yourself.

{{ quote(text="The page should read first and style second.", author="Theme note") }}

{{ details(summary="What this page demonstrates", text="Figure, audio, video, quote, sup, sub, and details are enough for a compact theme.") }}

{{ figure(src="/logo.svg", alt="Theme logo", caption="A local SVG beats a remote dependency.", loading="lazy") }}

{{ audio(src="/media/sample.ogg", mime="audio/ogg", caption="Local audio sample", fallback="download audio") }}

{{ video(src="/media/sample.mp4", mime="video/mp4", caption="Local video sample", fallback="download video") }}

Superscript and subscript are tiny helpers, but they keep technical text readable.

X{{ sup(body="2") }} and H{{ sub(body="2") }}O
