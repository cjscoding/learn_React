# learn_React

# React JS
    application이 아주 interactive하도록 만들어주는 library

# React-dom
    모든 React element들을 HTML body에 둘 수 있도록 해줌

# element
    script 내에서 직접 만든 요소는 대문자로 시작하기!

# React.useState();
    useState api 사용 시 react가 배열하나를 반환해 주는데, 그 배열의 첫번째 요소는 내가 담으려는 data 값이고 두번째 요소는 data값을 modify하는 값이다.
    modifier의 필요성 : data의 즉각적인 rerendering을 위해 필요하다.
    modifier의 사용(state 셋팅 방식 2가지)
        1. 직접 값을 설정해준다.
            modifier(data+1);
        2. 함수를 반환한다.
            modifier((curData) => curData + 1);
        => 가급적 2번 방식을 사용하자!