# LipSync_listed_assignment
AI model for Lip Synced video with the help of the video and audio as inputs.


1. Run the first cell to Install the dependencies and pretrained model.
2. Follow these instruuctions as a prerequisites for inputs:
   i) Create video file named input_video.mp4 - audio track removed
   ii) Create audio file named input_audio.wav
   iii) Both files have to be exact same length
   iv) Target face in the input_video.mp4, must be "detectable" in ALL videoframes (So no black or blurry frames etc)
   v) Make sure u use correct file extensions
   vi) wav2lip does not like very long and high res clips (1080p/30seconds max)
3. Upload your input files.
4. Run the inference code.
5. Play the result video.
6. Choose to download the result by running the next cell or delete the results by skipping the download and running the next cell.
7. Try out different variations such as :
   i) Introducing a resize_factor: It educes the resolution of the video as lower resolution yeilds a better output.
   ii) More Padding: To include the chin region (You can manually edit pads dimensions viewing and changing the code)
   iii) Scaling the results to 50%
