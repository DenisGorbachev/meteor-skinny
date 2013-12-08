Skinny, little skeleton tool for Meteor
=============

We're all used to creating files by hand. Writing a template in Meteor means creating 1 directory + 3 files in total. The basic contents of those files are very much predictable. And we do it very often, becoming typists instead of programmers. So, I've decided to automate the process.

## Installation

```
git clone https://github.com/DenisGorbachev/meteor-skinny
```

For now it's preferrable that you clone the package right in your workspace, to have quick access to the tool.

## Usage

```
../meteor-skinny/skinny client/templates/layout
```

It will create the specified directory along with three files:

* client/templates/layout/layout.html
* client/templates/layout/layout.js
* client/templates/layout/layout.css

What's more, the files would be pre-filled with some boilerplate code, which you don't have to write now!

If you wish to use other languages, just pass skinny some additional options:


```
../meteor-skinny/skinny -c -l client/templates/layout
```

That will create the following files:

* client/templates/layout/layout.html
* client/templates/layout/layout.*coffee*
* client/templates/layout/layout.*less*
