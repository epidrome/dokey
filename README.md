# dokey
> real men do it with the keyboard 
-old unix admin saying

# dependencies
* unix-based system (e.g., macos, linux, bsd, etc), might work on windows [with add-ons](https://en.wikipedia.org/wiki/Windows_Subsystem_for_Linux)
* [terminal emulator](https://en.wikipedia.org/wiki/Terminal_emulator)
* [command line](https://en.wikipedia.org/wiki/Command-line_interface)
* [python](https://docs.python-guide.org/starting/installation/)
* [asciinema](https://asciinema.org/) to record and share your sessions as described in the deliverables

# assignments and deliverables
| assignments | deliverables | references |
| -- | -- | -- |
|  | **user land** |  |
| set-up the main dependencies and demonstrate your base system | change your command prompt, list your dot files, display your shell configuration file and display system information (hardware+software) | [cheat](https://github.com/cheat/cheat) [tldr](https://tldr.sh/) `ls` `less` `nano` `source` `PS1` [neofetch](https://github.com/dylanaraps/neofetch) |
| get familiar with basic commands, reading documentation and editing files | browse and view files on your system | `man` `vim` [ranger](https://ranger.github.io/) [bash guide](https://github.com/Idnan/bash-guide) [error correction](https://github.com/nvbn/thefuck) |
| become productive with a todo list | create a list of todos, edit, delete, and check some of them | [todo.txt](http://todotxt.org/) [task](https://taskwarrior.org/docs/start.html)|
| plan your time with a calendar | add, edit, search for an appointment | [calcurse](https://calcurse.org/) |
| organize your notes with a wiki || []() |
| track your expenses | add a source of income and some expenses | [ledger](https://github.com/ledger/ledger) |
| track your time with a simple journal || [jrnl](https://github.com/jrnl-org/jrnl) |
| add a status bar to your shell/editor and configure a color-theme | edit the configuration files for your status line and for your color theme | [status bar](https://github.com/powerline/powerline) [solarized](https://github.com/altercation/solarized) [redshift](https://github.com/jonls/redshift) [pywall](https://github.com/dylanaraps/pywal) |
| build a custom desktop enviroment | customize the wallpaper, menu, bar, notifications, windows, screensaver and demonstrate them with a GIF | [polybar](https://github.com/polybar/polybar) [rofi](https://github.com/davatorium/rofi) [dunst](https://github.com/dunst-project/dunst) [awesome](https://github.com/awesomeWM/awesome) [pipes](https://github.com/pipeseroni/pipes.sh) |
| text editor and plug-ins for code highlighting and autocompletion | edit the vim or the shell configuration file | [vim](https://www.vim.org/) |
| search the local file system | search for your shell configuration file and open it for editing | [fzf](https://github.com/junegunn/fzf) |
| organise the terminal window into multiple areas | use one window to search-edit local files or browse the web and another window for performance monitoring  | [tmux](https://en.wikipedia.org/wiki/Tmux), [glances](https://github.com/nicolargo/glances) |
|  | **work online** |  |
| connect to wireless network | list available networks and connect to one that requires web login | `nmcli` `curl` `wpa_supplicant` [http-prompt](https://github.com/eliangcs/http-prompt) |
| check the weather | fetch the weather forecast for your home city and one more city that you want to travel to | [wttr](https://github.com/chubin/wttr.in) |
| use git to share your dot files | configure git, edit and push your dot files | [git](https://en.wikipedia.org/wiki/Git) |
| share your files online and along devices || [gcalcli](https://github.com/insanum/gcalcli)|
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
| connect to a remote machine with ssh | configure a remote machine to do all the previous tasks and connect to it through a simple local machine ||
|  | **rich content** |  |
| download mp3 | search, download and play (with the terminal) your favorite song of the month from youtube | [youtube-dl](https://github.com/ytdl-org/youtube-dl) [mpv](https://github.com/mpv-player/mpv) |
| visualize an mp3 | demonstrate album art and visualizations with an mp3 player and various songs | [mpd](https://github.com/MusicPlayerDaemon/MPD) [kunst](https://github.com/sdushantha/kunst) |
| manage your music library | import your music library, add tags and delete/add songs | [beets](https://github.com/beetbox/beets) |
| watch video | youtube video streaming | |
| download a torrent || [torque](https://github.com/dylanaraps/torque) [transmission-cli]() |
| edit a spreadsheet | edit values and formulas | [sc-im](https://github.com/andmarti1424/sc-im) |
| visualize your data | demo with your git commits history and percipation data per day for the last month from your city | [spark](https://github.com/holman/spark) |
| convert between different text formats | use vim to write your cv in markdown and convert it to docx, html | [pandoc](https://pandoc.org/) |
| create a simple website with a static generator | single page with name-AM-github and links to your asciinema deliverables | [jekyll](https://github.com/jekyll/jekyll) [hakyll](https://github.com/jaspervdj/hakyll) [nikola](https://github.com/getnikola/nikola) |
| visualize progress or status | improve your favorite python cli app with a progress bar | [tqdm](https://github.com/tqdm/tqdm) |
| create your final presentation | three slides with your name-AM-github, checkbox list of deliverables done, and highlights of significant contributions and/or roadblocks  | [mdp](https://github.com/visit1985/mdp) [patat](https://github.com/jaspervdj/patat) |
|  | **dev ops** |  |
| use the terminal as an IDE | edit your cv in vim and compile it in a different panel or use a plug-in | [latex](https://www.latex-project.org/) [vimtex](https://github.com/lervag/vimtex) |
| set-up a system for python development| install and configure *in a user folder* a python project that is not available through the package manager| [python virtual environments](https://docs.python-guide.org/dev/virtualenvs/) |
| set-up cloud services | ssh to a remote machine and demonstrate your cli user land | [OpenSSH](https://www.openssh.com) [Cloud Stack](https://en.wikipedia.org/wiki/Apache_CloudStack) |
| choose your stack || [howdoi](https://github.com/gleitz/howdoi) |
| set-up continuous integration |||
| create a docker image for your stack || [dry](https://github.com/moncho/dry) [dockly](https://github.com/lirantal/dockly) |
| configure headless services |||

# references

the above references are only indicative and you are strongly encouraged to search for and evaluate alternatives. There are several resources that provide information about terminal applications, such as:

[inconsolation blog](https://inconsolation.wordpress.com/)

[awesome command-line applications](https://github.com/agarrharr/awesome-cli-apps)

[awesome shell](https://github.com/alebcay/awesome-shell)

[terminals are sexy](https://github.com/k4m4/terminals-are-sexy)

[graphical user interfaces are good for 2 years old](https://www.youtube.com/watch?v=SdL6dzWvm5M)

[cool unix tools](https://kkovacs.eu/cool-but-obscure-unix-tools)

# grading

Passing grade is awarded as soon as you post to asciinema a demo of basic usage with default options. The grade improves for each extra configuration that you demonstrate and becomes excellent as soon as you find a similar tool or for significantly novel uses.
