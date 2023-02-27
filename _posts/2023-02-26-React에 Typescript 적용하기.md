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

## 앞으로 포스팅 될 React + Typescript 예제는 <br>
## 둘 중 하나는 알아야 이해 할 수 있는 과정입니다.

