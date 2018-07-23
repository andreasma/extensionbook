This is the folder for your templates. It's important to create a structure inside this folder for the different types of template files, e.g. for already in use categories like business correspondenz, presentations or for your new categories, e.g. 'education'. You need to add also a file 'groupuinames.xml' for this matter to this folder with e.g. something similar to the following structure:

<?xml version="1.0" encoding="UTF-8"?>
<groupuinames:template-group-list
    xmlns:groupuinames=
        "http://openoffice.org/2006/groupuinames">
    <groupuinames:template-group groupuinames:name="education"
        groupuinames:default-ui-name="Bildung" />
    <groupuinames:template-group groupuinames:name="presnt"
        groupuinames:default-ui-name="Pr`ä`sentationen" />
</groupuinames:template-group-list>
