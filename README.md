# ContextHook연습하기
provider와 consumer을 사용하여 데이터 접근하여 사용하기
```jsx
<ThemeContext.Consumer>
      {value=>(<div
                style={{
                margin:50,
                padding:50,
                backgroundColor:value,
      }}>
      <p>컨텍스트를 가지고 데이터를 전달하는 예</p>
      <button>확인</button>
      </div>
    )}
</ThemeContext.Consumer>
            
```
