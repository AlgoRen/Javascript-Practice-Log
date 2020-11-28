# Rewrite the showCircle function in the solution of the task Animated circle with callback so that it returns a promise instead of accepting a callback.

## The new usage:

```javascript
showCircle(150, 150, 100).then((div) => {
  div.classList.add("message-ball");
  div.append("Hello, world!");
});
```
