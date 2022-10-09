# Elena Golovanova

## Contact info
- **Phone**: +358 40 123 45 46
- **E-mail**: myaccount@gmail.com
- **LinkedIn**: [elena-golovanova](https://www.linkedin.com/in/elena-golovanova-a229981b1/)
- **GitHub**: [ElenaCoder](https://github.com/ElenaCoder)

## About me
I am a software development student at Omnia college in Finland. I have been living in Helsinki for 3 years, but I am originally from Moscow. I have a degree in Math (Applied Mathematics). I am highly interested in learning new things in the web development area. My teachers describe me as a self-disciplined and goal-focused person who pushes themselves to achieve success. I have recently joined a self-study education program in Rolling Scopes school with a mentor's support. I believe it will be beneficial for my career and it helps me to achieve corresponding competences for the junior level position.

## Skills
- HTML5
- CSS3 (Flex, Grid, BEM methodology)
- JavaScript Fundamentals (Metropolia University of Applied Sciences, Stepik, https://www.freecodecamp.org/)
- Java Basics (University of Helsinki’s massive online course)
- SQL and Relational DB (Metropolia University of Applied Sciences)
- Python (three online courses on Coursera and Stepik platforms)
- CVSs - Git, GitHub, Git Extensions, Git Bash (Omnia and Metropolia courses)
- Figma
- IDEs - VS Code, PyCharm, NetBeans
- Agile Frameworks – Scrum, Kanban, XP, FDD

## Code examples
#### Description: 
Task “Split Strings” from Codewars.com site:
Complete the solution so that it splits the string into pairs of two characters. If the string contains an odd number of characters then it should replace the missing second character of the final pair with an underscore ('_').
**Examples**:
```
> 'abc' =>  ['ab', 'c_']
- 'abcdef' => ['ab', 'cd', 'ef']
```
#### Code:
```
function solution(str){
  const len = str.length;
  const result = [];
  
  if(len % 2 !== 0){
     str += "_";
     }
   
  for(let i = 0; i < len; i=i+2){
    result.push(str.slice(i,i+2));
  }
  
  return result;
}
```