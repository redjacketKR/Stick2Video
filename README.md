# Stick2Video

![Screenshot of Stick2Video app](https://github.com/redjacketKR/Stick2Video/raw/main/python_BtIsA0U0Zx.png)


# Summary of Stick2Video Improvements @24.08.14

Several significant improvements have been made to the Stick2Video application. Here's a summary of the key enhancements:

1. **FFmpeg Integration**
   - Replaced OpenCV video writing with FFmpeg for improved video encoding capabilities.

2. **CSV Data Processing**
   - Improved CSV reading to handle different file formats (Betaflight, Rotorflight, Cleanflight).
   - Enhanced data normalization for stick positions to ensure consistent scaling across different input ranges.

3. **Video Codec Support**
   - Expanded codec options, including various ProRes formats, H.264, HEVC, and more.
   - Implemented platform-specific codec handling for better compatibility on macOS and Windows.

4. **Frame Processing Improvements**
   - Enhanced frame blending with alpha channel support for smoother transitions.

5. **User Interface Enhancements**
   - Added a codec selection dropdown in the UI for users to choose their preferred video format.
   - Improved progress tracking and display during video generation.
   - 
6. **Performance Optimizations**
   - Implemented more efficient frame sampling for video creation, reducing processing time for longer flights.

7. **Cross-Platform Compatibility**
    - Made adjustments to ensure better compatibility across different operating systems, particularly for macOS and Windows.

8. **Automatic base frame color creation
    - Now initial generation of movie with other than black given color will generate the PNGs automatically
      
These improvements have significantly enhanced the functionality, performance, and user experience of the Stick2Video application. The integration of FFmpeg, in particular, has greatly improved the video encoding capabilities, while the expanded codec support provides users with more flexibility in output formats. The enhanced error handling and logging will make troubleshooting easier, and the optimized processing should result in faster video generation, especially for longer flight logs.

Stick Trail has to be corrected -- broken chain due to engine replacement and image handling changed significantly.



