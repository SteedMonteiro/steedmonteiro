
```js
class Steed {
  constructor() {
    this.age = 38;
    this.from = "Paris";
    this.speaking = ["French", "English", "Spanish", "Portuguese"];
  }

  contact() {
    const email = "steed.monteiro@gmail.com";
    return { email };
  }

  code() {
    const languages = {
      expert: ["typescript", "react", "react-native"],
      intermediate: ["python", "swift", "java"],
    };
    const specialities = [
      "fullstack",
      "ai",
      "mobile",
      "nestjs",
      "nginx",
      "kubernetes",
    ];
    const config = ["mac", "vscode"];
    return { languages, specialities, config };
  }
}
```
