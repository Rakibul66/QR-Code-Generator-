# QR Code Generator 
 QR Code Generator using HTML, CSS and jQuery
 
 A QR code generator is an application that stores any required textual data into a QR code which can be later scanned with a QR code scanner to reveal the stored information. This QR Code can be used anywhere, for example, on a poster or website to allow users to get additional information. This application will allow the user to type in the data required and save it a PNG or SVG image of the QR code. 

Approach: To generate the QR code, we will use the Google Charts API. Using jQuery, the QR code image to be displayed is updated according to the image returned by the API.

The API endpoint that would be used is given below.

https://chart.googleapis.com/chart?chs=150×150&cht=qr&chl=Hello%20world

Explanation of the URL:

The root URL for Google Chart Infographics is https://chart.googleapis.com/chart. This can be specified with the required parameters to ger the desired output.
The chs parameter denotes the size of the QR code image in pixels.
The cht parameter denotes the type of the image to be created. The value “qr” will be used to generate a QR Code.
The chl parameter denotes the text or URL data to be encoded in the QR code.
