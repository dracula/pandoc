### [Pandoc](https://pandoc.org)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/pandoc.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/pandoc/archive/master.zip) option and unzip them.

#### Activating theme

1. Copy `dracula.theme` and `dracula.yaml` somewhere memorable (perhaps
   into `~/.config/pandoc/`)
2. Get `draculatheme.sty` from [the LaTeX Dracula
   theme](https://draculatheme.com/latex) and put it with `dracula.theme` and
   `dracula.yaml`
3. Replace the paths in `dracula.yaml` with the full paths of wherever you have
   placed `dracula.theme` and `draculatheme.sty`
4. Use pandoc with the flag `--defaults path/to/dracula.yaml`
3. Boom! It's working
