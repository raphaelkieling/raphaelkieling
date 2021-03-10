```js
const me = {
  name: "Raphael Kieling",
  type: "me",
  age: 23,
  birthday: "1998-05-01T12:30:00",
  timezone: -3,
  from: "Brazil",
  currentLevel: "Tech Lead",
  social: [
    "https://www.linkedin.com/in/raphael-kieling/",
    "https://kieling.netlify.app/"
  ],
  currentJob: {
    name: "DX.CO",
  }
}

new LifeBuilder()
  .withMe(me)
  .withCoffe()
  .withPet({ type: 'cat', quantity: 2 })
  .withWife()
  .build()
```
