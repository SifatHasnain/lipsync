# LipSync

1. Here Wav2lip has been used for lip sync a video wit desired audio
2. As generated video had very low qualty and face became very blurry, used restoration GAN named GFPGAN

Reference
- https://github.com/zabique/Wav2Lip
- https://github.com/TencentARC/GFPGAN

** ALL THE INSTRUCTIONS ARE INCLUDED IN THE NOTEBOOK

## Quick guide
### Wav2Lip
```
1. Create video file input_video.mp4
2. Create audio file input_audio.wav
3. Both files have to be exact same length
4. Target face in the input_video.mp4, must be in ALL videoframes (So no black or blurry frames etc)
```
### GFP GAN
```
1. Generate frames from output video
2. Run inference
3. Generate video and add audio
```