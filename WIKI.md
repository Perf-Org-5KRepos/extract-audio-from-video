# Short Title

Extract audio from video

# Long Title

Extract audio from video and store it in cloud object storage


# Author
* [Manoj Jahgirdar](https://www.linkedin.com/in/manoj-jahgirdar-6b5b33142/)
* [Manjula Hosurmath](https://www.linkedin.com/in/manjula-g-hosurmath-0b47031)

# URLs

### Github repo

* https://github.com/IBM/convert-video-to-audio/


### Video Link
* https://youtu.be/zbhDULZGJEE

# Summary

In this code pattern, Given a video recording of the virtual meeting or a virtual classroom, we extract the audio from the video and store it in IBM Cloud Object Storage.

# Technologies

* [Python](https://developer.ibm.com/technologies/python): An open-source interpreted high-level programming language for general-purpose programming.

* [Object Storage](https://developer.ibm.com/technologies/object-storage): Store large amounts of data in a highly scalable manner.

# Description

As part of the series which extracts insights from virtual meetings or classrooms, the very first step is to extract audio from video and store it in a common accessible storage space.  In this code pattern, we will consider a video recording of a meeting, extract audio from that video file using open source library FFMPEG in a python flask runtime. FFMPEG is a complete, cross-platform solution to record, convert and stream audio and video. Lastly, we will store the extracted audio in IBM Cloud Object Storage. IBM Cloud Object Storage is a highly scalable cloud storage service, designed for high durability, resiliency and security. The stored audio files will be used for further processing to provide speaker diarization in the next code pattern of the series.

Refer this link for complete details of the series: <https://developer.ibm.com/articles/text-mining-and-analysis-from-webex-recordings>

# Flow

<!--add an image in this path-->
![architecture](doc/source/images/architecture.png)

1. User uploads video file to the application.

2. The [FFMPEG](https://www.ffmpeg.org/) library extracts the audio from the video.

3. The extracted audio file is stored in Cloud Object Storage.

# Instructions

> Find the detailed steps in the [README](https://github.com/IBM/convert-video-to-audio/blob/master/README.md) file.


1. Clone the repo

2. Create Cloud Object Storage Service

3. Add the Credentials to the Application

4. Deploy the Application

5. Run the Application

# Components and services

* [Object Storage](https://cloud.ibm.com/catalog/services/cloud-object-storage): IBM Cloud Object Storage is a highly scalable cloud storage service, designed for high durability, resiliency and security. Store, manage and access your data via our self-service portal and RESTful APIs. Connect applications directly to Cloud Object Storage use other IBM Cloud Services with your data.
