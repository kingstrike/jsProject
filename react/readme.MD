# react 
    -초기 js는 웹브라우저를 대상으로 이벤트/연산/인터렉션 담당하는 단순 스크립트였다.
    -구글 -> 2005(ajax등장) -> 2008(chrome 브라우저 개발 공개) -> VS엔진공개
    -> VS엔진공개 - VS기반으로 js를 구동하는 생태계 생성 : node
    -node기반 / 언어(JavaScript -> TypeScript)
        -웹 어플리케이션, 서버 사이드, 데스크톱 어플리케이션 전방위에 사용됨
        -slack, atom, vscode : electron 기반 데스크톱 어플리케이션 
        -페이스북, 디스코드, 페이팔, 이베이 : 모바일웹앱(ionic, phonegap, titanium, react native(3세대), 플러터(구글 3~4세대/Dart 언어))
        -SPA : 프런트 중심 웹어플리케이션(angalrt, react, vue)
    -react는 전통적인 웹 프레임웤의 아키텍처 MVC(Model View Controller) 
        MWM,MVM, .. 중에서 View에만 집중하는 프레임웤이다. 화면처리속도를 높이는 전략
            -화면상에 갱신되는 부분만 새로 view를 만들어서 대체 
            -렌더링(화면갱신)
                -절차(나중에 기록)
            -react + (나머지 기능:third part 프레임웤/라이브러리)=>node 생태계 지원 
    -프레임웤 : 해당 생태계의 룰에 맞춰서 개발
    -라이브러리 : 일종의 특정 기능을 제공하는 모듈, 나의 룰대로 개발