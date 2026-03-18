# Softwalk Brand Site

이 저장소는 **Softwalk** 플랫폼과 프로그램을 소개하는 브랜드 사이트를 GitHub Pages + Jekyll 로 퍼블리싱하기 위해 만들어졌습니다.

* **docs/** 폴더 아래에 사이트용 Markdown 페이지가 위치합니다.
* **_config.yml** 파일에서 사이트 설정과 원격 테마를 정의합니다.
* 루트 README 는 저장소 설명 및 로컬 개발 방법을 안내합니다.

## 로컬 미리보기

```bash
bundle install
bundle exec jekyll serve --baseurl "" --watch
```

브라우저에서 <http://localhost:4000> 을 열면 변경 사항을 바로 확인할 수 있습니다.
