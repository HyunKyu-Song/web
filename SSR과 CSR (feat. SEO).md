> ## SSR (Server Side Rendering)
서버 사이드 렌더링이라고 하며, 예시로 Next.js가 있다.
여기서 말하는 렌더링은 일반적으로 알고 있는 html, css, js를 다운받아 해석하고 화면을 그려주는 렌더링과는 약간 다르다.<br>
SSR에서 렌더링은 이미 서버에서 파일이 준비되어 있는 것을 말한다.
즉, brower가 받았을 때 내용이 들어있다.<br><br>
#### 📍요약하자면
이미 내용이 들어있는 파일을 서버가 보내주기 때문에 클라이언트는 화면을 보여주기만 하면 됨<br><br>
![](https://velog.velcdn.com/images/thdgusrbek/post/5cedce00-383f-44a9-aec8-32e0fa83b7f7/image.png)<br><br><br><br>

> ## CSR (Client Side Rendering)
클라이언트 사이드 렌더링이러고 하며, 예시로 React, vue가 있다.
CSR은 SSR과 다르게 서버에서 빈 파일을 보내주고 browser에서 다운받고 실행시켜서 화면을 그려준다.<br><br>
![](https://velog.velcdn.com/images/thdgusrbek/post/c84d35ae-3092-4c3c-b447-3e647495fb0e/image.png)<br><br><br><br>

> ## SEO (Search Engine Optimization)
검색 엔진 최적화라고 한다.<br>
검색 엔진 봇이 사이트를 방문하며 정보를 수집하는데 SSR은 사이트가 렌더링 되어 정보를 제공하지만 CSR은 빈 화면에서 다운받고 실행시켜야 정보를 제공할 수 있다. 
그래서 CSR은 검색 엔진 봇에게 정보를 제공할 수 없다.<br><br>
#### 📍요약
`SSR로 만든 사이트는 검색에 노출↑`
`CSR로 만든 사이트는 검색에 노출↓`<br><br><br><br>

> 사진출처: https://medium.com/walmartglobaltech/the-benefits-of-server-side-rendering-over-client-side-rendering-5d07ff2cefe8
