### The Aim of the Project

We aimed to develop a tool which allows any Wikimedia Commons user to import images to Commons from the online repositories 
of a number of GLAMs (**g**alleries, **l**ibraries, **a**rchives and **m**useums) easily.

### Tasks Completed

- Designed the architecture of the tool so that it is easily scalable.
- Enabled authentication of the users via Oauth.
- Designed a very simple user interface.
- Enabled auto-fill of the metadata of the uploaded images with little user intervention.
- Added support for upload via URL or unique ID of the image.
- Enabled searching of images based on a given search string.
- Enabled creation of an image gallery on performing a string based image search.
- Enabled multiple image upload at a time.
- Added support for adding multiple categories for the images.
- Prevented uploading of images that are already present in Wikimedia Commons.
- Enabled showing of proper error messages in the UI when exceptions occur.
- Deployed the app on Wikimedia Founadtion Toollabs ([link](https://tools.wmflabs.org/glam2commons/)).
- Added two GLAMs (National Archief, Amsterdam Museum) into the tool.

### Achievements

To make the tool easily scalable was a challenge in itself. We have followed a OOP based approach where there is a base class from which all GLAM classes inherit. For inclusion of a new GLAM the corresponding GLAM class has to define a set of pre-decided attributes and methods. The details of the architecture is [here](https://commons.m.wikimedia.org/wiki/User:Infobliss/Glam2Commons/How_to_add_a_new_glam).

### Next steps

- Adding pagination support in the image gallery.
- Adding new GLAMs to the tool.

### Source Code

The source code is licensed under GNU General Public License v3.0. Here is the [link](github.com/infobliss/sibutest2) to the source code.

### Mentors

- [Bas](https://github.com/basvb)
- [Zhuyifei](https://github.com/zhuyifei1999)
- [Tom](https://github.com/tom29739)
