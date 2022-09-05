# clip-generator
여러 각도에서 동시에 촬영된 mp4 영상들을 선택한 구간의 프레임 만큼 잘라내 새로운 mp4 클립들을 생성하는 프로그램.

## 목차
* 개발 환경
– 버전 정보
* 기능 설명

## 개발 환경
- ### 버전 정보

| 언어 및 툴 | 버전 |
|--|--|
| Tool | Microsoft Visual Studio Community 2019 버전 16.9.3 |
| Framework | .NET Framework 4.7.2 |
| Project Template | Windows Forms 앱(.NET Framework) |
| Language | C# |
| OpenCvSharp4 | 4.5.2.20210404 |
| OpenCvSharp4.runtime.win | 4.5.2.20210404 | 

## 기능 설명 
- ### 썸네일 생성 
현재 프레임을 기준으로 목록의 모든 영상에 썸네일을 생성한다. 

- ### 클립 생성
시작점과 종료점을 기준으로 목록의 모든 영상에 클립을 생성한다.

- ### in put 및 out put 정보
1. fps는 60프레임 영상을 기준으로 한다.
2. .mp4 영상을 대상으로 한다.
3. 코덱은 DivX MPEG-4 코덱을 사용한다. ( FourCC.DIVX )
4. 결과물의 저장 위치는 대상의 위치와 동일하다.
5. 썸네일은 "프레임_영상이름.jpg"의 이름으로 생성된다.
6. 클립은 "시작프레임_종료프레임_영상이름.mp4"의 이름으로 생성된다.
7. 파일 탐색기의 시작 위치는 "d:\"로 되어있다.
