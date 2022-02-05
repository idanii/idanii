```js
const HelloWorld = async () => {
  const response = await fetch("https://github.com/idanii", {
    method: "POST",
    data: {
      title: "Hey there 👋 I'm Idan Masas - Software developer.",
      content: "I started coding at the age of 12, and have been exploring and learning the security & technology world ever since. I'm a self-learner, love solving hard problems,                 and passionate about security and programming."
    }
  })
}
```
