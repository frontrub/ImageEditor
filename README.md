# ImageEditor
FrontRub Image Editor was a web-based image editing tool that edits your images in several clicks.
# Usage (in JSON)
```
{
  "ImageEditor": {
    "filters": {
      "brightness_object": "selected",
      "saturation": "null",
      "inversion": "null",
      "grayscale": "null",
      "brightness": "50%"
    },
    "rotate": {
      "left": "null",
      "right": "null"
    },
    "flip": {
      "horizontal": "null",
      "vertical": "null"
    },
    "right": {
      "image": "object ImagePreview(object Image)"
    },
    "button": [
      "object ResetFilters",
      "object OpenImage",
      "object SaveImage"
    ]
  }
}
```
