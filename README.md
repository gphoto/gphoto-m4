gphoto-m4
=========

`gphoto-m4` is the gPhoto projects' collection of m4 macros for use
with the autoconf/automake based build systems.

It has been designed to be used in

  * `gphoto2`
  * `libgphoto2`
  * `libgphoto2_port` (located in `libgphoto2/`)
  * `gtkam`

Some macros are re-used ones from `libexif`.

Since the gPhoto project moved from SVN to git, we have not figured
out yet how to properly include the `gphoto-m4` files into the
respective software's `gphoto-m4/` subdirectory (either `git subtree`
or `git submodule` come to mind).

So for the time being, we manually update and synchronize the files.
