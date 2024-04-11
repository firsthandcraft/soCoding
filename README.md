# soCoding
https://create-react-app.dev/docs/adding-a-css-modules-stylesheet/

```
npm install -g create-react-app
create-react-app my-app
```

# 01 router
 Router :: 데이터들을 가지고있다; 주소, 기록 
           내부적으로 contextprovider이다.
           사용할려면 router 컴포넌트 안에서 사용해야한다.
 * context  :: 많은 컴포넌트에서 사용하는데이터를 반복적인 props전달(Props Drilling)없이 공유
 * 배경 ::
 여기저기 하위의 데이터들을 하나의 기능으로 묶고 싶을때(한국어> 영어)전역 데이터로 올라가서 변경을 해야하는데 이때  props 를 여러번 내리는 문제(prop Drilling반복해서 props를 내려주는 상황)을 해결하기 위해 나옴 
 ==> props를 거치지 않고 여러컴포넌트에 공유해줌
```javascript
//router 사용법
import {BrouserRouter} form 'react-router-dom';
function Main(){
    return <BouserBouter></BrouserRouter>;
}
export default Main;
```
 Routes
 Route
 Link
