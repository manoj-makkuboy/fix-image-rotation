# fix-image-rotation
npm package to rotate the image based on EXIF values stored in the image.

## Install
> $ npm install fix-image-rotation

## Usage
    let fixRotation = require('fix-image-rotation')
    let ArrayOfFilesToBeRotated = [File1, File2]
    let myRotationFunction = async function (ArrayOfFilesToBeRotated) {
      let blobOfArray = await fixRotation.fixRotation(ArrayOfFilesToBeRotated)
      return blobOfArray
    }

