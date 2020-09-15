### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false) {
    console.log("get back to work!");
  } else {
    if (availableTime < 20) {
      console.log("get pick up and eat in lab!");
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log("try someplace nearby");
    } else {
      console.log("Dont waste too much time on lunch!");
    }
  }
};
```