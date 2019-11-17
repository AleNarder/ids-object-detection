# Object recognition model builder

## DESCRIPTION
A simple linux environment to produce useful .tflite models that can be integrated into an existing android application 

## PREREQUISITES
1. A linux environment
2. vitualenv installed locally

## ENVIRONMENT SETUP
1. From root directory, open terminal and run: <code>virtualenv env</code>
2. Activate virtual environment, with command: <code>source env/bin/activate</code>
3. <code>pip3 install tensorflow = 1.9.*</code>

## INSTRUCTIONS

1. Make a video to the object you intend to recognize
2. Save that video in videos dir -> (video has to be in .mp4 format)
3. From videos directory, open terminal and run: <code>./mp4_2_jpeg {video-name}</code> 
4. From root directory, open build script with your favourite editor and change the default parameters in order to satisfy your needs
5. From root directory, open terminal and run: <code>./build</code> 

