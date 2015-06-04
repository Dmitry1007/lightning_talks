# How To MarkDown Like A Boss

## Markdown is a text-based markup language created by John Gruber in 2004 as a way to write in an easy-to-read format that can be converted into HTML. It uses a very simple formatting syntax of familiar punctuation and characters, which makes writing content for the web a faster and more intuitive experience.

## How to load your markdown files
### Go to your package control, install package, markdown preview and make sure it has revolunet in it's load path. 

### If you don't have a build shortcut for your editor go to your key bindings, Preferences --> Settings User and add

```ruby  
{ "keys": ["ctrl+b"], "command": "build" }
```

```css
.hey {
  padding: 5px; 
}

```
#### You'll ~~need an extended~~ color theme, I suggest Monokai Extended. Just Grab that from control __Package__ as *well*. 
  * Go Shopping
  * Workout
  * Here's a link to [Google](https://www.google.com)

#### Here's what a picture would look like [picture]: http://nice-cool-pics.com/data/media/30/cool_design_desktop_wallpaper__5045_.jpg

#### Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

#### Code stuff

```python
s = "Python syntax highlighting"
print s
```

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

