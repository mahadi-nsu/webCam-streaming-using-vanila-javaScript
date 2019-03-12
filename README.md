# webCam-streaming-using-vanila-javaScript

The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types.

It returns a Promise that resolves to a MediaStream object. If the user denies permission, or matching media is not available, then the promise is rejected with NotAllowedError or NotFoundError respectively.

Here I have worked with only Webcam audio and vedio that will take permission on the browser and output video or deined upon the user permission.
