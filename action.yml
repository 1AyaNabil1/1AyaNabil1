name: "generate-snake-game-from-github-contribution-grid"
description: "Generates a snake game from a GitHub user contributions grid. Outputs the animation as a GIF or SVG."
author: "platane"

runs:
using: docker
image: docker://platane/snk@sha256:753878055e52fbbaf3148fdac4590e396f97581f1dc4c1f861701add7a1dc1b5

inputs:
github_user_name: "1AyaNabil1"

outputs:

name: github-snake.svg
description: "Snake game generated from GitHub contributions grid."
path: github-snake.svg
options:
palette: "github-dark"
actions:
generate:
description: "Generate SVG"
uses: actions/generate@v1
with:
output: github-snake.svg
options:
palette: "github-dark"
