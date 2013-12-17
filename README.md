OCR-iOS-Example
===============

A simple example of how to do optical character recognition (OCR) on iOS.

### About

This was a little project I did one night to see how well OCR performed on the iPhone using Tesseract (an OCR library). Luckily for me, some people have already done the heavy lifting (compliled the libraries for iOS, made wrappers, etc). Here, I've simply brought that all together in project that should have you going with minimal setup.

### Setup

1. Clone this repo.
2. Run the app on your device.
3. It should be able to scan English language characters.


### Updating the language dataset

This repository contains the English language data for Tesseract 3.02, so if you'd like to update to a later version or use another langage, follow the steps below.

1. Go to [https://code.google.com/p/tesseract-ocr/downloads/list](https://code.google.com/p/tesseract-ocr/downloads/list) to download a language dataset.
2. Replace the `tessdata` folder with your decompressed tesseract data:

![image](https://raw.github.com/mstrchrstphr/OCR-iOS-Example/master/images/ocr-ios-screenshot01.png)

 
That's it! The source code shouldn't be too difficult to follow. Feel free to do whatever you like with this.

### Brought to you by

[https://code.google.com/p/tesseract-ocr](https://code.google.com/p/tesseract-ocr)
<br />
[https://github.com/ldiqual/tesseract-ios](https://github.com/ldiqual/tesseract-ios)
<br />
[http://tinsuke.wordpress.com/2011/11/01/how-to-compile-and-use-tesseract-3-01-on-ios-sdk-5](http://tinsuke.wordpress.com/2011/11/01/how-to-compile-and-use-tesseract-3-01-on-ios-sdk-5)


