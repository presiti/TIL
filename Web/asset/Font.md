# Font

글꼴은 사이트의 내용이나, 분야에 따라 더 깔끔하거나 개성이 드러나는 글꼴을 적용해서 분위기를 조성하는 요소 중 하나예요. 다양한 글꼴을 이용해서 사이트를 꾸미기 위해서 어떻게 글꼴을 적용할지 상황에 따라 적절히 선택해야해요. 글꼴을 적용하는 방식에서 차이가

## Tpye of font

### Local font

이름의 local처럼 현재 사이트를 개발하는 내 PC나 배포할 서버 컴퓨터에 설치되어서 웹사이트에 포함되어 있는 글꼴을 'local font'라고 합니다. 이 방식을 사용하고자 한다면 개발자는 자신의 사이트에 사용한 폰트를 사이트를 배포한 서버에도 동일하게 설치해서 사용할 수 있어요.

### Web font

local font와 달리 설치하지 않고 url을 통해 다운로드해서 화면에 표시하는 글꼴입니다. Naver, Google에서 제공하는 글꼴을 사용할 때 사용자가 자신의 컴퓨터에 직접 설치하지 않고도 사용하는 글꼴을 말해요.

두 종류의 각각의 특징을 아래와 같이 정리할 수 있죠.

- `글꼴 선택의 폭`  
   Local font - 다양한 종류의 글꼴을 사용할 수 있어요.
  Web font - 지원하는 글꼴은 적어서 종류가 제한적이에요.

- `네트워크 부하 감소`  
   Local font - 외부 서버에서 폰트를 다운로드하는 부하를 감소할 수 있어요.
  Web font - 폰트가 필요한 웹사이트에 일괄적으로 로드 되기에 여러 사이트에 걸쳐 중복 다운로드를 방지하여 네트워크 대역폭을 효율적으로 사용해요.

- Local font  
   `로딩 속도` - 서버에서 직접 불러오기 때문에 초기 로딩 속도가 빨라요.  
   `특정 글꼴만 포함 가능` - 필요한 글꼴만 포함시켜 사용하면 효율적으로 리소스를 관리할 수 있어요.
- Web font
  `캐싱과 브라우저 최적화` - 적절한 캐싱과 브라우저 최적화고 효율적으로 관리할 수 있어요.
  `모바일 최적화` - 모바일 환경에도 최적화되어 더 빠르게 로드할 수 있어요.

> 참고자료  
> https://velog.io/@s0zzang/성능최적화-웹폰트-최적화-가이드
