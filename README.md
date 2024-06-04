
```javascript

const {
  sayHello,
  aboutMe
} = require('/dev/null')

function greetings() {
  
  sayHello('Hi there!');
  
  aboutMe({
    name: 'Joey',
    professionalRoles: ['Backend Developer', 'Data Engineer', 'DevOps Engineer'],
    passionateAbout: ['Data Science'],
    languages: ['python', 'javascript']
  })
}

grettings();
```
