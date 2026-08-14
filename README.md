# AEO 보고서 (정적 페이지)

`index.html` 한 장이 전부다. 외부 파일을 하나도 안 부른다(폰트·CSS 내장).

**여기서 직접 고치지 마라.** 정본은 Dropbox 의 md 다.

```
0.2_vibe/AEO project/분석_AEO원리와_마롱커버리지_20260814.md   ← 정본
python3 _tools/aeomd2html.py <정본> --out index.html          ← 이걸로 다시 만든다
```

md 를 고치고 위 명령을 돌린 뒤 커밋하면 페이지가 갱신된다.
