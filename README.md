# dokey
> real men do it with the keyboard 
-old unix admin saying

# dependencies
* unix-based system (e.g., macos, linux, bsd, etc), might work on recent versions of windows [with add-ons](https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux) or with older windows and a [virtualbox](https://www.virtualbox.org/) unix installation
* [terminal emulator](https://en.wikipedia.org/wiki/Terminal_emulator)
* [command line](https://en.wikipedia.org/wiki/Command-line_interface)
* [python](https://docs.python-guide.org/starting/installation/)
* Create an account in [asciinema](https://asciinema.org/) to record and share your terminal sessions
* [giph](https://github.com/phisch/giph) to record your desktop sessions

# topics

- [warm up](#warmup): basic skills and gui alternatives
- [hci](#hci): user land
- [cscw](#cscw): collaborate with users and devices
- [visualization](#visualization): rich content
- [software](#software): dev ops

## warmup

| assignments | deliverables | references |
| -- | -- | -- |
| set-up the main dependencies and demonstrate your base system | change your command prompt with your student ID, list your dot files, display your shell configuration file and display system information (hardware+software) | `ls` `less` `nano` `source` `PS1` [github guide](https://dotfiles.github.io) [neofetch](https://github.com/dylanaraps/neofetch) |
| get familiar with basic commands, reading documentation and editing files | browse and view files on your system | `man` `vim` [pacvim](https://github.com/jmoon018/PacVim) [ranger](https://ranger.github.io/) [lf](https://github.com/gokcehan/lf) [bash guide](https://github.com/Idnan/bash-guide) [error correction](https://github.com/nvbn/thefuck) |
| connect to wireless network | list available networks and connect to one that requires web login | `nmcli` `curl` `wpa_supplicant` [http-prompt](https://github.com/eliangcs/http-prompt) |
| become productive with a todo list | create a list of todos, edit, delete, and check some of them | [todo.txt](http://todotxt.org/) [todo.txt-cli](https://github.com/todotxt/todo.txt-cli) [task](https://taskwarrior.org/docs/start.html)|
| check the weather | fetch the weather forecast for your home city and one more city that you want to travel to | [wttr](https://github.com/chubin/wttr.in) |
| fetch information | read the business news | [awesome-console-services](https://github.com/chubin/awesome-console-services) |
| try different text-based web browsers and get used to the keyboard shortcuts for one | use your favorite text-based browser to retrieve information from the web | [lynx](https://lynx.browser.org/) [w3m](http://w3m.sourceforge.net/) [links](http://links.twibright.com/) |
| manage your bookmarks | add, search, and visit a bookmark to your favorite site | [buku](https://github.com/jarun/Buku) |
| search the web from the terminal |create aliases for common searches such as dictionary definition | [googler](https://github.com/jarun/googler) [ddgr](https://github.com/jarun/ddgr) |
| twitter | display your personal stream and that of your favorite person | [twitter](https://github.com/orakaro/rainbowstream) |
| browse popular web sites through the terminal | configure the browser environment to you terminal browser | [hacker news](https://github.com/donnemartin/haxor-news) [reddit](https://github.com/michael-lazar/rtv) `BROWSER` [awesome-finder](https://github.com/mingrammer/awesome-finder) |
| read an ebook | read, search, bookmark, and annotate your favorite ebook | [epr](https://github.com/wustho/epr) |
| manage torrent files | search and download a torrent | [torque](https://github.com/dylanaraps/torque) |
| edit a spreadsheet | edit values and formulas | [sc-im](https://github.com/andmarti1424/sc-im) |
| try a different shell | change your default shell to zsh and configure it with auto-completions-suggestions and repeat some of the above | `chsh` [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) [zsh-completions](https://github.com/zsh-users/zsh-completions) [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) |
| surf the web | create a new elvi | [surfraw](https://gitlab.com/surfraw/Surfraw) |
| manage and share your dot files | configure git, edit, push and pull your dot files among at least two different machines | [github guide](https://dotfiles.github.io) [rcm](https://github.com/thoughtbot/rcm) [dotfiles](https://github.com/jbernard/dotfiles) [stow](https://github.com/xero/dotfiles) [yadm](https://github.com/TheLocehiliosan/yadm) |
| share your calendar | share your calendar | [gcalcli](https://github.com/insanum/gcalcli)|
| transfer files to your phone | send an image file to your phone | [qr-filetransfer](https://github.com/sdushantha/qr-filetransfer) |
| upload and share files || [transfer](https://github.com/dutchcoders/transfer.sh/) [firefox send](https://github.com/timvisee/ffsend) |
| read the news with an RSS reader || [newsboat](https://github.com/newsboat/newsboat) |
| use irc to chat with your friends | create a room, invite friends, and chat| [weechat](https://weechat.org/) |
| back-up your home online | create a back-up schedule | `cron` `rsync` [rclone](https://github.com/rclone/rclone) |
| batch image conversion | convert your image files to different sizes and formats | `ImageMagick` `ufraw`|
| track your expenses | add a source of income and some expenses | [ledger](https://github.com/ledger/ledger) |
| track your time with a simple journal || [jrnl](https://github.com/jrnl-org/jrnl) |
| search the local file system | search for your shell configuration file and open it for editing and search for the contents of a text file | [fzf](https://github.com/junegunn/fzf) [skim](https://github.com/lotabout/skim) [percol](https://github.com/mooz/percol) |
| manage your music library | import your music library, add tags and delete/add songs | [beets](https://github.com/beetbox/beets) |
| visualize an mp3 | demonstrate album art and visualizations with an mp3 player and various songs | [mpd](https://github.com/MusicPlayerDaemon/MPD) [kunst](https://github.com/sdushantha/kunst) |
| organize your notes | add (edit and delete) and link several pages| [org-wiki](https://github.com/caiorss/org-wiki) [viki](https://github.com/tomtom/vikibase_vim) [nb](https://github.com/xwmx/nb) |
| create your final presentation | three slides with your name-AM-github, checkbox list of deliverables done, and highlights of significant contributions and/or roadblocks  | [mdp](https://github.com/visit1985/mdp) [patat](https://github.com/jaspervdj/patat) [present](https://github.com/vinayak-mehta/present) |
| manage your academic bibliography | import your bibtex formated bibliography, add, edit, delete an entry | [pubs](https://github.com/pubs/pubs) [papis](https://github.com/papis/papis) |
| organise the terminal window into multiple areas | use one window to search-edit local files or browse the web and another window for performance monitoring  | [tmux](https://en.wikipedia.org/wiki/Tmux), [glances](https://github.com/nicolargo/glances) |
| try different terminals and shells | repeat some of the previous exercises with a different terminal-shell and create a custom configuration that fits your needs | [st](https://github.com/LukeSmithxyz/st) [mosh](https://github.com/mobile-shell/mosh) `zsh` `fish` |


## hci

| assignments | deliverables | references |
| -- | -- | -- |
| download mp3 | search, download and play (with the terminal) your favorite song of the month from youtube | [youtube-dl](https://github.com/ytdl-org/youtube-dl) [mpv](https://github.com/mpv-player/mpv) |
| text editor and plug-ins for code highlighting and autocompletion | edit the vim or the shell configuration file | [vim](https://www.vim.org/) |
| organize your notes with emacs | use org mode | `emacs` |
| format your report | use text formating tools to layout your final report | [groff](https://www.gnu.org/software/groff/manual/html_node/index.html) |
| create your own static site and blog generator with pandoc | the generator should consider posts, pages, and templates | [bashyll](https://github.com/faithanalog/bashyll) [pandoc+makefile](https://tylercipriani.com/blog/2014/05/13/replace-jekyll-with-pandoc-makefile/) |
| add a status bar to your shell/editor and configure a color-theme | edit the configuration files for your status line and for your color theme | [status bar](https://github.com/powerline/powerline) [solarized](https://github.com/altercation/solarized) [redshift](https://github.com/jonls/redshift) [pywall](https://github.com/dylanaraps/pywal) |
| configure a custom desktop enviroment | customize the wallpaper, menu, bar, notifications, windows, screensaver and demonstrate them with a GIF | [polybar](https://github.com/polybar/polybar) [rofi](https://github.com/davatorium/rofi) [dunst](https://github.com/dunst-project/dunst) [awesome](https://github.com/awesomeWM/awesome) [pipes](https://github.com/pipeseroni/pipes.sh) [flashfocus](https://github.com/fennerm/flashfocus) |
| configure a custom window manager | try different wm and configure one to fit your needs| [sowm](https://github.com/dylanaraps/sowm) [dwm](https://dwm.suckless.org/) |
| convert between different text formats | use vim (or emacs) to write your cv in markdown, [track multiple formats](https://tex.stackexchange.com/questions/103244/git-latex-and-branches-workflow) with git and convert it to docx, html with pandoc | [pandoc](https://pandoc.org/) [git](https://en.wikipedia.org/wiki/Git) `sed` |


## cscw

| assignments | deliverables | references |
| -- | -- | -- |
| create a simple website with a static generator | single page with name-AM-github and links to your asciinema deliverables | [jekyll](https://github.com/jekyll/jekyll) [hakyll](https://github.com/jaspervdj/hakyll) [nikola](https://github.com/getnikola/nikola) [tclssg](https://github.com/tclssg/tclssg) |
| read, write, and send email | configure mail server, display greek characters, display rich content, open links in text-based browser, store attachments, compose email with vim | [mutt](http://www.mutt.org/) `EDITOR` `URLVIEW` [aerc](https://aerc-mail.org/) |
| connect to a remote machine with ssh | configure a remote machine to do all the previous tasks and connect to it through a simple local machine | `ssh` [mosh](https://github.com/mobile-shell/mosh)|
| send rich email with emacs | filter and send emails with links | [emacs](https://www.gnu.org/software/emacs/) [reading-and-writing-email-with-emacs](https://emacs.stackexchange.com/questions/12927/reading-and-writing-email-with-emacs) |
| pair programming | edit a text file together with a friend | [tmate](https://github.com/tmate-io/tmate) |

## visualization

| assignments | deliverables | references |
| -- | -- | -- |
| visualize git commits | display your commits from a previous course, eg hci | [git-bars](https://github.com/knadh/git-bars) |
| generate plots | create plots for your data from some other course or project | [plot](https://github.com/asmuth/clip) |
| analyse web log files | create reports similar to google analytics | [goaccess](https://github.com/allinurl/goaccess) |
| use color to improve your cli tools | Print colorized text from a shell script, in order to make it more beautiful-usable | [pastel](https://github.com/sharkdp/pastel) |
| visualize your data | demo with your git commits history and percipation data per day for the last month from your city | [spark](https://github.com/holman/spark) |
| convert you cli to gui | convert one of the previous python tools to gui | [gooey](https://github.com/chriskiehl/Gooey) |
| create a cv | build your cv with latex in pdf format, upload it, and track it with git lfs | `latex` `git lfs` |
| visualize a large text file with a word cloud | use a book from project gutenberg or from the daily news and mask the word cloud with an image that fits the theme of the book | [word_cloud](http://amueller.github.io/word_cloud/auto_examples/index.html) [newspaper](https://github.com/codelucas/newspaper) [gutenberg](https://www.gutenberg.org/) |
| visualize progress or status | improve your favorite python cli app with a progress bar | [tqdm](https://github.com/tqdm/tqdm) |
| give rainbow power to your cli python program | visualize your code, tables, markdown, and programs | [rich](https://github.com/willmcgugan/rich) |
| add icons to your terminal workflow | | [icons-in-terminal](https://github.com/sebastiencs/icons-in-terminal) [awesome terminal fonts](https://github.com/gabrielelana/awesome-terminal-fonts) |

## software

| assignments | deliverables | references |
| -- | -- | -- |
| set-up continuous integration | build and deploy your static site and your cv dynamically every time you make a small change in the source files | `github` `travis` `netlify` |
| use the terminal as an IDE | edit your files (e.g., cv, website, code, etc) in vim or emacs and compile it in a different panel or use a plug-in | [latex](https://www.latex-project.org/) [vimtex](https://github.com/lervag/vimtex) [spacevim](https://spacevim.org/) [doom-emacs](https://github.com/hlissner/doom-emacs) [make](https://www.gnu.org/software/make/) [just](https://github.com/casey/just) [tmex](https://github.com/evnp/tmex) |
| set-up a system for python development| install and configure *in a user folder* a python project that is not available through the package manager| [python virtual environments](https://docs.python-guide.org/dev/virtualenvs/) |
| send notifications to your desktop-mobile | send a notifcation when a big task completes, eg download, compiling, etc | [ntfy](https://github.com/dschep/ntfy) |
| create notifications on your sever | send notifications on important server events | [mqttwarn](https://github.com/jpmens/mqttwarn) |
| create your own static site and blog generator | the generator should consider posts, pages, and templates | [bashblog](https://github.com/cfenollosa/bashblog) [jenny](https://github.com/hmngwy/jenny) [bashyll](https://github.com/faithanalog/bashyll) [kiss linux blog](https://github.com/kisslinux/website) [pandoc+makefile](https://tylercipriani.com/blog/2014/05/13/replace-jekyll-with-pandoc-makefile/) |
| try different operating systems in the emulator | load at least two operating systems without a GUI (only CLI) and create a virtual local network | [qemu](https://www.qemu.org/) `freebsd` `archlinux` `alpine` |
| set-up cloud services | ssh to a remote machine and demonstrate your remote cli user land (e.g., email, editor, cv, code, etc) | [OpenSSH](https://www.openssh.com) [Cloud Stack](https://en.wikipedia.org/wiki/Apache_CloudStack) |
| create an agent for news | the demo should display the new content added on a news web site | [huginn](https://github.com/huginn/huginn) |
| programmable voice | deploy an application that forwards a call depending on a white- and black- list of phone numbers | [twilio-python](https://github.com/twilio/twilio-python) |
| choose your stack | set-up an OS image with a set of cli tools with minimal dependencies and a software licence that allows commercial use and selling | [freebsd](https://www.freebsd.org) |
| performance monitoring | monitor the performance of your python scripts and visualize them with colors and/or spark lines | [py-spy](https://github.com/benfred/py-spy) [hyperfine](https://github.com/sharkdp/hyperfine) |
| create a docker image for your development stack | demonstrate the custom image for CI of your cv and site | [dry](https://github.com/moncho/dry) [dockly](https://github.com/lirantal/dockly) [alpine](https://hub.docker.com/_/alpine) |
| create a cli app for your favorite site | the application should be similar to rtv, haxor from hci | [click](https://github.com/pallets/click) |
| create a minimal linux system for a particular purpose | gif of a VM with your custom (init, libc) linux system should boot to a terminal and include a set of tools that you really need (e.g., secure, minimal, aesthetics, libraries, etc) | [LFS](http://www.linuxfromscratch.org/) [suckless](https://suckless.org/) [kiss linux](https://k1ss.org) [init systems](https://wiki.gentoo.org/wiki/Comparison_of_init_systems) [libc](http://www.etalabs.net/compare_libcs.html) |

# manuals

The majority of cli tools include either a `man` page, or a short help (`-h`) screen. The following tools provide common examples about common tools:

- [cheat](https://github.com/cheat/cheat)
- [tldr](https://tldr.sh/)
- [navi](https://github.com/denisidoro/navi)
- [howdoi](https://github.com/gleitz/howdoi)

# tutorials

The assignments assume some basic knowledge and skills, which can be acquired promptly through the following tutorials:

- [shell](http://swcarpentry.github.io/shell-novice/)
- [git](http://swcarpentry.github.io/git-novice/)
- [python](https://swcarpentry.github.io/python-novice-inflammation/)

# references

The references in the assignments are only indicative and you are strongly encouraged to search for and evaluate alternatives. There are several resources that provide information about terminal and command-line applications, such as:

[You Dont Need GUI](https://github.com/you-dont-need/You-Dont-Need-GUI)

[the art of command-line](https://github.com/jlevy/the-art-of-command-line)

[terminal blog](https://blog.balthazar-rouberol.com/tag/terminal)

[inconsolation blog](https://inconsolation.wordpress.com/)

[awesome command-line applications](https://github.com/agarrharr/awesome-cli-apps)

[awesome shell](https://github.com/alebcay/awesome-shell)

[awesome bash](https://github.com/awesome-lists/awesome-bash)

[terminals are sexy](https://github.com/k4m4/terminals-are-sexy)

[graphical user interfaces are good for 2 years old](https://www.youtube.com/watch?v=SdL6dzWvm5M)

[cool unix tools](https://kkovacs.eu/cool-but-obscure-unix-tools)

[unix toolbox](http://cb.vu/unixtoolbox.xhtml)

[Coderwall](https://coderwall.com/t/command-line/popular)

