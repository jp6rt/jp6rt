
```javascript

const {
  sayHello,
  aboutMe
} = require('/dev/null')

function greetings() {
  
  sayHello('Hi there!');
  
  aboutMe({
    name: 'Joey',
    currentRoles: ['Software', 'DevOps', 'Data'],
    languages: ['python', 'hcl', 'javascript']
  })
}

grettings();
```
