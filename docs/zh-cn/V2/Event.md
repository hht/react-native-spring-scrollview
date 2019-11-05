### onTouchBegin : ()=>any
手指按下时回调
```$js
<SpringScrollView onTouchBegin={()=>{
    console.log("onTouchBegin");
} />
```

### onTouchEnd : ()=>any
手指抬起时回调
```$js
<SpringScrollView onTouchEnd={()=>{
    console.log("onTouchEnd");
} />
```

### onMomentumScrollBegin : ()=>any
松手后减速开始的回调
```$js
<SpringScrollView onMomentumScrollBegin={()=>{
    console.log("onMomentumScrollBegin");
} />
```

### onMomentumScrollEnd : ()=>any
减速结束回调
```$js
<SpringScrollView onMomentumScrollEnd={()=>{
    console.log("onMomentumScrollEnd");
} />
```
