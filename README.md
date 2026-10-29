# 트렉 매장 환대 키네틱 타이포 영상

30초, 1920×1080, 30fps. [HyperFrames](https://github.com/heygen-com/hyperframes)로 HTML을 렌더링해 만든 모션 그래픽입니다.

- 완성 영상: `trek-welcome.mp4`
- 기획: `STORYLINES.md`(3안), `SPEC.md`(채택한 A안 상세)
- 장면: `compositions/s1-door.html` ~ `s9-end.html`, 루트 `index.html`

## 다시 렌더링

```bash
npx hyperframes preview      # 브라우저 미리보기
npx hyperframes render       # MP4 렌더링
```

Node.js 22 이상과 FFmpeg가 필요합니다.

## 에셋 출처

- 매장 사진: 의뢰인 제공
- 트렉 로고: Wikimedia Commons `2018 Trek logo word mark black.svg`
- 서체: Noto Sans KR (SIL Open Font License)
- 효과음: Pixabay Content License (HyperFrames media-use 번들)
- 배경음악: 없음
