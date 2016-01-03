# Starter zshrc

Zsh has given me so much mileage with respect to efficiency at the command line.
Looking back I'm a little sad I didn't switch to it sooner. One of the reasons
why it took so long was that I didn't know where to start; with this in mind,
I've collected some of the zsh-specific bits of my dotfiles into one place to
help people hit the ground running.

Note that this is an example _starter_ zshrc. What I mean by this is that it's
more of a skeleton zshrc. It's been crafted with the assumption that you're
coming from bash and you already have some bash config that you're weary to
part with. The content here aims to be minimally invasive, and since zsh is
largely compatible with bash, the rest of your config should fit right in.

## Usage

By default, though, it depends on two external plugins (so it's not as minimal
as it could be). These are [oh-my-zsh][1] and [zsh-syntax-highlighting][2].


```console
# install oh-my-zsh first:
$ git clone https://github.com/robbyrussell/oh-my-zsh ~/.oh-my-zsh

# then install zsh-syntax-highlighting as an oh-my-zsh plugin:
$ git clone https://github.com/zsh-users/zsh-syntax-highlighting ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting

# and finally download this zshrc (WARNING: overwrites your current one!):
$ curl https://github.com/jez/starter-zshrc/blob/master/zshrc.zsh > ~/.zshrc
$ zsh
```

There are other options to install oh-my-zsh and zsh-syntax-highlighting which
you can find by reading [their][1] [READMEs][2]. Depending on the route you end
up taking, you might have to adjust some of the settings in the actual file.

[1]: https://github.com/robbyrussell/oh-my-zsh
[2]: https://github.com/zsh-users/zsh-syntax-highlighting


## Documentation

The file itself is __heavily commented__. It should explain (at least briefly)
what every line attempts to do.

[Check it out][zshrc] for yourself!

[zshrc]: zshrc.zsh


## License

MIT License. See LICENSE.
