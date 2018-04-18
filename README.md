# pxt-mkdocs-sample

View the [demo here](https://microsoft.github.io/pxt-mkdocs-sample/).

This repo is a documentation website generated with [mkdocs.org](http://mkdocs.org) using MakeCode for rendering the blocks code.


# How to use this repo?

The three main configuration points for add MakeCode blocks rendering into your mkdocs project are: 
- mkdocs.yml configuration
- add embed.js to your docs folder
- configure embed.js with the makecode website URL you want to use. eg: makecode.microbit.org


## mkdocs.yml configuration

Open your mkdocs.yml and add the following configuration lines: 

```
libs: jquery
extra_javascript: [embed.js]
```

## add embed.js

Copy the [embed.js]() file from this repo and insert it into your /docs folder

## configure embed.js

Open embed.js in a text editor and make sure you have the correct configuration for the MakeCode website you want to use. 
For example, if you are writing blocks for the micro:bit. In the top of the file, edit `makecodeUrl` and change it to "makecode.microbit.org". For Adafruit, use "makecode.adafruit.com" instead.

# License 

MIT
