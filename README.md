# rubyslippers
Modernize your shell and (optionally) install a yaml list of favorite tools with as little as one copy/paste. 


### "There's no place like $HOME."

Currently a work in progress. I've had various versions of something like this to manage dotfiles over the years but, it's time for a major rewrite and why not make it public this time? 

A one-line do it all to set up your shell with reasonable defaults, fix common errors, add a $HOME/bin/ if it's not present and path it first. Will also support keeping a shared set of environment variables in a private repo or some secret store that makes sense. 

I also plan to revive "s", which was at one point a tiny bit popular. It could use a cleanup/rewrite as well. It is possible it will be rolled into a package of rubyslippers.

*If* I dropped the "must run on any reasaonable bash where ssh-keygen and ssh have same options" requirement, and that's an if, I have some thoughts on integration with mosh, getting rid of lots of keyfiles and storing them in sqlite, or semi-secure remote storage (like DynamoDB, maybe?), or portable storage (usb key), or "cloud" (.sqlite on Dropbox/OneDrive? Private gist (kind of a bad idea).

#### Feature List

- Zip, bang. Oh My Bash with some extras configured.
- Support for auto virtual environments on dir change. Configure by projects. 
- Per directory theme support (keeps you sane when working on several repos)
- JR "Bob" Dobs, or Banksy. May eventually make this a theme submission thing.
- I want ANSI login art. Yes, I was a BBS kid. Sue me. 
- Detect support for extended unicode and svg in the terminal? Use where available. Treat it like the web treated "progressive enhancement"
- Use 256 color shell support where available. Treat it like the web treated "progressive enhancement"
- Have one mission and do it well... make any shell feel like $HOME / Autofix some common nags on various unix and terminals.
- On/Off in session. Can set default to on or off. 
- Lots and lots of quick-references for things? Wiki manual with excellent Lynx support? Companion app (could two factor as well for secret store)

