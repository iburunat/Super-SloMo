If you want to convert a video from 30fps to 90fps, set fps to 90 and sf to 3 (to get 3x frames than the original video).

python video_to_slomo.py --video video.avi --sf 3 --checkpoint SuperSloMo.ckpt --fps 90 --output output.mkv

Run the following commmand for help / more info: python video_to_slomo.py --h


