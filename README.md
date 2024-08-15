# Stick2Video

![Screenshot of Stick2Video app](https://github.com/redjacketKR/Stick2Video/raw/main/Stick2Video_vFtLRvsMsY.png)


# Summary of Stick2Video Improvements

Several significant improvements have been made to the Stick2Video application. Here's a summary of the key enhancements:

1. **FFmpeg Integration**
   - Replaced OpenCV video writing with FFmpeg for improved video encoding capabilities.
   - Added checks to locate FFmpeg in multiple directories (system PATH, _internal folder, file folder).
   - Updated the PyInstaller spec file to include FFmpeg in the bundled application.

2. **CSV Data Processing**
   - Improved CSV reading to handle different file formats (Betaflight, Rotorflight, Cleanflight).
   - Enhanced data normalization for stick positions to ensure consistent scaling across different input ranges.

3. **Video Codec Support**
   - Expanded codec options, including various ProRes formats, H.264, HEVC, and more.
   - Implemented platform-specific codec handling for better compatibility on macOS and Windows.

4. **Frame Processing Improvements**
   - Enhanced frame blending with alpha channel support for smoother transitions.
   - Implemented a more robust method for determining color order in frames (RGBA vs BGRA).

5. **User Interface Enhancements**
   - Added a codec selection dropdown in the UI for users to choose their preferred video format.
   - Improved progress tracking and display during video generation.

6. **Error Handling and Logging**
   - Implemented more comprehensive error logging throughout the application.
   - Added debug print statements to help with troubleshooting, especially for FFmpeg path detection.

7. **Performance Optimizations**
   - Implemented more efficient frame sampling for video creation, reducing processing time for longer flights.

8. **About Box Updates**
   - Updated the 'About' section to include information about newly integrated libraries and tools, including FFmpeg.

9. **Build Process Improvements**
   - Updated the PyInstaller spec file to include necessary dependencies and assets, ensuring a more complete standalone application.

10. **Cross-Platform Compatibility**
    - Made adjustments to ensure better compatibility across different operating systems, particularly for macOS and Windows.

These improvements have significantly enhanced the functionality, performance, and user experience of the Stick2Video application. The integration of FFmpeg, in particular, has greatly improved the video encoding capabilities, while the expanded codec support provides users with more flexibility in output formats. The enhanced error handling and logging will make troubleshooting easier, and the optimized processing should result in faster video generation, especially for longer flight logs.

----
Stick Movement to Video Generator v1.0 - RC1

# Stick2Video 개선 사항 요약

Stick2Video 애플리케이션에 여러 중요한 개선을 이루었습니다. 주요 개선 사항은 다음과 같습니다:

1. **FFmpeg 통합**
   - 향상된 비디오 인코딩 기능을 위해 OpenCV 비디오 쓰기를 FFmpeg으로 대체했습니다.
   - 여러 디렉토리(시스템 PATH, _internal 폴더, file 폴더)에서 FFmpeg을 찾는 검사를 추가했습니다.
   - 번들 애플리케이션에 FFmpeg을 포함하도록 PyInstaller 스펙 파일을 업데이트했습니다.

2. **CSV 데이터 처리**
   - 다양한 파일 형식(Betaflight, Rotorflight, Cleanflight)을 처리할 수 있도록 CSV 읽기를 개선했습니다.
   - 다양한 입력 범위에서 일관된 스케일링을 보장하기 위해 스틱 위치에 대한 데이터 정규화를 개선했습니다.

3. **비디오 코덱 지원**
   - 다양한 ProRes 형식, H.264, HEVC 등을 포함한 코덱 옵션을 확장했습니다.
   - macOS와 Windows에서 더 나은 호환성을 위해 플랫폼별 코덱 처리를 구현했습니다.

4. **프레임 처리 개선**
   - 더 부드러운 전환을 위해 알파 채널 지원으로 프레임 블렌딩을 개선했습니다.
   - 프레임의 색상 순서(RGBA vs BGRA)를 결정하는 더 강력한 방법을 구현했습니다.

5. **사용자 인터페이스 개선**
   - 사용자가 선호하는 비디오 형식을 선택할 수 있도록 UI에 코덱 선택 드롭다운을 추가했습니다.
   - 비디오 생성 중 진행 상황 추적 및 표시를 개선했습니다.

6. **오류 처리 및 로깅**
   - 애플리케이션 전반에 걸쳐 더 포괄적인 오류 로깅을 구현했습니다.
   - 특히 FFmpeg 경로 감지를 위한 디버그 출력문을 추가하여 문제 해결에 도움을 주었습니다.

7. **성능 최적화**
   - 비디오 생성을 위한 더 효율적인 프레임 샘플링을 구현하여 긴 비행에 대한 처리 시간을 줄였습니다.

8. **정보 창 업데이트**
   - FFmpeg을 포함한 새로 통합된 라이브러리 및 도구에 대한 정보를 포함하도록 '정보' 섹션을 업데이트했습니다.

9. **빌드 프로세스 개선**
   - 필요한 종속성과 자산을 포함하도록 PyInstaller 스펙 파일을 업데이트하여 더 완전한 독립 실행형 애플리케이션을 보장했습니다.

10. **크로스 플랫폼 호환성**
    - 특히 macOS와 Windows에서 더 나은 호환성을 보장하기 위해 조정을 했습니다.

이러한 개선 사항들은 Stick2Video 애플리케이션의 기능성, 성능 및 사용자 경험을 크게 향상시켰습니다. 특히 FFmpeg의 통합은 비디오 인코딩 기능을 크게 개선했으며, 확장된 코덱 지원은 사용자에게 출력 형식에 대한 더 많은 유연성을 제공합니다. 향상된 오류 처리 및 로깅은 문제 해결을 더 쉽게 만들어주며, 최적화된 처리는 특히 긴 비행 로그에 대해 더 빠른 비디오 생성을 가능하게 합니다.




