# Hi, I'm Terrence 👋🏾

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa

```js
const aboutMe = { 
name: "Terrence Wright", 
location: "Wichita, KS", 
education: "Southern New Hampshire University", 
major: "Computer Science",
skills: ["JavaScript", "Python"],
goals: "Become a full-time Software engineer", 
},
```

![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=Software+Engineer;Front-end+Dev;)

![coding gif](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHJ6cWx4bTR6d3JuNGV6c3pycnAydms2bHZ4Zm9zb2gzZWI3aXE5ZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/AuUN3mognBAIf5eKdb/giphy.gif)

![coding gif](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExY2R2am5xaGd1ZG9sbjUxMnBsa2pmNWw3OHp5NzhkcDl3Yms5MXlqbCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JtwISFbwSjfIk/giphy.gif)
