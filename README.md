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
    languages: ['python', 'javascript'],
    links: [
      'https://www.codewars.com/users/jp6rt',
      'https://www.linkedin.com/in/jp6rt/'
    ]
  })
}

grettings();
```
