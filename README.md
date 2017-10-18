dssweb.tinymce-people-shortcut
====================================

Navigate with tinymce to plone site root for people

Works for Plone 4.3+ (

INSTALL:

If you are using buildout you can do this:

* Add ``dssweb.tinymce-people-shortcut`` to the list of eggs to install, e.g.:

    [buildout]
    ...
    eggs =
        ...
        dssweb.tinymce-people-shortcut
       
* Re-run buildout, e.g. with:

    $ ./bin/buildout -N
        
Navigate to TinyMCE ControlPanel (portal_tinymce/@@tinymce-controlpanel) and add "People" to link the People shortcut.

Origin reference: http://docs.plone.org/5/en/develop/plone/forms/wysiwyg.html#tinymce-shortcuts
