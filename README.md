# Class Fixers
Class Fixers is a simple utility theme designed to make simple theming easier by making elements use proper CSS variables for coloring. This theme can be used to patch other themes that may have unthemed elements, or can be depended on by other themes. **This theme will not change how Discord looks by itself, it is just designed to fix styles for other themes.*

## Installation
Run the installation command for your operating system in the terminal and the theme will be installed! You may have to reload Discord for the installation to complete.
| Operating System    | Command                                                                                          |
| ------------------- | -----------------------------------------------------------------------------------------------  |
| Unix (macos, linux) | `cd powercord/src/Powercord/themes && git clone git@github.com:/RedDaedalus/pc-class-fixers.git` |
| Windows             | `cd powercord\src\Powercord\themes && git clone git@github.com:/RedDaedalus/pc-class-fixers.git` |

## Adding Class Fixers to your theme
Some themes may want to automatically load class fixers as part of their theme. To do so, add the following line to the top of the css:
```css
@import url("https://cdn.jsdelivr.net/gh/RedDaedalus/pc-class-fixers/theme.css");
```
This line will automatically bundle the proper theme into the file.