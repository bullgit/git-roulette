# git-roulette

## Make your git workflow a little less boring.

What's life without a little risk?

`git roulette` is just like `git commit -m`, but with a twist : once in a while, it'll blow up in your face and do something silly.

git-roulette won't boost your productivity. But hey, maybe it's a good way to learn how to fix git related issues.


It's less dangerous than Russian roulette though: you'll always get a warning message, the silly things git-roulette does can always be fixed easily (if you know your way around git), and it won't affect any of your collaborators (unless you push carelessly).


## Usage

```
$ git add .
$ git roulette "A super descriptive commit message"
$ git push # If you're lucky
```


## Installing

Just put the `git-roulette` script somewhere your $PATH can see it.

This would be a simple way to do it:
```
git clone git@github.com/victormours/git-roulette.git
cp git-roulette/git-roulette /bin/git-roulette
```


## LICENSE

Good old MIT license.

## Contributing

Eh, I'm not so sure there's much to add. But you can always fork and send a pull request.

## TODO:
- Obligatory "How git-roulette uses git-roulette to develop git-roulette" conference talk
- `git-roulette --hint` to give advice on how to fix things
- `git-poker`?
- fix intermittent bug that crashes the whole system and removes the whole repo on all remotes once in a while

