WebP Express 0.15.3. Conversion triggered using bulk conversion, 2019-09-24 06:00:15

*WebP Convert 2.1.4*  ignited.
- PHP version: 7.3.1
- Server software: Apache

Stack converter ignited

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/gourl/images/_img48.png
- destination: [doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/gourl/images/_img48.png.webp
- log-call-arguments: true
- converters: (array of 9 items)

The following options have not been explicitly set, so using the following defaults:
- converter-options: (empty array)
- shuffle: false
- preferred-converters: (empty array)
- extra-converters: (empty array)

The following options were supplied and are passed on to the converters in the stack:
- alpha-quality: 80
- encoding: "auto"
- metadata: "none"
- near-lossless: 60
- quality: 85
------------


*Trying: cwebp* 

Options:
------------
The following options have been set explicitly. Note: it is the resulting options after merging down the "jpeg" and "png" options and any converter-prefixed options.
- source: [doc-root]/wp-content/uploads/gourl/images/_img48.png
- destination: [doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/gourl/images/_img48.png.webp
- alpha-quality: 80
- encoding: "auto"
- low-memory: true
- log-call-arguments: true
- metadata: "none"
- method: 6
- near-lossless: 60
- quality: 85
- use-nice: true
- command-line-options: ""
- try-common-system-paths: true
- try-supplied-binary-for-os: true

The following options have not been explicitly set, so using the following defaults:
- auto-filter: false
- default-quality: 85
- max-quality: 85
- preset: "none"
- size-in-percentage: null (not set)
- skip: false
- rel-path-to-precompiled-binaries: *****
------------

Encoding is set to auto - converting to both lossless and lossy and selecting the smallest file

Converting to lossy
Locating cwebp binaries
1 cwebp binaries found in common system locations
Checking if we have a supplied binary for OS: Darwin... We do.
We in fact have 1
A total of 2 cwebp binaries where found
Detecting versions of the cwebp binaries found (and verifying that they can be executed in the process)
Executing: /usr/local/bin/cwebp -version. Result: version: 1.0.3
Executing: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12 -version
Exec failed (the cwebp binary was not found at path: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12)
Trying executing the cwebs found until success. Starting with the ones with highest version number.
Creating command line options for version: 1.0.3
Quality: 85. 
The near-lossless option ignored for lossy
Trying to convert by executing the following command:
nice /usr/local/bin/cwebp -metadata none -q 85 -alpha_q '80' -m 6 -low_memory '[doc-root]/wp-content/uploads/gourl/images/_img48.png' -o '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/gourl/images/_img48.png.webp.lossy.webp' 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/gourl/images/_img48.png.webp.lossy.webp'
File:      [doc-root]/wp-content/uploads/gourl/images/_img48.png
Dimension: 256 x 256 (with alpha)
Output:    5060 bytes Y-U-V-All-PSNR 45.59 52.68 53.60   46.98 dB
           (0.62 bpp)
block count:  intra4:        100  (39.06%)
              intra16:       156  (60.94%)
              skipped:        73  (28.52%)
bytes used:  header:            115  (2.3%)
             mode-partition:    515  (10.2%)
             transparency:     1014 (65.6 dB)
 Residuals bytes  |segment 1|segment 2|segment 3|segment 4|  total
  intra4-coeffs:  |    2531 |      10 |       0 |      48 |    2589  (51.2%)
 intra16-coeffs:  |     310 |       6 |       0 |     100 |     416  (8.2%)
  chroma coeffs:  |     190 |      15 |       0 |     151 |     356  (7.0%)
    macroblocks:  |      70%|       1%|       0%|      29%|     256
      quantizer:  |      17 |      13 |      10 |       8 |
   filter level:  |      40 |       3 |       2 |       0 |
------------------+---------+---------+---------+---------+-----------------
 segments total:  |    3031 |      31 |       0 |     299 |    3361  (66.4%)
Lossless-alpha compressed size: 1013 bytes
  * Header size: 79 bytes, image data size: 934
  * Precision Bits: histogram=3 transform=3 cache=0
  * Palette size:   85

Success
Reduction: 81% (went from 27 kb to 5 kb)

Converting to lossless
Locating cwebp binaries
1 cwebp binaries found in common system locations
Checking if we have a supplied binary for OS: Darwin... We do.
We in fact have 1
A total of 2 cwebp binaries where found
Detecting versions of the cwebp binaries found (and verifying that they can be executed in the process)
Executing: /usr/local/bin/cwebp -version. Result: version: 1.0.3
Executing: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12 -version
Exec failed (the cwebp binary was not found at path: [doc-root]/wp-content/plugins/webp-express/vendor/rosell-dk/webp-convert/src/Convert/Converters/Binaries/cwebp-mac12)
Trying executing the cwebs found until success. Starting with the ones with highest version number.
Creating command line options for version: 1.0.3
Trying to convert by executing the following command:
nice /usr/local/bin/cwebp -metadata none -q 85 -alpha_q '80' -near_lossless 60 -m 6 -low_memory '[doc-root]/wp-content/uploads/gourl/images/_img48.png' -o '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/gourl/images/_img48.png.webp.lossless.webp' 2>&1

*Output:* 
Saving file '[doc-root]/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/gourl/images/_img48.png.webp.lossless.webp'
File:      [doc-root]/wp-content/uploads/gourl/images/_img48.png
Dimension: 256 x 256
Output:    12806 bytes (1.56 bpp)
Lossless-ARGB compressed size: 12806 bytes
  * Header size: 858 bytes, image data size: 11923
  * Lossless features used: PREDICTION CROSS-COLOR-TRANSFORM SUBTRACT-GREEN
  * Precision Bits: histogram=3 transform=3 cache=6

Success
Reduction: 53% (went from 27 kb to 13 kb)

Picking lossy
cwebp succeeded :)

Converted image in 219 ms, reducing file size with 81% (went from 27 kb to 5 kb)
