# Derkach Danyil
******
# Contacts
* **E-mail:** derkach782003@ukr.net
* **Telegram:** @DerkachDanyil
* [Linkedin](https://www.linkedin.com/in/derkachda/)
******

# Info
I am 18 years old, highly motivated student, who is studing Computer Science in Chernihiv State Technological University, currenty finishing second year. Programming always has been my passion. I made my choise to become programmer in the beginning of high school. Since then I started analysing what programming languages exist, whats the difference between them, what to choose to study. Long story short, on the second year of university I finally realise that I want to study JavaScript. And here I am, studing Front-End in rs-school and willing to become proud member of rs-community.
******

# Skills
* HTML5, CSS
* C++ Basics
* JS Basics
* Figma, Adobe Photoshop
* VS Code, Qt
* Git/Github
* Blender
******

# Code example
**Codewar (Sudoku Solution Validator)** Sudoku is a game played on a 9x9 grid. The goal of the game is to fill all cells of the grid with digits from 1 to 9, so that each column, each row, and each of the nine 3x3 sub-grids (also known as blocks) contain all of the digits from 1 to 9.

```
function validSolution(board) {
  for (let i = 0; i < 9; i += 3) {
    for (let j = 0; j <  9; j += 3) {
      let temp = [];
      for (let k = 0; k < 3; ++k) {
        for (let l = 0; l < 3; ++l) {
          if (temp.includes(board[i + k][j + l]) || board[i + k][j + l] === 0) {
            return false;
          } else {
            temp.push(board[i + k][j + l]);
          }
        }
      }
    }
  }
  return true;
}
```

# Education
* **University:** Chernihiv State Technological University, Computer Sciene 2020-2024
* **Courses:**
    + XYZ School: Intro to 3D Design
    + RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
    
# Languages
* Ukrainian (native)
* Russian (native)
* English (C2 according to [EFSET](https://www.efset.org/cert/tRTscD))
