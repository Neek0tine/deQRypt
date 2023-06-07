# Optimized QR Code Scanner 
![deQRypt](https://github.com/Neek0tine/deQRypt/blob/main/assets/banner.png)

## Methods

- PCLines
- Hough Spaces
- FRCNN if image is blurry/broken (Not real time)
- Detect format and version information
- Data masking
- Apply the mask patterns and determine which one results in the lowest penalty
- Error correction (Reed solomon / CNN ?)
- Interleave blocks if necessary
- Generate error correction codewords
- Decode the data

## References

- Gao, S. (2003). A new algorithm for decoding Reed-Solomon codes. Communications, information and network security, 55-68.
- https://github.com/pwning/public-writeup/blob/master/mma2015/misc400-qr/writeup.md
- Szentandrási, I., Herout, A., & Dubská, M. (2012). Fast detection and recognition of QR codes in high-resolution images. Proceedings of the 28th Spring Conference on Computer Graphics - SCCG  ’12. doi:10.1145/2448531.2448548 
- Ren, S., He, K., Girshick, R., & Sun, J. (2015). Faster r-cnn: Towards real-time object detection with region proposal networks. Advances in neural information processing systems, 28.
