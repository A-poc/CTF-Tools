CTF-Tools
---------------

*Collection of tools I use to solve CTF challenges.*

---------------
# Table of Contents

1. [OSINT](#osint)
    - Reverse Image Search (*Tineye*)
    - Face Search Engine (*Pimeyes*)
    - Image Search (*Baidu*)
    - Image Search (*Google Lens*)
2. [Steganography](#steganography)
    - Steghide
    - Binwalk
    - Foremost
    - Exiftool
    - StegoVeritas
3. [Barcode](#barcode)
    - Barcode Reader (*Inlite*)
    - Barcode Reader (*Aspose*)
10. [Misc](#misc)
    - Disposable Email (*TempMail*)

---------------

OSINT
====================

* [Reverse Image Search - Tineye](https://tineye.com/)

	Online tool for reverse searching an image.
  
  	![Screenshot_9](https://user-images.githubusercontent.com/100603074/158078956-f168d6be-f410-4a84-89d8-04ceade7c3f2.jpg)


* [Face Search Engine - Pimeyes](https://pimeyes.com/)

	Online tool to finding a person from an image.
  
  	![Screenshot_1](https://user-images.githubusercontent.com/100603074/158078970-29fc9381-5dd4-43cd-bccb-825ba40a81af.jpg)

  
* [Image Search - Baidu](https://image.baidu.com/)

	Good search engine for similar image search.
  
  	![Screenshot_2](https://user-images.githubusercontent.com/100603074/158078987-79050066-976b-47a0-8a62-46734adef8b3.jpg)


* [Image Search - Google Lens](https://lens.google/)

	Search tool for finding similar images.
  
  	![Screenshot_3](https://user-images.githubusercontent.com/100603074/158079207-1fc47b73-6d45-4e00-a20a-22ea85c0fcad.jpg)


Steganography
====================

* [Steghide](https://www.kali.org/tools/steghide/)

	Tool for viewing and extracting hidden data from files.
  
  	`steghide info file` : displays info about whether a file has embedded data or not.
  
  	`steghide extract -sf file [--passphrase password]` : extracts embedded data from a file [using a password].
  
  	![Screenshot_5](https://user-images.githubusercontent.com/100603074/158079780-c9f88efe-0b06-4845-b988-919dab07015f.jpg)


* [Binwalk](https://www.kali.org/tools/binwalk/)
  
  	Tool for viewing and extracting hidden data from files.
  
	`binwalk file` : Displays the embedded data in the given file.
  
  	`binwalk -e file` : Displays and extracts the data from the given file.
  
  	`binwalk --dd ".*" file` : Displays and extracts the data from the given file.
  
  	![Screenshot_4](https://user-images.githubusercontent.com/100603074/158079711-8e67816f-36b0-46e8-a1c9-f820e4568beb.jpg)


* [Foremost](https://www.exiftool.org/)

	Tool for extracting hidden data from files.
  
	`foremost -i file` : extracts data from the given file.

	![Screenshot_10](https://user-images.githubusercontent.com/100603074/158080315-9b716ba8-0b0e-48f6-9e3b-09559ce40482.jpg)

  
* [Exiftool](https://www.exiftool.org/)

	Tool for viewing file metadata.
  
  	`exiftool file` : shows the metadata of the given file.

  	![Screenshot_6](https://user-images.githubusercontent.com/100603074/158080117-fbfc5353-6f91-49dd-a90d-fe14ce60b9e6.jpg)


* [StegoVeritas](https://github.com/bannsec/stegoVeritas)

	Spray and pray stego tool.
	
	Install with `pip3 install stegoveritas`
	
	`stegoveritas file` : attempts all stego modules on the file.
	
	![Screenshot_11](https://user-images.githubusercontent.com/100603074/158081013-a83c9f46-458e-4d72-9072-39c26d761827.jpg)


Barcode
====================

* [Barcode reader - Inline](https://online-barcode-reader.inliteresearch.com/)

	Good online barcode scanner. Can scan 1D: Code 39, Code 128, PDF417, Postal, QR code, DataMatrix, Driver License, ID cards.

  	![Screenshot_7](https://user-images.githubusercontent.com/100603074/158078594-fd4660cf-7226-4701-a74d-29a7f78d0d76.jpg)
  
* [Barcode reader - Aspose](https://products.aspose.app/barcode/scan#/nocamera)

	Another good online barcode scanner. Can identify wide range of barcodes.
  
  	![Screenshot_8](https://user-images.githubusercontent.com/100603074/158078705-5ac842db-d33b-435c-b7a3-3a68f2444143.jpg)
  
  
Misc
====================

* [Disposable Email - TempMail](https://temp-mail.org/en/)

	Nice service that lets you access a temporary email account. Good for quickly creating fake accounts for website access.

  	![Screenshot_12](https://user-images.githubusercontent.com/100603074/158081735-5f9c54b0-68bc-43f5-8c82-74e72847189d.jpg)

