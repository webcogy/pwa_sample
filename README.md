# PWA

#### MixCentro 소스 기준으로 확인

- 원본 소스 : https://github.com/S-ayanide/MixCentro
- 참고1 (원본소스설명) : https://ui.toast.com/weekly-pick/ko_20191007
- 참고2 (React로 프로그레시브 웹 앱(Progressive Web App) 만들기) : https://leonkong.cc/posts/pwa.html

## PWA 특징

- 설치가능
- 구글/앱스토어에서 다운로드 가능해졌음
- 일반 PWA 사이트에 접속시 설치여부를 묻는다
- 캐싱을 통한 오프라인 지원
- 네이티브 기능 일부 접근 (하지만 제한적, 푸시알림은 Android만 가능)

## PWA 되기위한 조건

- 서비스워커
- 앱과 유사한 동작 및 뷰
- Manifest 필요 ( iOS에서는 현재 manifest를 지원하지 않기에 html head 부분에 meta 태그를 이용해 내용을 추가 )
