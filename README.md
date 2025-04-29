# Public Domain Recipes
![PRs Welcome](https://badgen.net/static/PRs/Welcome/green) ![LICENSE](https://badgen.net/static/LICENSE/Unlicense) [![GitHub release](https://img.shields.io/github/release/ronaldl29/public-domain-recipes.svg)](https://GitHub.com/ronaldl29/public-domain-recipes/releases/) [![GitHub contributors](https://badgen.net/github/contributors/ronaldl29/public-domain-recipes)](https://GitHub.com/ronaldl29/public-domain-recipes/graphs/contributors/) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

[PublicDomainRecipes.com](https://publicdomainrecipes.com)

This is a simple cooking website where users can submit recipes here for credit.
There are no ads, trackers or cookies (unless recipes thereof).

This site is compiled and organized with Hugo, using [this very simple theme](https://github.com/lukesmithxyz/lugo). This project is a continuation of LukeSmithXYZ's [based.cooking project](https://github.com/LukeSmithxyz/based.cooking).

![Screenshot](https://github.com/ronaldl29/public-domain-recipes/blob/main/README-image.png?raw=true)

## Ways to contribute

- By adding a recipe.
- Make a recipe and take a nice picture of it if no nice picture already
  exists. Submitted images should be small `.webp` files ideally less than 100K
  or so.
- Fix errors in recipes or add minor improvements.

## Rules for submission

- Model submission files after [example.md](example.md). Put them in `content/`.
- File names should be the name of the dish with words separated by hyphens
  (`-`). Not underscores, and definitely not spaces.
- No need to include simple items (salt, pepper, etc.) in the ingredient list.
- The file needs to be `\n` terminated in unix-fashion (if you're on Linux you
  don't need to care, it should be automatic).

You may include a json file with your personal links/donation addresses in
`data/authors/your-name.json`.

### Tags

Remember to add tags to your recipe, but try to use tags already used by other recipes.

If your recipe contains no meat or dairy, include the `fasting` tag.
If it includes dairy but no milk, include the `cheesefare` tag.

### Images

Images are stored in `/pix`.

Each recipe can have a title image at the top and perhaps several instructional
images as absolutely necessary.

Do not add stock images you found on the internet. Take a good picture yourself
of the actual dish created. If you see a bad or substandard image, you may
submit a better one.

Images should be in `.webp` format and with as small file size as possible. If
you submit an image for say, `chicken-parmesan.md`, it should be added as
`pix/chicken-parmesan.webp`.

If you would like to add additional directional images,
they should be numbered with two digits like: `pix/chicken-parmesan-01.webp`, etc.

Note also that images should have links beginning with a slash in this use
case, i.e. `/pix/...`.

## License

This website and all its content is in the public domain.
By submitting text or images or anything else to this repository,
you waive any pretense of ownership to it,
although you are welcome and recommended to give yourself credit
at the bottom of a submitted page for you adding it
(including personal or donation links).
