# [98-CaptureCameraStorage](https://github.com/molab-itp/98-CaptureCameraStorage)

```
# Browsing Your Photos
2022-12-17 JHT: Truely bizarre -  
this code is extracted from 
https://developer.apple.com/tutorials/sample-apps/capturingphotos-browsephotos
which is download as CapturingPhotos.swiftpm
which can be openned in xcode or swift playground app.
link [View a tutorial on this sample.] appears to only make sense in swift playground
I added [tutorial] which opens useless xcode browser link preview

>> example has deep logic that is only skimmed over in tutorial
>> needed to add Info.plist in xcode to allow for camera and photo library access
>> not sure how to do this via "Signing & Capabilities"

## Plan:

[] upload to thumb to FireBase
[] album name in UI 
  DataModel / photoCollection / PhotoCollection(albumNamed: "Dice" ...

## Log

>> private func unpackPhoto
modify to use cgImageRepresentation() to control resolution of image

Not sure how to get rid of entitlements file

>> on iphone13 photo capture test:
      print("photoDimensions", photoDimensions)
      print("previewDimensions", previewDimensions)
photoDimensions CMVideoDimensions(width: 4032, height: 3024)
previewDimensions CMVideoDimensions(width: 852, height: 640)


```

# Browsing Your Photos

Browse the photos in your photo library.

## Overview

Enjoy taking photos? Most of us do, and it’s easy to end up with hundreds or thousands of photos in your library. 🏞

Follow your photos as they’re retrieved from your photo library and displayed in a scrolling gallery you can browse.

## Tutorial

[View a tutorial on this sample.](doc://com.apple.documentation/tutorials/sample-apps/CapturingPhotos-BrowsePhotos)

[tutorial](https://developer.apple.com/tutorials/sample-apps/capturingphotos-browsephotos)

## Running the Sample Code Project

Before running this sample on a physical device, select a Development Team under the Signing & Capabilities section in the project editor.


