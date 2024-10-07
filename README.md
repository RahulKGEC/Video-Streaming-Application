# Video-Streaming-Application
 FFmpeg  , This is a Node.js API built using Express and Multer that allows users to upload videos and converts them to HLS (HTTP Live Streaming) format using FFmpeg. The app is designed for serving video content in chunks, enabling better streaming performance.
Video Upload and HLS Conversion API
This is a Node.js API built using Express and Multer that allows users to upload videos and converts them to HLS (HTTP Live Streaming) format using FFmpeg. The app is designed for serving video content in chunks, enabling better streaming performance.

Features:
Video Upload: Supports uploading of video files through a POST request.
Multer: Manages file uploads and saves them in the ./uploads folder.
Unique File Names: Generates unique file names for each upload using uuid.
HLS Conversion: Uses FFmpeg to convert uploaded videos into HLS format for efficient streaming.
Cross-Origin Resource Sharing (CORS): Allows access from specified front-end domains.
Static File Serving: Serves uploaded videos from the /uploads directory.
Endpoints:
GET /: Basic health check route returning a welcome message.
POST /upload: Accepts video file uploads and returns the HLS stream URL upon conversion.
How it works:
The user uploads a video file.
The API stores the file and generates a unique lesson ID.
FFmpeg processes the video to HLS format and stores the segments.
The URL for the HLS stream is returned to the client.
