# mencoder

수많은 mov 파일을 이어 붙혀 하나의 영상파일로 만들 때 사용합니다.

설치
```bash
# yum install mencoder
```

오디오 코덱, 비디오 코덱을 그대로 유지하고 영상을 이어 붙히는 명령어 입니다.
회사에서 생성된 각 샷의 .mov 파일을 묶어서 실행할 수 있습니다.

```bash
$ mencoder -oac copy -ovc copy first.0001-0100.mov second.0101-0200.mov -o all.mov
```