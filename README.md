A Quick Introduction to React Native
------------------------------------

Slides for this repo are [here](https://docs.google.com/presentation/d/19-m21WXp1HrXUnoOZVBdFOSVRpgynCoG6uuLogWpU_Q/edit?usp=sharing).

This is a quick introduction to [React Native](http://facebook.github.io/react-native/) for my presentation to the [Portal](http://www.theportal.io/).

## Installing React Native

I skimmed over this in the presentation, but here's some more detailed instructions.

NOTE: React Native (and pretty much all iOS development) requires a Mac running OS X.  Apologies to any students who don't have access to one.

### Installing Requirements

First off, I installed iojs, the "new" fork of node.js.  I just used their package file here:

https://iojs.org/dist/latest/iojs-v3.3.0.pkg

For other requirements, I used homebrew.

If you're not familiar [Homebrew](http://brew.sh/), it's unofficial package manager for OSX (like Ubuntu's apt-get).  If you're doing any development on a Mac, it's usually the first thing you install.

Once you've got Homebrew (copy the command on the homepage to install it if you haven't yet), you can do the following in a Terminal:

```bash
# You could install node.js or iojs through brew as well if you didn't install the .pkg above
# brew install node

# watchman is a better file watcher, it makes Cmd+R reloads less buggy.
brew install watchman

# flow is a code checker for javascript, which can catch coding issues before you do
brew install flow
```

And now that you have the prereqs, let's install the `react-native` tool.  Again, in your Terminal:

```bash
npm install -g react-native-cli
```

Now, you can make your own react projects instead of cloning this repo.

