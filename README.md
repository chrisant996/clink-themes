# clink-themes

A site for sharing Clink color themes and custom prompts.

> [!IMPORTANT]
> Custom prompts shared in this repo are contributed by users of Clink.  They may not have been tested thoroughly, and using them on a different computer than the author's computer might reveal unexpected problems.  If you find problems, open an issue in this repo -- or if there's a link to a separate repo for the custom prompt then open an issue in its separate repo.
>
> As with any software, decide whether you trust the author of a custom prompt before trying to use the custom prompt.  That should go without saying for all software -- but I'm calling it out here because it might not be obvious that custom prompts are software just like any other software, and could have unexpected effects.

### Installation

The recommended way to install is to clone this repo:
1. Clone this repo to your computer, for example with `git clone https://github.com/chrisant996/clink-themes.git c:\repos\clink-themes`.
2. Let Clink know where to find the themes, for example with `clink installscripts c:\repos\clink-themes`.

Or you can download individual .clinktheme and .clinkprompt files to a directory on your computer, and give Clink the full path name to the file.  For example you could download the [Sample.clinkprompt](https://github.com/chrisant996/clink-themes/blob/main/themes/Sample.clinkprompt) file and save it into a "c:\MyTools\" directory, with `clink config prompt use c:\MyTools\Sample`.

### Why Does It Look Different On My Computer?

You may see screenshots for a custom prompt and try it out, but find that it doesn't look the same for you.

If you see strange symbols, then you probably need to also use a [Nerd Font](https://nerdfonts.com) or a [Powerline Font](https://github.com/powerline/fonts) in order for the custom prompt to display properly.  These fonts include special symbols and icons, and many custom prompts use them to add stylistic flair or indicator icons.

Or you may need to also configure the custom prompt to turn on (or off) its features, or to choose colors or modes or what to include in the prompt display.  Consult each custom prompt's documentation for its specific customization information (the information is usually found near the top of the corresponding .clinkprompt file).

> [!NOTE]
> Clink color themes only control Clink's own colors.  They don't affect the rest of the terminal window, and they don't affect other programs.
>
> Clink custom prompts only control what your prompt looks like (the text you see before where you'll type your commands).
>
> To configure terminal colors and features, consult the documentation for your terminal program.

### Color Themes

Visit [here](/themes/COLORTHEMES.md) for a list of color themes in this repo.

### Custom Prompts

Visit [here](/themes/CUSTOMPROMPTS.md) for a list of custom prompts in this repo.

### More Information

Refer to [Color Themes](https://chrisant996.github.io/clink/clink.html#color-themes) and [Custom Prompts](https://chrisant996.github.io/clink/clink.html#custom-prompts) in the Clink documentation for information on creating and using color themes and custom prompts.

### Contributing

Do you have a color theme or custom prompt you want to share here?

1. Create a fork of this repo in GitHub.
2. Create a topic branch in your forked repo.
3. Add your file(s) in the topic branch.
   - In comments at the top of the .clinktheme or .clinkprompt file(s), note the license for the theme or prompt, if applicable.
   - Optionally include a screen shot of the theme (recommended).
   - Add a section in the [COLORTHEMES.md](/themes/COLORTHEMES.md) or [CUSTOMPROMPTS.md](/themes/CUSTOMPROMPTS.md) file for your color theme or custom prompt.
4. Push your changes to GitHub.
5. Create a Pull Request from your topic branch to the main clink-themes repo.

For more detailed information on each step, consult git documentation and GitHub documentation.

### License

.clinktheme and .clinkprompt files are assumed to be Public Domain unless stated otherwise inside the file.
