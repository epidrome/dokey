# Οδηγίες

Το κάθε μάθημα έχει διαφορετικό σετ ασκήσεων τις οποίες θα βρείτε κάτω από τον αντίστοιχο τίτλο. Το κάθε σετ έχει περισσότερες από 10 ασκήσεις οι οποίες εμφανίζονται με σειρά δυσκολίας από την πιο εύκολη στην πιο δύσκολη.  Αν γίνουν περισσότερες τότε θα κρατήσουμε τους 4 καλύτερους βαθμούς, αρκεί να έχουν έχουν γίνει commit τα λινκ μέσα στην αναφορά σας στις παρακάτω προθεσμίες. **Για να βαθμολογηθεί μια άσκηση θα πρέπει [το command prompt να είναι ο ΑΜ σας](https://unix.stackexchange.com/questions/35777/how-to-change-the-prompt-in-linux).** Για περισσότερες οδηγίες δείτε την ενότητα της βαθμολόγησης παρακάτω.

# Προθεσμίες

| Άσκηση | Προθεσμία |
| -- | -- |
| 1 | 20 Οκτ.|
| 2 | 3 Νοε. |
| 3 | 17 Νοε. |
| 4 | 1 Δεκ. |
| 5 | 14 Δεκ. | 
| 6 | 12 Ιαν. |

**Οι παραπάνω προθεσμίες είναι για τα commit στην αναφορά σας, η οποία [αποστέλεται σε διαφορετικές ημερομηνίες με pull-request στο κεντρικό](https://courses-ionio.github.io/help/deadlines/).**

# dokey
> real men do it with the keyboard 
-old unix admin saying

# dependencies
* unix-based system (e.g., macos, linux, bsd, etc), might work on recent versions of windows [with add-ons](https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux) or with older windows and a [virtualbox](https://www.virtualbox.org/) unix installation
* [terminal emulator](https://en.wikipedia.org/wiki/Terminal_emulator)
* [command line](https://en.wikipedia.org/wiki/Command-line_interface)
* [python](https://docs.python-guide.org/starting/installation/)
* [asciinema](https://asciinema.org/) to record and share your sessions as described in the deliverables

# assignments and deliverables

- [hci](#hci): user land
- [cscw](#cscw): work online
- [multimedia](#multimedia): rich content
- [software](#software): dev ops


## hci

| assignments | deliverables | references |
| -- | -- | -- |
| set-up the main dependencies and demonstrate your base system | change your command prompt with your student ID, list your dot files, display your shell configuration file and display system information (hardware+software) | [cheat](https://github.com/cheat/cheat) [tldr](https://tldr.sh/) `ls` `less` `nano` `source` `PS1` [neofetch](https://github.com/dylanaraps/neofetch) |
| get familiar with basic commands, reading documentation and editing files | browse and view files on your system | `man` `vim` [ranger](https://ranger.github.io/) [bash guide](https://github.com/Idnan/bash-guide) [error correction](https://github.com/nvbn/thefuck) |
| become productive with a todo list | create a list of todos, edit, delete, and check some of them | [todo.txt](http://todotxt.org/) [todo.txt-cli](https://github.com/todotxt/todo.txt-cli) [task](https://taskwarrior.org/docs/start.html)|
| plan your time with a calendar | add, edit, search for an appointment | |
| text editor and plug-ins for code highlighting and autocompletion | edit the vim or the shell configuration file | [vim](https://www.vim.org/) |
| organize your notes with emacs | use org mode | `emacs` |
| organize your notes with a wiki | use vi or emacs org-mode to add (edit and delete) and link several pages| [org-wiki](https://github.com/caiorss/org-wiki) [viki](https://github.com/tomtom/vikibase_vim) |
| track your expenses | add a source of income and some expenses | [ledger](https://github.com/ledger/ledger) |
| track your time with a simple journal || [jrnl](https://github.com/jrnl-org/jrnl) |
| add a status bar to your shell/editor and configure a color-theme | edit the configuration files for your status line and for your color theme | [status bar](https://github.com/powerline/powerline) [solarized](https://github.com/altercation/solarized) [redshift](https://github.com/jonls/redshift) [pywall](https://github.com/dylanaraps/pywal) |
| build a custom desktop enviroment | customize the wallpaper, menu, bar, notifications, windows, screensaver and demonstrate them with a GIF | [polybar](https://github.com/polybar/polybar) [rofi](https://github.com/davatorium/rofi) [dunst](https://github.com/dunst-project/dunst) [awesome](https://github.com/awesomeWM/awesome) [pipes](https://github.com/pipeseroni/pipes.sh) |
| convert between different text formats | use vim (or emacs) to write your cv in markdown, track multiple versions with git and convert it to docx, html with pandoc | [pandoc](https://pandoc.org/) [git](https://en.wikipedia.org/wiki/Git) |
| search the local file system | search for your shell configuration file and open it for editing and search for the contents of a text file | [fzf](https://github.com/junegunn/fzf) [percol](https://github.com/mooz/percol) |
| organise the terminal window into multiple areas | use one window to search-edit local files or browse the web and another window for performance monitoring  | [tmux](https://en.wikipedia.org/wiki/Tmux), [glances](https://github.com/nicolargo/glances) |
| try a different shell | change your default shell to zsh and configure it with auto-completions-suggestions and repeat some of the above | `chsh` [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) [zsh-completions](https://github.com/zsh-users/zsh-completions) [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) |


## cscw

| assignments | deliverables | references |
| -- | -- | -- |
| connect to wireless network | list available networks and connect to one that requires web login | `nmcli` `curl` `wpa_supplicant` [http-prompt](https://github.com/eliangcs/http-prompt) |
| check the weather | fetch the weather forecast for your home city and one more city that you want to travel to | [wttr](https://github.com/chubin/wttr.in) |
| fetch information | read the business news | [awesome-console-services](https://github.com/chubin/awesome-console-services) |
| manage and share your dot files | configure git, edit and push your dot files | [rcm](https://github.com/thoughtbot/rcm) [dotfiles](https://github.com/jbernard/dotfiles) [stow](https://github.com/xero/dotfiles) |
| share your files online and along devices | share your calendar | [gcalcli](https://github.com/insanum/gcalcli)|
| try different text-based web browsers and get used to the keyboard shortcuts for one | use your favorite text-based browser to retrieve information from the web | [lynx](https://lynx.browser.org/) [w3m](http://w3m.sourceforge.net/) [links](http://links.twibright.com/) |
| manage your bookmarks | add, search, and visit a bookmark to your favorite site | [buku](https://github.com/jarun/Buku) |
| search the web from the terminal |create aliases for common searches such as dictionary definition | [googler](https://github.com/jarun/googler) [ddgr](https://github.com/jarun/ddgr) |
| twitter | display your personal stream and that of your favorite person | [twitter](https://github.com/orakaro/rainbowstream) |
| browse popular web sites through the terminal | configure the browser environment to you terminal browser | [hacker news](https://github.com/donnemartin/haxor-news) [reddit](https://github.com/michael-lazar/rtv) `BROWSER` [awesome-finder](https://github.com/mingrammer/awesome-finder) |
| upload and share files || [transfer](https://github.com/dutchcoders/transfer.sh/) [firefox send](https://github.com/timvisee/ffsend) |
| read the news with an RSS reader || [newsboat](https://github.com/newsboat/newsboat) |
| use irc to chat with your friends | create a room, invite friends, and chat| [weechat](https://weechat.org/) |
| back-up your home online | | `rsync` [rclone](https://github.com/rclone/rclone) |
| read, write, and send email | configure mail server, display greek characters, display rich content, open links in text-based browser, store attachments, compose email with vim | [mutt](http://www.mutt.org/) `EDITOR` `URLVIEW` |
| connect to a remote machine with ssh | configure a remote machine to do all the previous tasks and connect to it through a simple local machine | `ssh` [mosh](https://github.com/mobile-shell/mosh)|
| send rich email with emacs | filter and send emails with links | [emacs](https://www.gnu.org/software/emacs/) [reading-and-writing-email-with-emacs](https://emacs.stackexchange.com/questions/12927/reading-and-writing-email-with-emacs) |
| pair programming | edit a text file together with a friend | [tmate](https://github.com/tmate-io/tmate) |

## multimedia

| assignments | deliverables | references |
| -- | -- | -- |
| download mp3 | search, download and play (with the terminal) your favorite song of the month from youtube | [youtube-dl](https://github.com/ytdl-org/youtube-dl) [mpv](https://github.com/mpv-player/mpv) |
| edit a spreadsheet | edit values and formulas | [sc-im](https://github.com/andmarti1424/sc-im) |
| read an ebook | read, search, bookmark, and annotate your favorite ebook | [](https://github.com/wustho/epr) |
| manage torrent files | search and download a torrent | [torque](https://github.com/dylanaraps/torque) [transmission-cli]() |
| manage your music library | import your music library, add tags and delete/add songs | [beets](https://github.com/beetbox/beets) |
| visualize an mp3 | demonstrate album art and visualizations with an mp3 player and various songs | [mpd](https://github.com/MusicPlayerDaemon/MPD) [kunst](https://github.com/sdushantha/kunst) |
| batch image conversion | convert your image files to different sizes and formats | `ImageMagick` `ufraw`|
| watch video | youtube video streaming with asciiart | |
| visualize your data | demo with your git commits history and percipation data per day for the last month from your city | [spark](https://github.com/holman/spark) |
| create a simple website with a static generator | single page with name-AM-github and links to your asciinema deliverables | [jekyll](https://github.com/jekyll/jekyll) [hakyll](https://github.com/jaspervdj/hakyll) [nikola](https://github.com/getnikola/nikola) |
| create your final presentation | three slides with your name-AM-github, checkbox list of deliverables done, and highlights of significant contributions and/or roadblocks  | [mdp](https://github.com/visit1985/mdp) [patat](https://github.com/jaspervdj/patat) |
| manage your academic bibliography | import your bibtex formated bibliography, add, edit, delete an entry | [pubs](https://github.com/pubs/pubs) [papis](https://github.com/papis/papis) |
| visualize a large text file with a word cloud | use a book from project gutenberg or from the daily news and mask the word cloud with an image that fits the theme of the book | [word_cloud](http://amueller.github.io/word_cloud/auto_examples/index.html) [newspaper](https://github.com/codelucas/newspaper) [gutenberg](https://www.gutenberg.org/) |
| visualize progress or status | improve your favorite python cli app with a progress bar | [tqdm](https://github.com/tqdm/tqdm) |

## software

| assignments | deliverables | references |
| -- | -- | -- |
| try different terminals and shells | repeat some of the previous exercises with a different terminal-shell and create a custom configuration that fits your needs | [st](https://github.com/LukeSmithxyz/st) [mosh](https://github.com/mobile-shell/mosh) |
| configure a custom window manager | try different wm and configure one to fit your needs| [sowm](https://github.com/dylanaraps/sowm) |
| use the terminal as an IDE | edit your cv in vim and compile it in a different panel or use a plug-in | [latex](https://www.latex-project.org/) [vimtex](https://github.com/lervag/vimtex) |
| set-up a system for python development| install and configure *in a user folder* a python project that is not available through the package manager| [python virtual environments](https://docs.python-guide.org/dev/virtualenvs/) |
| create your own static site and blog generator | the generator should consider posts, pages, and templates | [blag](https://github.com/dylanaraps/blag) |
| try different operating systems in the emulator | load at least two operating systems and create a virtual local network | [qemu](https://www.qemu.org/) |
| set-up cloud services | ssh to a remote machine and demonstrate your remote cli user land | [OpenSSH](https://www.openssh.com) [Cloud Stack](https://en.wikipedia.org/wiki/Apache_CloudStack) |
| programmable voice | deploy an application that forwards a call depending on a white and black list of phone numbers | [twilio-python](https://github.com/twilio/twilio-python) |
| choose your stack | set-up a set of cli tools with minimal dependencies | [howdoi](https://github.com/gleitz/howdoi) |
| set-up continuous integration |||
| create a docker image for your stack || [dry](https://github.com/moncho/dry) [dockly](https://github.com/lirantal/dockly) [alpine](https://hub.docker.com/_/alpine) |
| configure headless services |||
| create a minimal linux system for a particular purpose | your custom linux system should boot to a terminal and include a minimal set of tools that you really need | [LFS](http://www.linuxfromscratch.org/) [suckless](https://suckless.org/) |

# references

the above references are only indicative and you are strongly encouraged to search for and evaluate alternatives. There are several resources that provide information about terminal and command-line applications, such as:

[the art of command-line](https://github.com/jlevy/the-art-of-command-line)

[inconsolation blog](https://inconsolation.wordpress.com/)

[awesome command-line applications](https://github.com/agarrharr/awesome-cli-apps)

[awesome shell](https://github.com/alebcay/awesome-shell)

[terminals are sexy](https://github.com/k4m4/terminals-are-sexy)

[graphical user interfaces are good for 2 years old](https://www.youtube.com/watch?v=SdL6dzWvm5M)

[cool unix tools](https://kkovacs.eu/cool-but-obscure-unix-tools)

[unix toolbox](http://cb.vu/unixtoolbox.xhtml)

# grading

Passing grade is awarded as soon as you include in your project report a link to a post to asciinema (idle-time<0.5sec) that demonstrates basic usage with default options. The grade improves for each extra configuration added and becomes excellent as soon as you find a similar tool or for significantly novel uses. [Ncurses](https://en.wikipedia.org/wiki/Ncurses) is an interesting tool but it is not purely command line, so you might employ it at your own risk.
