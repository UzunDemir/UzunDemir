- 👋 Hi, I’m @UzunDemir
- 👀 I’m interested in machine learning and data science...
- 🌱 I’m currently learning python and taking a machine learning course in Skillbox
- 💞️ I’m looking to collaborate on ...in fact, I have not yet decided in which direction to put my efforts. 
- 📫 How to reach me ...uzunvitt@gmail.com


![](https://komarev.com/ghpvc/?username=UzunDemir)

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=UzunDemir&theme=github_dark)

![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=UzunDemir&theme=github_dark) ![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=UzunDemir&theme=github_dark)

![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=UzunDemir&theme=github_dark) ![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=UzunDemir&theme=github_dark)

- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ [github.repository_owner](https://github.com/UzunDemir) }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

