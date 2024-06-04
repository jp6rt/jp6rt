
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
    sideQuests: ['IOT Development for ESP32'],
    languages: ['python', 'javascript'],
    findMeAt: {
      linkedIn: 'https://www.linkedin.com/in/jp6rt/',
      codewars: 'https://www.codewars.com/users/jp6rt'
    }
  })
}

grettings();
```
