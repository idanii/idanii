```js
const HelloWorld = async () => {
  const data = {
    title: "Hey there 👋 I'm Idan Masas - A software developer.",
    content: "I started coding at the age of 12, and have been exploring and learning the security & technology
    world ever since. I'm a self-learner, love solving hard problems, and passionate about security and programming.",
    key: "8nbmmMOeBPZRufvTpAkBeNYJBwQX5zXl"
  }

  const response = await fetch("https://idanmasas-github.idanosh.repl.co/", {
    method: "POST",
    body: JSON.stringify(data)
  })
  
  console.log(response.json())
}
```
