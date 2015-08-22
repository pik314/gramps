Please read the **COPYING** file first.

Please read the **INSTALL** file if you intend to build from source.

Requirements
==========
The following packages *MUST* be installed in order for Gramps to work:

* Python 3.2 or greater
* GTK 3.10 or greater
* pygobject 3.12 or greater
* cairo, pango, pangocairo with introspection bindings (the gi packages)
* librsvg2 (svg icon view)
* xdg-utils
* bsddb3

The following package is needed for full translation of the interface
to your language:

*   language-pack-gnome-xx

 Translation of GTK elements to your language, with
 xx your language code; e.g. for Dutch you need
 language-pack-gnome-nl. The translation of the
 Gramps strings is included with the gramps source.


The following packages are **STRONGLY RECOMMENDED** to be installed:
--------------------------------------------------------------------
*  **osmgpsmap**

 Used to show maps in the geography view.
 It may be osmgpsmap, osm-gps-map, or python-osmgpsmap,
 but the Python bindings for this must also be present.
 Without this the GeoView will not be active, see
 https://gramps-project.org/wiki/index.php?title=Gramps_4.2_Wiki_Manual_-_Categories#Geography_Category

* **Graphviz**

  Enable creation of graphs using Graphviz engine.
  Without this, three reports cannot be run.
  Obtain it from: http://www.graphviz.org

* **PyICU**

 Improves localised sorting in Gramps. In particular, this
 applies to sorting in the various views and in the
 Narrative Web output. It is particularly helpful for
 non-Latin characters, for non-English locales and on MS
 Windows and Mac OS X platforms. If it is not available,
 sorting is done through built-in libraries. PyICU is
 fairly widely available through the package managers of
 distributions. See http://pyicu.osafoundation.org/
 (These are Python bindings for the ICU package. 
 https://pypi.python.org/pypi/PyICU/)

The following packages are optional:
------------------------------------
* **gtkspell** 

 Enable spell checking in the notes. Gtkspell depends on
 enchant. A version of gtkspell with gobject introspection
 is needed, so minimally version 3.0.0

* **rcs**

 The GNU Revision Control System (RCS) can be used to manage
 multiple revisions of your family trees. See info at
 https://gramps-project.org/wiki/index.php?title=Gramps_4.2_Wiki_Manual_-_Manage_Family_Trees#Archiving_a_Family_Tree
 Only rcs is needed, NO python bindings are required

* **PIL**

 Python Image Library is needed to crop
 images and also to convert non-JPG images to
 JPG so as to include them in LaTeX output.
 (For Python3 a different source may be needed,
 python-imaging or python-pillow or python3-pillow)

* **GExiv2**

 Enables Gramps to manage Exif metadata embedded in your
 media. Gramps needs version 0.5 or greater.
 See https://www.gramps-project.org/wiki/index.php?title=GEPS_029:_GTK3-GObject_introspection_Conversion#GExiv2_for_Image_metadata

* **ttf-freefont**

 More font support in the reports

* **goocanvas2** 

 Required for the (user-downloadable) GraphView plugin

No longer needed:
-----------------
* Since Gramps 4.2:
   **gir-webkit**

* Since Gramps 4.0:
   **pygoocanvas, pygtk, pyexiv2**

* Since Gramps 3.3:
   **python-enchant Enchant**

* Since Gramps 3.2:
   **python glade bindings**

* Since Gramps 3.1:
   **yelp** -             Gnome help browser. No offline help is shipped see Gramps website for User manual


Documentation
-------------
The User Manual is maintained on the Gramps website:

* https://www.gramps-project.org/wiki/index.php?title=User_manual


The Gramps Project ( https://gramps-project.org )
-------------------------------------------------
We strive to produce a genealogy program that is both intuitive for hobbyists and feature-complete for professional genealogists.


