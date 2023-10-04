
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
    languages: ['hcl', 'python', 'bash', 'javascript/typescript']
  })
}

grettings();
```
