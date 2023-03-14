# Abdulla Yerezhep

## Contacts:
 - Email: yerezhepabdulla@gmail.com.
 - Whats'app: +7 771 633 10 12.
 - GitHub: https://github.com/AbdullaYerezhep

## About me:
    My goal is to become full-stack developer in next 3 years. I have studied basics of Computer Science in University of Information Technology and Management in IT/Programming specialisation after graduation I've worked as a BPM developer for two year where I have learned to program logic for different bussines processes and had an understanding of data, fields and state manipulations also it had a big impact in my understanding of system architectures.
    Throughout this journey I realised that my desire for further advancement of my knowledge in creation multi-layer web application is getting stronger, and that I really enjoy creative solving and breaking hard challenges into smaller ones. 
    I have achieved some crucial skills in IT area such as patience, communication(confident, articulate, and professional speaking abilities) and persistance which I know will help me to be one of the competent and competetive worker in your company.
    
## Skills
 - Html/Css
 - Golang
 - JS/Node
 - SQL
 - Docker
 - Git
## Code Example
**CodeWars: Take a Ten Minutes Walk** 
###Description:
You live in the city of Cartesia where all roads are laid out in a perfect grid. You arrived ten minutes too early to an appointment, so you decided to take the opportunity to go for a short walk. The city provides its citizens with a Walk Generating App on their phones -- everytime you press the button it sends you an array of one-letter strings representing directions to walk (eg. ['n', 's', 'w', 'e']). You always walk only a single block for each letter (direction) and you know it takes you one minute to traverse one city block, so create a function that will return true if the walk the app gives you will take you exactly ten minutes (you don't want to be early or late!) and will, of course, return you to your starting point. Return false otherwise.
###Solution:
```
    function isValidWalk(walk) {
        if (walk.length !== 10) {
          return false
        }
        let mins = 10
        let x = 0
        let y = 0
        for (let i = 0; i < mins; i++) {
          if (walk[i] === 'n') {
            x++
          } else if (walk[i] === 's') {
            x-- 
          } else if (walk[i] === 'e') {
            y++
          } else if (walk[i] === 'w') {
            y--
          }
        }
       return (x===0 && y===0)
      }
```
## Work Experience

## Education

## English

