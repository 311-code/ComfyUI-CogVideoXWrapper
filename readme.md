This repo is for testing. Added CogVideo Dualtextencode. I have noticed it adds a lot more movement to the image to video with CogVideoXFun. It was just merged into Kijai main branch so try it out there instead https://github.com/kijai/ComfyUI-CogVideoXWrapper

Example here: https://github.com/kijai/ComfyUI-CogVideoXWrapper/pull/61

Findings: It seems to add movement even when using only using a single t5 text encoder, but you can also add dual clip loader to load in t5 with clip_l and control the strength.
