
```javascript

const {
  sayHello,
  aboutMe
} = require('/dev/null')

function greetings() {
  
  sayHello('Hi there!');
  
  aboutMe({
    name: 'Joey',
    currentRoles: ['Backend Developer', 'DevOps Engineer', 'Cloud Engineer'],
    languages: ['javascript', 'typescript', 'bash'],
    favoriteQuote: 'It\'s not a battle for perfection but progress.'
  })
}

grettings();
```
