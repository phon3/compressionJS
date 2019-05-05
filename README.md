# compressionJS

#### Simple use of lz-string.js library to compress a string.


You can simply open the index.html in any web browser.

 - copy paste your HTML page, Thesis Paper, or other Document into the "Original" text area. 
 - then press the "Compress Code!" button to watch the magic.

Huffman encoding is based on the principle that letters that appear more frequently should have a smaller code than the ones that are used less often. So, in the English language, vowels would be used more than the letter 'z', and would get shorter codes. This javascript-based compression example uses this method to compress whatever you give it. It can work on web pages, javascript code, and tons more. The downfall is that it is extremely slow. It also re-encodes the binary data in a method similar to UUEncode, which inflates 3 bytes of binary data to 4 bytes of textual data, so some of the awesome compression that is possible will be eliminated from the expansion of data.