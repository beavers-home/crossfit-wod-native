# 프로젝트 유의사항 및 디렉토리 설명

<strong>추 후 수정되거나 추가 될 수 있습니다.</strong>

## 유의 사항

1. JSX(TSX) 를 Return하는 파일은 tsx 확장자를 붙여야합니다. ex ) Photo.tsx

- JSX : React 스크립트 안에서 일반적인 HTML의 형태의 문법을 사용할 수 있도록 자바스크립트를 확장한 문법입니다. 이 프로젝트는 타입스크립트이기때문에 확장자를 TSX로 지정합니다.

2. tsx 확장자를 가지고있는 파일들은 다음과 같은 네이밍 규칙을 가집니다. </br>
   ex ) Photo.tsx, Login.tsx </br>
   디렉토리나 ts 확장자를 가지는 파일들의 이름은 소문자로 구성합니다.

3. 프로젝트 실행 방법

- npm install로 package.json에 명시된 모듈들을 다운로드 받습니다.
- npm run ios 혹은 npm run android로 프로젝트를 실행합니다.

---

## 디렉토리 설명

### assets : 정적인 폰트, 이미지가 위치하는 폴더입니다.

### components : 컴포넌트들이 위치하는 폴더입니다.

- 하위 디렉토리들을 새롭게 생성하거나, 파일만 생성 할 수도 있습니다.

### screens : 페이지를 의미하는 컴포넌트들이 위치하는 디렉토리입니다.

### navigators : 네비게이터들이 위치하는 디렉토리입니다. (Teb Navigator / Stack Navigator 등)

# 사용 라이브러리

🚨 새로운 라이브러리가 추가되면 이곳에 적어주세요!

- styled-components : UI 스타일링 할 때 사용할 라이브러리입니다.
- react-hook-form : form을 구현할 때 코드 가독성 및 생산성을 높여주는 라이브러리입니다.
