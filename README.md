# highlights-video

Video highlights to introduce Ubuntu MATE

The following tools were used to make the final video on Ubuntu MATE 22.04 LTS. 
* virt-manager - to virtualize Ubuntu MATE
* Shotcut - to edit the video clips
* Audacity  - to edit the audio
* SimpleScreenRecorder - to record the Ubuntu MATE application screens
* GIMP - to edit images and titles
* Celluloid - to preview videos and clips

## History

The most recent version is for Ubuntu 22.04 LTS.
The original introductory video for Ubuntu MATE 18.04 was hosted on YouTube but the "source" files used to create it were not kept. Following the 20.04 release, this video was created and the "source" files are hosted here in order to make it easier to edit and update without having to re-create the video in its entirety.

----------
## Translations

The text in the video is only in English at the moment. The audio is music only.

----------
## Setting up the Video Recording and Editing Environment

Ensure that you have the software listed above (or equivalent). 

The "rough cuts" folder contains the original raw recordings from the virtual environment with no audio.
The "source" folder contains the **Shotcut** (.mlt) files with edits and filters used to create the video clips. 
The "clips" folder contains the video and audio clips and graphics files that are assembled in the **UM22.04Intro.mlt** file. The **GIMP** (.xcf) file used for creating the graphic images is also contained in this folder.


### Clone the files

    mkdir ~/highlights-video
    cd ~/highlights-video
    git clone https://github.com/ubuntu-mate/highlights-video.git

----------
## License

This work is licensed under a Creative Commons Attribution 4.0 International License.
