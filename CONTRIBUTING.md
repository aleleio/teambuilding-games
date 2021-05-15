# Contributing to Teambuilding Games

Thanks for considering to contribute to the teambuilding games collection! :tada:

### Adding or Updating Games
Adding to the library of teambuilding games is as simple as opening a game and clicking the `Edit this file` pencil icon.
Save your changes (they will be saved in a separate fork on your account) and create [a pull request](https://github.com/aleleio/teambuilding-games/pulls).

That's it.

If you need help or get stuck, please feel free to [open an issue](https://github.com/aleleio/teambuilding-games/issues). If you want to edit more than one game, the recommended way is to fork and clone the repo locally:

* Create [a fork](https://github.com/aleleio/teambuilding-games/fork) of this repo in your account
* Clone the repo to your local machine with `git clone https://github.com/[YOUR-ACCOUNT]/teambuilding-games.git`
* Create a new branch using `git switch -c new-branch`
* Add your changes in this branch and commit them with a descriptive name
* Create [a pull-request](https://github.com/aleleio/teambuilding-games/pulls) from your `new-branch -> main`

This is also known as [Github Flow](https://guides.github.com/introduction/flow/).


### YAML Frontmatter

Please stick to these enums, when creating frontmatter:

```yaml
---
game_type:
  - ice | ener | trust | prob | name | brain | song | race | gtk
game_length:
  - short  # <10 mins
  - medium  # 10-30 mins
  - long  # 30-120 mins
group_size:
  - small  # 2-7 people
  - large  # 13-16 people
  - multiple  # 15-40 people
  - event  # 50-300 people
group_needs:
  - slug: first | energy | honesty | strategy | inspiration | why | identity
    score: 0 | 1 | 2 | 3 | 4 | 5
---
```
