# node-win-mouse
nodejs 模拟鼠标动作

```javascript
const WinMouse = require('./build/Release/addon');
WinMouse.moveTo(200,300);
WinMouse.leftDown();
WinMouse.leftUp();
console.log(WinMouse); 
```
