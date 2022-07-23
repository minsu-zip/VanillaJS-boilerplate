# vanillaJS-boilerplate

## Getting Started

### Clone Repository

```
git clone https://github.com/minsu-zip/vanillaJS-boilerplate.git
```

### install Packages

```
npm install
```

### run development application

```
npm run dev
```

### run production application

```
npm start
```

## Information

babel과 webpack을 이용해 트렌스파일링 및 번들링 작업

#### 개발 모드와 배포 모드로 분류

개발 모드 : 번들된 JS코드도 개발자 모드에서 확인 할 수 있게 source-map 적용 <br>
배포 모드 : TerserWebpackPlugin : 자바스크립트 코드를 난독화하고 debugger, console.log 구문 제거
그 외에 최적화 수행
