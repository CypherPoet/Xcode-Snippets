# Custom Xcode Snippets ✂️

_Custom Code Snippets for Xcode._


Xcode gives us the ability to create custom code snippets by highlighting a block of code, right-clicking, and then selecting the `Create Code Snippet` option.

For each custom snippet that's created, there is a file stored in the following directory:

```zsh
~/Library/Developer/Xcode/UserData/CodeSnippets/
```

_(The assumption being that `~/Library/Developer/Xcode/` is the path to your Xcode developer directory)._

But what if we want to share these snippets across devices? That's where it helps to store them in a git repo 💪.

Simply download the files here, or clone the repo, and copy whichever `.codesnippet` file you want to use into the directory above.

**Quick-Start Example:**

```zsh
cp -r ./snippets/**/*.codesnippet ~/Library/Developer/Xcode/UserData/CodeSnippets/
```

Those files are plain `plist` documents using a random UUID as a name and having the `.codesnippet` file extension.

From there, feel free to use this repo as a starting point or reference for your own snippets! ⚡️
