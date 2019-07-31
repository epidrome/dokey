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
| become productive with a todo list | create a list of todos, edit, delete, and check some of them | [todo.txt](http://todotxt.org/) |
| connect to wireless network | list available networks and connect to one that requires web login | `nmcli` `curl` |
| use git to share your dot files | configure git, edit and push your dot files | [git](https://en.wikipedia.org/wiki/Git) |
| get familiar with basic commands, reading documentation and editing files | browse and view files on your system | `man` `vim` [ranger](https://ranger.github.io/) |
| add a status bar to your shell/editor and configure a color-theme | edit the configuration files for your status line and for your color theme | [status bar](https://github.com/powerline/powerline) [solarized](https://github.com/altercation/solarized) |
| try different text-based web browsers and get used to the keyboard shortcuts for one | use your favorite text-based browser to retrieve information from the web | [lynx](https://lynx.browser.org/) [w3m](http://w3m.sourceforge.net/) [links](http://links.twibright.com/) |
| browse popular web sites through the terminal | configure the browser environment to you terminal browser | [hacker news](https://github.com/donnemartin/haxor-news) [reddit](https://github.com/michael-lazar/rtv) `BROWSER` |
| use irc to chat with your friends | create a room, invite friends, and chat| [weechat](https://weechat.org/) |
| build a custom desktop enviroment | customize the menu, bar, notifications, windows and use a GIF to demonstrate with an mp3 player | [polybar](https://github.com/polybar/polybar) [rofi](https://github.com/davatorium/rofi) [dunst](https://github.com/dunst-project/dunst) [mpd](https://github.com/MusicPlayerDaemon/MPD) [awesome](https://github.com/awesomeWM/awesome) |
| text editor and plug-ins for code highlighting and autocompletion | edit the vim or the shell configuration file | [vim](https://www.vim.org/) |
| search the local file system | search for your shell configuration file | [fzf](https://github.com/junegunn/fzf) |
| organise the terminal window into multiple areas | use one window to search-edit local files or browse the web and another window for performance monitoring  | [tmux](https://en.wikipedia.org/wiki/Tmux), [glances](https://github.com/nicolargo/glances) |
|  | **rich content** |  |
| search the web from the terminal |create aliases for common searches such as dictionary definition | [googler](https://github.com/jarun/googler) [ddgr](https://github.com/jarun/ddgr) |
| download mp3 | search, download and play (with the terminal) your favorite song of the month from youtube | [youtube-dl](https://github.com/ytdl-org/youtube-dl) [mpv](https://github.com/mpv-player/mpv) |
| watch video | youtube video streaming ||
| download a torrent || [torque](https://github.com/dylanaraps/torque) [transmission-cli]() |
| edit a spreadsheet | edit values and formulas | [sc-im](https://github.com/andmarti1424/sc-im) |
| convert between different text formats | use vim to write your cv in markdown and convert it to docx, html | [pandoc](https://pandoc.org/) |
| create a simple website with a static generator | single page with name-AM-github and links to your asciinema deliverables | [jekyll](https://github.com/jekyll/jekyll) [hakyll](https://github.com/jaspervdj/hakyll) [nikola](https://github.com/getnikola/nikola) |
| create your final presentation | three slides with your name-AM-github, checkbox list of deliverables done, and highlights of significant contributions and/or roadblocks  | [mdp](https://github.com/visit1985/mdp) [patat](https://github.com/jaspervdj/patat) |
| read, write, and send email | configure mail server, display greek characters, display rich content, open links in text-based browser, store attachments, compose email with vim | [mutt](http://www.mutt.org/) `EDITOR` `URLVIEW` |
|  | **dev ops** |  |
| use the terminal as an IDE | edit your cv in vim and compile it in a different panel or use a plug-in | [latex](https://www.latex-project.org/) [vimtex](https://github.com/lervag/vimtex) |
| set-up a system for python development| install and configure *in a user folder* a python project that is not available through the package manager| [python virtual environments](https://docs.python-guide.org/dev/virtualenvs/) |
| set-up cloud services | ssh to a remote machine and demonstrate your cli user land | [OpenSSH](https://www.openssh.com) [Cloud Stack](https://en.wikipedia.org/wiki/Apache_CloudStack) |
| set-up continuous integration |||
| create your docker image |||

# references

the above references are only indicative and you are strongly encouraged to search for and evaluate alternatives. There are several resources that provide information about terminal applications, such as:

[inconsolation blog](https://inconsolation.wordpress.com/)

[awesome command-line applications](https://github.com/agarrharr/awesome-cli-apps)

[graphical user interfaces are good for 2 years old](https://www.youtube.com/watch?v=SdL6dzWvm5M)

# grading

Passing grade is awarded as soon as you post to asciinema a demo of basic usage with default options. The grade improves for each extra configuration that you demonstrate and becomes excellent as soon as you find a similar tool or for significantly novel uses.
