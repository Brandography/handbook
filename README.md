# Development at Brandography
At Brandography, we have some of the best nerds around. We love [GIFs](https://media.giphy.com/media/tIjdrTgFkT3kig4DY0/giphy.gif), [dogs](https://cdnbrandog2-c7f.kxcdn.com/wp-content/uploads/2014/01/Roufous-540x540-1.jpg), [tech news](https://news.ycombinator.com/), and [beer](https://media1.giphy.com/media/4JOaSVSBUczAY/giphy.gif). If you're wondering what our developers do or might be interested in working on our team, here's how we work.

## Code Standards
Our team has collected some basic syntax tools and style guide references. We use these every day to build quality in our craft.

### Your Editor
Your integrated development environment (IDE) is a very personal part of you doing your best work. You know it like the back of your hand. We will never enforce a specific editor (but we love [VS Code](https://code.visualstudio.com/)), terminal emulator, or operating system upon you (we prefer MacOS or Linux). You are free to set up your system to your liking.

#### `~/.editorconfig`
We won't enforce the editor you choose to use. We do ask that you install a plugin for it called [Editor Config](https://editorconfig.org/). This plugin allows us to set some basic syntax standards across a wide range of languages for our team. It ensures basic syntax like tabs vs spaces (we use spaces) are set from the get go.

You can find our `.editorconfig` file in [our .editorconfig repository](https://github.com/Brandography/.editorconfig/). The easiest way to get this working is to add it in your home folder. All you have to do is run this command: `curl https://raw.github.com/Brandography/.editorconfig/master/.editorconfig > ~/.editorconfig`

### Style Guides
- [PHP](https://www.php-fig.org/psr/psr-2/)
- [CSS/SCSS](https://github.com/airbnb/css/blob/master/README.md)
- [JavaScript](https://github.com/airbnb/javascript/blob/master/README.md)
- [TypeScript](https://github.com/basarat/typescript-book/blob/master/docs/styleguide/styleguide.md)

#### WordPress
We do a lot of work with WordPress themes and plugins. Some of that work may be from developers outside our team. When crafting _new_ work for WordPress, stick to the [WordPress Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/), but please ignore their section on [indentation](https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/#indentation) (we use spaces).

For WordPress theme development, use [Theme Check](https://wordpress.org/plugins/theme-check/). It will check your theme for everything from bad practices to missing requirements. Additionally, use the [Theme Unit Test Data](https://codex.wordpress.org/Theme_Unit_Test) to import and check all major content types, embeded content, image sizes, etc are styled and handled correctly in your theme.

## Security
Security is one of the most important things to get right in software development. We take a common sense approach to securing our software and workspace.

### Don't Commit Secrets
Never commit passwords, private API keys, `.env` files, or other credentials into version control. All of your credentials should be loaded from the environment variables set in the operating system during deployment.

### Encrypt Your Hard Drive
Having an encrypted drive is common sense. Laptops are prone to being stolen or lost. Having an encrypted drive ensures your data or our client's data cannot be decoded. For MacOS users, you just need to turn on FileVault.

### Lock Your Computer
When you walk away from your desk, always lock your computer. The time it takes to login again is miniscule compared to any type of unauthorized access to your system.

## Project Management
### Trello
We use [Trello](https://trello.com) to manage projects and tasks. You will need a Trello account.

### Everhour
We use [Everhour](https://everhour.com) as our time tracker for projects and tasks. It integrates with Trello via a [browser extension](https://everhour.com/extensions).
