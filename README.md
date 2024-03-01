# CodeBoost: App Concepts

## Bytecode Compiler/Interpreter for Rust

Create a Bytecode Interpreter for Rust, allowing code execution on a variety of devices. This project provides a unique challenge to deepen your understanding of Rust internals and compiler design.

- Explore [Rust Programming Language](https://www.rust-lang.org/).
- Learn how compilers work [here](https://stackify.com/how-do-compilers-work/).
- Understand what [bytecode](https://en.wikipedia.org/wiki/Bytecode) is.
- Research how [bytecode interpreters](https://compilers.iecc.com/crenshaw/tutor5.pdf) function.
- Dive into the [Rustc Guide](https://rustc-dev-guide.rust-lang.org/).
- Pinpoint components of the [Rust compiler](https://github.com/rust-lang/rust) to modify.
- Begin implementing bytecode interpretation for basic Rust constructs.
- Gradually extend the interpreter to cover more Rust features with guidance from [Crafting Interpreters](https://craftinginterpreters.com/).

## Material Design Theme + MudBlazor

- Generate as many palettes as possible based on your Primary/Secondary colors.
- Utilize a palette generator like [Coolors](https://coolors.co/account/general) or a similar one such as [MyColor](https://mycolor.space).
- Explore color theme creation following the theming rules/methods outlined [here](https://m2.material.io/design/material-theming/implementing-your-theme.html#color).
- Extend theming capabilities with tools like [Material Theme Builder](https://m3.material.io/theme-builder#/dynamic) or existing ones.
- Implement or use already exported CSS files to override MudBlazor themes.
- Enhance MudBlazor by addressing missing properties through custom CSS or components.
- Develop a custom MudBlazor component for loading different themes/CSS to visualize them effectively.
- Explore solutions like [ThemeManager](https://github.com/MudBlazor/ThemeManager) for seamless integration with CSS bundles.


## Database Diagram Visualizer for Entity Framework

- Automatically generate a database diagram image upon the introduction of new migrations.
- Investigate methods such as reflection or designer files for efficient implementation.
- Optionally, integrate it as a GitHub action, save it to the project directory, and reference it in the readme file.
- For inspiration, refer to [Azimutt](https://github.com/azimuttapp/azimutt).

## Web API Generator from JSON file


## Unit Test Generator

> A case analysis is performed for every conditional branch in the code. For example, if statements, assertions, and all operations that can throw exceptions are analyzed. This analysis is used to generate test data for a parameterized unit test for each of your methods, creating unit tests with high code coverage.

- Refer to resources like Visual Studio [Unit Test Generation](https://learn.microsoft.com/en-us/visualstudio/test/generate-unit-tests-for-your-code-with-intellitest?view=vs-2022).
- Explore tools such as [gotests](https://github.com/cweill/gotests) and [jest-unit-test-generator](https://github.com/ed4becky/jest-unit-test-generator).

## Questionnaire

Develop a dynamic questionnaire based on a list of questions with the following structure:

- The questions are n-tiered and subsequent questions are asked based on the responses
    or series of responses of previous questions.
- In general, the questions are grouped, such that a set of questions are asked and that
determines if additional questions need to be added. Similar to the structure of a
treenode, where more questions are revealed if a node is clicked.
- The questions need to be asked one at a time
- The responses to the questions can be Boolean, radio selection (Boolean can fit here),
checkbox selection, checkbox selection with “other” textbox, or informational textbox.
- Each question is assigned a “point” value, and this needs to be recorded and reported to
tabulate a response
- from the Analyst – this point value is typically used to discretionary display further
questions depending on the value reported.
- The initial question (tier 0) is the acceptance of a disclaimer.
- There are domains for the sets of questions (aka categories) and this does not need to be
displayed

## Synonyms Game

- Utilize resources like [WordNet](https://wordnet.princeton.edu) and [Dictionary API](https://dictionaryapi.dev).
- Explore [Oxford Dictionaries API](https://developer.oxforddictionaries.com/documentation).

## Blazor WebAssembly Game

- Explore projects like [GameATron4000](https://github.com/amolenk/GameATron4000) and [Blazor Pages](https://github.com/fernandreu/blazor-pages).

## Contribution Graph Pixel Art

- Implement a workflow triggered by events like recurring events or commit pushes.
- Explore [Gitfiti](https://github.com/gelstudios/gitfiti) for inspiration.

## News Feed Profile Readme

- Implement a workflow triggered by events like recurring events or commit pushes.
- Utilize GitHub Actions with a focus on events triggering workflows.
- Fetch and filter data to update the profile readme.

## Sports Betting Bot

- Leverage sports databases, categorizing sports games and player statistics.
- Implement features for football leagues, clubs, and player statistics.
- Include game results, odds, and rules for calculating winning conditions.
- Explore Selenium or other tools for website login.
- Implement data scraping for odds and sports-related news.
- Incorporate arbitrage checks for betting odds using available resources.
- Useful Links
  - [Arbitrage Betting](https://en.wikipedia.org/wiki/Arbitrage_betting)
  - [Sports Betting](https://github.com/georgedouzas/sports-betting)
  - [Premier League Statistics](https://www.premierleague.com/stats/top/players/goals?se=489)
  - [Data Sources](https://data.world/datasets/sports)
  - [Football Data Hub](https://datahub.io/collections/football)


### Contribution

Feel free to suggest new ideas or improvements. Happy coding!
