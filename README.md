
```js
class Steed {
  get contact() {
        const email = "steed.monteiro@gmail.com"
        return { email }
  }

  get life() {
    const age = 36;
    const from = 'Paris';
    const speaking = ['French', 'English', 'Spanish', 'Portuguese'];
    return { age, from, speaking,  };
  }

  get coding() {
    const languages = {
      expert: ['typescript','react','react-native'],
      intermediate: ['python', 'swift'],
      learning: ['c', 'c++', 'c#'],
    };
    const specialities = [ 'fullstack', 'ai', 'mobile','nestjs', 'nginx', 'kubernetes' ];
    const config = ['mac', 'vscode'];
    };
    return { languages, specialities, config };
  }
}
```
