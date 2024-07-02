```javascript
const {
  aboutMe
} = require('/dev/null')

function greetings() {
  aboutMe({
    name: 'Joey',
    professionalRoles: [
      'Backend Developer',
      'Data Engineer',
      'DevOps Engineer
    '],
    passionateAbout: ['Data Science', 'IOT Development with ESP32'],
    languages: ['python', 'javascript']
  })
}

greetings();
```
