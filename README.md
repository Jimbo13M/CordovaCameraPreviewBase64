# CordovaCameraPreviewBase64

<b>Require Apache Cordova and CordovaCameraPreview (iOS Only)</b>

A simple and light modification made to the excellent and very convenient <a href="https://github.com/mbppower/CordovaCameraPreview">CordovaCameraPreview</a> by <a href="https://github.com/mbppower">mbppower</a> that enables you to get a base64 jpg image in return when a user takes a photo with this plugin.

This modification also prevent the application from adding the photo in the iOS photo library.

To use this, erase the CameraPreview.m file in your cordova project (plugins/com.mbppower.camerapreview/src/ios/) with this <a href="https://github.com/Jimbo13M/CordovaCameraPreviewBase64/blob/master/CameraPreview.m">file</a>.

Take a look on this <a href="https://github.com/Jimbo13M/CordovaCameraPreviewBase64/blob/master/example.html">example script</a> to see how to render the base64 image in your app.

