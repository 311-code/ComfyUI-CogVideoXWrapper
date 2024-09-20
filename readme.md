This repo is for testing. Added CogVideo Dualtextencode. I have noticed it adds a lot more movement to the image to video with CogVideoXFun. It was just merged into Kijai main branch so try it out there instead https://github.com/kijai/ComfyUI-CogVideoXWrapper

Example here: https://github.com/kijai/ComfyUI-CogVideoXWrapper/pull/61

Findings: It seems to add movement even when using only using a single t5 text encoder, but you can also add dual clip loader to load in t5 with clip_l and control the strength.

https://github.com/user-attachments/assets/7b39eef0-8ee4-4b2a-b22c-415a76f45576

Here was the juggernaut x init image from the workflow:

![jugx_init_image](https://github.com/user-attachments/assets/34d5ea4e-015a-4646-a299-f7bc9dfdcb89)

Workflow to test it out here:

[cog_video_dual_clip_gorilla.json](https://github.com/user-attachments/files/17050172/cog_video_dual_clip_gorilla.json)
