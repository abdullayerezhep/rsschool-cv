# Abdulla Yerezhep

## Contacts:
 - Email: yerezhepabdulla@gmail.com.
 - Whats'app: +7 771 633 10 12.
 - GitHub: https://github.com/AbdullaYerezhep

## About me:
  My goal is to become a full-stack developer within the next three years. I studied the basics of computer science at the University of Information Technology and Management, specializing in IT/Programming. After graduation, I worked as a BPM developer for two years, where I learned to program logic for various business processes and gained an understanding of data, fields, and state manipulations. This experience had a significant impact on my understanding of system architectures.

Throughout my journey, I realized that my desire to advance my knowledge in creating multi-layer web applications is growing stronger, and I thoroughly enjoy creatively solving and breaking down complex challenges into smaller, manageable ones. I have developed crucial IT skills such as patience, communication (confident, articulate, and professional speaking abilities), and persistence, which I know will help me become a competent and competitive worker in any company.
    
## Skills
 - HTML/CSS
 - Golang
 - JS/Node/JQuery/React
 - SQL
 - Docker
 - Git
## Code Example
**CodeWars: Take a Ten Minutes Walk** 
### Description:
You live in the city of Cartesia where all roads are laid out in a perfect grid. You arrived ten minutes too early to an appointment, so you decided to take the opportunity to go for a short walk. The city provides its citizens with a Walk Generating App on their phones -- everytime you press the button it sends you an array of one-letter strings representing directions to walk (eg. ['n', 's', 'w', 'e']). You always walk only a single block for each letter (direction) and you know it takes you one minute to traverse one city block, so create a function that will return true if the walk the app gives you will take you exactly ten minutes (you don't want to be early or late!) and will, of course, return you to your starting point. Return false otherwise.
### Solution:
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
- BPM Developer
- Pet projects:
Ascii-art-web(Golang/Js) https://github.com/AbdullaYerezhep/ascii-art-web
Groupie-Tracker(Golang/Js) https://github.com/AbdullaYerezhep/groupie-tracker
Heroes(Js) https://github.com/AbdullaYerezhep/heroes
## Education
Programmin - University of Information Technology and Management(Poland)
## English
C1

