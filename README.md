# python-cv2-aztec-extraction
A helper script to find and extract Aztec code from image. Used alongside Zxing improves "detectability" of large(r) codes based on [AnonimowiAnalitycy/Z3SBarcodeScanner](https://github.com/AnonimowiAnalitycy/Z3SBarcodeScanner).

* Dirty implementation in 4 hours
* Tested 15 times on small sample of codes
  - car registration certificates ([what these folks charge serious buck for](https://www.dekoderaztec.pl/))
  - train tickets
  - small product codes (google "Aztec sample")
* Silly, but works™

## Demo

This is based on an image found [here](https://kurier-kolejowy.pl/aktualnosci/20554/konduktor-pkp-ic-naliczyl-zbyt-wysoka-cene-za-bilet.html).

| Image | 
|-|
|![](demo/in.jpg)|
|![](demo/s1.jpg)|
|![](demo/s2.jpg)|
|![](demo/out.jpg)|
