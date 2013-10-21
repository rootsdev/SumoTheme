# Sumo Theme based on Themestrap

**Themestrap** is a simple starter kit for constructing Twitter Bootstrap 3+ themes. It provides the skeleton
for a simple, maintainable theme that always uses code directly from Bootstrap with as little replacement as
possible.

## Themestrap's Philosophy

1. A theme should be built *on top* of the framework, with as little intrusive change as possible.
2. As the framework evolves, a theme should be easily updated to the latest version.

To this end, Themestrap provides you with two simple files to modify: **variables.less**
and **theme.less** (both in the `less` directory). You can tweak any and all of the Bootstrap variables 
in **variables.less** and support any additional code or classes you'd like in **theme.less**. The compiled
theme CSS includes the Bootstrap library and will automatically pick up any overrides from variables.

## Modifying this Theme

First start by cloning this repo:

    git clone https://github.com/rootsdev/SumoTheme.git
    
Install the node and bower modules:

    npm install
    bower install
    
Now you're ready to go! Simply edit `less/variables.less` and `less/theme.less` to your liking.
When you're ready, just run `grunt` and it will compile and minify the distribution for you.
You can also run `grunt watch` to automatically compile as you work.