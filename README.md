
# Video Streaming Apllication

Video Upload and HLS Conversion API
This is a Node.js API built using Express and Multer that allows users to upload videos and converts them to HLS (HTTP Live Streaming) format using FFmpeg. The app is designed for serving video content in chunks, enabling better streaming performance.


## Deployment

To run this project run

```bash
  npm run start
```


## Features


- Video Upload: Supports uploading of video files through a POST request.
- Multer: Manages file uploads and saves them in the ./uploads folder.
-  Unique File Names: Generates unique file names for each upload using uuid.
-  HLS Conversion: Uses FFmpeg to convert uploaded videos into HLS format for efficient streaming.
-  Cross-Origin Resource Sharing (CORS): Allows access from specified front-end domains.



## Authors

- [Rahul Shaw](https://github.com/RahulKGEC)


## Installation

Install my-project with npm

```bash
  npm init -y
  npm i cors express multer uuid
  Visit the official FFmpeg website: https://ffmpeg.org/download.html
```
    
