# nilnul develop main source folder
## codename: nilnul.dev.\_src\_.eg\_.main



This follows NilNul Develop recommendation to set up the main folder for your source code.

You can clone this into that main folder:
  - if that folder hasn't been created, run <kbd> git clone {url of this repo}  newSrcFolder <kbd>
  - if that folder has been created, run <kbd> git clone {url of this repo} .</kbd>

Or you can just download some of the files here into your main folder.


Next let's create a dir named <kbd>.packages</kbd> to contain installed nuget packages. Some projects in the source folder will use symlink to reference that dir; by doing so, many projects share installed packages, thus save a lot of storage space.
This dir can also be symlink pointing to another location when you want to keep your source code folder not bloated by those installed packages.
