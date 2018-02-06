Please copy into this directory the autocorrectur file that you created for your extension. It should 
have a name like 'arcor_de-DE.dat' or something similar. It depends on the language setting of your
operating system or your LibreOffice, while you create your autocorrection file.

This sample autocorrection is prepared only without multilingual support. Thus if you want to create such
autocorrection extension you could create subdirectories here for every language, you support with an
own correction file and put the autocorrection for that language setting there.

In that case you had to edit the paths.xcu and replace the xml tag:
'<node oor:name="%origin%/autocorr" oor:op="fuse"/>
with:
'<node oor:name="%origin%/autocorr/$(vlang)" oor:ope="fuse"/>
