
* Build amazing things

https://www.npmjs.com/
 

        npm i react-slick  --force
        npm i react-slide-toggle --force
        npm i echarts-for-react  --force
        npm i react-dnd  --force
        npm i react-slide-toggle  --force
        npm i react-tooltip  --force
        npm i react-device-detect  --force
        npm i semantic-ui-react  --force
        npm i react-tooltip  --force
        npm i react-wordcloud  --force
        npm i react-tooltip  --force
        npm i immutability-helper  --force
        npm i react-dnd  --force
        npm i react-dnd-html5-backend  --force
        npm i react-device-detect  --force
        npm i react-device-detect  --force
        npm i immutability-helper  --force
        npm i react-device-detect  --force
        npm i immutability-helper  --force
        npm i slick-carousel  --force
        npm i jsx-runtime --force
        npm i html-webpack-plugin --force
        npm i web-vitals --force

        npm audit fix --force


npm audit은 dependency tree의 보안 취약점과 해결방안을 제공해준다. 프로젝트에 구성된 dependency에 대한 설명을 기본 레지스트리에 제출하고 알려진 취약성에 대한 보고서를 요청합니다.
npm audit fix는 npm audit으로 나온 결과를 자동적으로 고쳐주는 것이다. 


npm cache clean --force
첫 번째 방법은 npm cache clean --force 명령어이다. npm 버전 5 이후로는 --force를 붙이지 않으면 오류가 발생한다. 이 명령어는 npm의 cache를 모조리 삭제하는 명령어이다.

npm cache verify
두 번째 방법은 npm cache verify 명령어인데, 이 명령어는 cache 폴더의 내용을 확인하고, 가비지 데이터들을 수집하여 삭제하고 무결성을 확인한다. 즉 cache에서 꼬인 부분을 체크 및 해결하는 명령어로, 지우는 명령어보다는 온건한(?) 방법이라고 할 수 있다.
