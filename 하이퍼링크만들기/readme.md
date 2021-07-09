1. controls : 플레이어 화면에 컨트롤 바를 표시할때 사용

2. autoplay : 오디오나 비디오를 자동이로 실행할때 사용

3. loop : 오디오나 비디오를 반복재생할때 사용

4. muted : 오디오나 비디오의 소리르 제거할때 사용

5. preload : 페이지를 불러올 때 오디오나 비디오 파일을 어떻게 로딩할것인지 지정합니다. 사용할수 있는 값은 auto, metadata, none입니다. 기본적으로 preload="auto"를 사용

6. width, height : 비디오 플레이어의 너비와 높이를 지정합니다.
                    width, height

7. poster="파일 이름" : 

※ 플레이어 표시 없이 배경 음악 넣기
<audio src="파일 경로" autoplay loop></audio>

※ 비디오 자동 재생하기
<video src="파일 경로" width="동영상크기" autoplay muted loop></video>
                                                   └ 크롬 및 파이어폭스 
                                                   브라우저에서는 음소거를 해야 
                                                   비디오를 자동재생할수 있다