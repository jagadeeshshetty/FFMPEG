# FFMPEG
FFMPEG command usage

# Rotate video
$ ffmpeg -i input_file -vf transpose_parameter output_file

Ex:
$ ffmpeg -i in.mov -vf "transpose=1" out.mov

For the transpose parameter you can pass:
0 = 90CounterCLockwise and Vertical Flip (default)
1 = 90Clockwise
2 = 90CounterClockwise
3 = 90Clockwise and Vertical Flip
