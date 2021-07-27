# react-ts-multiplepropsinfun

```js
import React from 'react';

function Greeter(props:any){
  return <div> Hello {props.name} with age {props.age}!</div>
}

function App() {
  return (
    <div>
      <Greeter name="Akshay" age={39} />
      <Greeter name="Panth" age ={4} />
    </div>
  );
}

export default App;
```
