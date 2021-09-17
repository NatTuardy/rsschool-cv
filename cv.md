# NATALY MAYDANNYK 

## JUNIOR FRONT-END DEVELOPER
_________________________________________________________________

## CONTACTS:

**Phone** +38 097 1099991  
**E-mail** nattuardy@gmail.com  
**Telegram** @NatalyTuardy  
[LinkedIn](https://linkedin.com/in/nataly-maydannyk-b508a31b5)  
[GitHub](https://github.com/NatTuardy)  
________________________________________________________________

## OBJECTIVE

With a passion to web-development, I want to work as a junior front-end developer where I could create digital solutions and elevate user experience to the next level.
_________________________________________________________________

## TECH SKILLS

* HTML5, CSS3, SCSS
* JavaScript, ES5, ES6
* DOM, Fetch Api, CRUD, Promise Api
* React, Redux, Redux Toolkit, React Hooks
* WebPack, Gulp
* GIT, GitHub
* Node.js, TypeScript
* VSCode, Figma, Sony Vegas Pro, Adobe Photoshop
_________________________________________________________________

## COURSES

1. RS School Course «JavaScript/Front-end Stage 1» (in progress...)
2. Vladilen INC Course «JavaScript Junior Frontend Developer» (online course from Vladilen Minin)
3. Go-It Bootcamp Course «Full Stack Developer»
_________________________________________________________________

## LANGUAGES

**English:** Intermediate
**Ukrainian:** Advanced
**Russian:** Advanced
_________________________________________________________________

## CODE EXAMPLE

_Johnny is a farmer and he annually holds a beet farmers convention "Drop the beet".

Every year he takes photos of farmers handshaking. Johnny knows that no two farmers handshake more than once. He also knows that some of the possible handshake combinations may not happen.

However, Johnny would like to know the minimal amount of people that participated this year just by counting all the handshakes.

Help Johnny by writing a function, that takes the amount of handshakes and returns the minimal amount of people needed to perform these handshakes (a pair of farmers handshake only once)._

```
function getParticipants(handshakes){
    if(!handshakes) return 1;
  let people = 0;
  let sumHandshakes = 0
  while(handshakes > sumHandshakes) {
    sumHandshakes = people * (people + 1) / 2;
    people++;
  }
  return people;
}
```

