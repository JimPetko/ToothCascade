# ToDo

## Make Posiive Result Images
Make images with high contrast background. For tooth images make black background. run sample images through an opencv app to remove all the non-whitish, non-yellowish colored pixels ^1. Image resolution doesnt need to be excessive ~720p.

## Make Sample image processor
Measure criteria for recognitions and make an openCV applicaiton to take images and strip out non-essential data. then save the output in the positiveImageDir.

## Start with a few 100's of images
use a script similar to: 
    
    opencv_createsamples -img cropped00.jpg -bg negativeImageDir/negatives.txt -info sampleImageDir/cropped00.txt -num 128 -maxxangle 0.0 -maxyangle 0.0 -maxzangle 0.3 -bgcolor 255 -bgthresh 8 -w 48 -h 48
