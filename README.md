
```javascript

const {
  sayHello,
  aboutMe
} = require('/dev/null')

function greetings() {
  
  sayHello('Hi there!');
  
  aboutMe({
    name: 'Joey',
    currentRoles: ['Backend Developer', 'Data Engineer', 'DevOps Engineer'],
    languages: ['python', 'javascript']
  })
}

grettings();
```
