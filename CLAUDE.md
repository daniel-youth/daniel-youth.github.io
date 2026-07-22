# 다니엘 청년부 수련회 사이트

## 이미지 등록 규칙

### PDF 홍보물 추가 시
PDF 파일은 모바일 브라우저에서 인라인 표시가 되지 않으므로, 반드시 PNG로 변환한 뒤 등록한다.

**변환 명령어 (macOS 기본 내장, 별도 설치 불필요):**
```bash
sips -s format png 파일명.pdf --out 파일명.png
```

**예시:**
```bash
sips -s format png honbo2.pdf --out honbo2.png
```

변환 후 원본 PDF는 삭제해도 무방하다. HTML에서는 `.png` 파일을 참조한다.