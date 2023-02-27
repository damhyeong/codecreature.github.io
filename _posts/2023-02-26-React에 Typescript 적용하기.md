## 기초적인 Typescript 문법을 알아야 합니다

### 1. 변수 선언 방법

```typescript
const typeString : string = "Hello World"
```

`const` : 변하지 않는 고정 값이라는 의미입니다.
<br/>  
`typeString` : 제가 임의로 정한 변수 이름입니다.   
<br/>
`string` : Typescript에서는 모든 변수에 타입이 지정이 되어야 합니다.   
<br/>

### 2. 함수의 반환값 선언 방법
```typescript
const App : () : JSX.Element => {
    return (
        <div>
            <h1>Hello World</h1>
        </div>
    );
};
```

`App` : React 프로젝트를 작성 시, <b>"컴포넌트"</b> 를 모아서 처리하는 역할로 계속 쓰이게 됩니다.
<br/>

`JSX.Element` : "`React.FC`" 로 선언하는 방식이 있지만, `JSX.Element`가 훨씬 더 편했던 경향이 있어 사용합니다.
<br/>

<hr/><br/>

## 앞으로 Typescript를 적용할 예제 책

> ***리액트를 다루는 기술*** : 김민준 (Velopert) 

> 김민준(Velopert) : Velog 사이트를 만드신 분   
<br/>

### 책을 사고 Typescript 적용하면서 보시는 걸 추천합니다.
* 이유
    * 책에 훨씬 자세한 내용이 적혀있어 실력향상에 좋습니다.
    * 이미 이 책을 끝냈다고 하더라도 `Typescript` 적용이 절대로 쉽지 않습니다.
    * 이어질 포스팅에서 `Typscript` 적용 과정에서 설명이 필요 시 책의 내용을 참고하겠지만, 최대한 `Typescript`에만 설명을 집중 할 겁니다.
