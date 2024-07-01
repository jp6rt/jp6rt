```javascript
const {
  aboutMe
} = require('/dev/null')

function grettings() {
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

grettings();
```
