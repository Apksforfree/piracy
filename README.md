<div hidden align="center">
  <a href="https://piracy.now.sh"><img width="200" src="https://piracy.now.sh/logo.svg" alt="arrrr!"></a>
  <h1 align="center">Piracy</h1>
  <h3 align="center">It's illegal cuz they can't tax you!</h3>
</div>

<div align="center">
  <a href="https://piracy.now.sh/"><img src="https://img.shields.io/badge/website-piracy.now.sh-3eaf7c?style=for-the-badge" alt="Website"></a>
  <a href="https://github.com/maximousblk/piracy"><img src="https://img.shields.io/github/stars/maximousblk/piracy?color=555&logo=github&style=for-the-badge" alt="GitHub stars"></a>
  <a href="https://twitter.com/intent/tweet?text=Head over to https://piracy.now.sh/ for amazing %23piracy links and resources!"><img src="https://img.shields.io/badge/-tweet%20about%20this-1da1f2?logoColor=fff&logo=twitter&labelColor=1da1f2&style=for-the-badge" alt="Tweet"></a>
</div>

This list is an attempt to add structure to the resources you need to get started on your pirate voyage.

For discussion, feedback or if you come across dead links please head over to [issues](https://github.com/maximousblk/piracy/issues/) section of the [GitHub repository](https://github.com/maximousblk/piracy).

## Credits

This list exists because of

- All [contributors](https://github.com/maximousblk/piracy/graphs/contributors).
- [CHEF-KOCH/Warez](https://github.com/CHEF-KOCH/Warez)
- [Igglybuff/awesome-piracy](https://github.com/Igglybuff/awesome-piracy)

## Frequently asked questions?

#### Why was this even created?

Research purposes... :wink:

#### Is this a biased list?

Somewhat. I do not know everything about digital piracy and can be a little resistive while adding new links.

#### Why can I only search for headers on the website?

A full-text search function is planned.
The website uses vuepress for easy maintainance and deployment.
Vuepress currently only supports header search and algolia pluggin.
I don't know how to integrate algolia in the current deployment cycle.
Any help regarding this will be much appreciated.
Untill then you will have to search via `Ctrl` + `F` or `Cmd` + `F`.
You can also use the GitHub's search and search in the repository.

## Contribute

Contributions are welcome! (But read the [contribution guidelines](contributing.md) first)

## Project structure

- [.github/workflows/archive.yml](.github/workflows/archive.yml) - Github Workflow to automatically archive the website after every update.
- [docs/](docs/) - Main website Source code and lists.
  - [.vuepress/](docs/.vuepress/) - Vuepress configuration file and static assets.
  - [404/README.md](docs/404/README.md) - 404 page for the website.
  - [about/README.md](docs/about/README.md) - 404 page for the website.
  - [laws/README.md](docs/laws/README.md) - List of laws and restrictions regardind digital piracy.
  - [security/README.md](docs/security/README.md) - List of security related tools and assets.
  - [README.md](docs/README.md) - List of all digital piracy related tools and assets.
- [.gitignore](.gitignore) - gitignore file.
- [check_links.py](check_links.py) - A python file to find broken links.
- [contributing.md](contributing.md) - Contribution guidelines.
- [LICENSE](LICENSE) - License file.
- [now.json](docs/now.json) - Configuration file for Vercels Now.
- [package-lock.json](docs/package-lock.json) - Lock file for package manager.
- [package.json](docs/package.json) - Package manager configurations.
- [README.md](README.md) - This file.

## Disclaimer

The owner of this project ([Maximous Black](https://maximousblk.github.io/)) is not responsible for and in no way associated to any external links or their content! The inclusion of any links does not necessarily imply a recommendation or endorse the views expressed within them. I have no control over the nature, content and availability of other websites. If you dislike the information this website provides then please contact the corresponding website's owner/webmaster/hoster directly and fill a DMCA takedown request.

If you believe that your work is accessible through this project in a way that constitutes copyright infringement, you may [create a GitHub issue](https://github.com/maximousblk/piracy/issues/new) to notify me.

## License

[![License](https://img.shields.io/github/license/maximousblk/piracy?style=for-the-badge)](LICENSE)

To the extent possible under law, [Maximous Black](https://maximousblk.github.io/) has waived all copyright and related or neighboring rights to this project.
