# native-test-route
前端路由实现原理，前端路由实践

## hash

#后面就是hash的内容，哈希值的变化不会导致浏览器刷新。

location.hash可以获取当前页面的哈希值。

## history

history.pushState方法可以修改会话栈历史，更新url而不引起浏览器的刷新。

不同于hash，history模式下，使用location.pathname获取当前的url。

pushState的变化、浏览器的前进后退，通过popstate事件触发。