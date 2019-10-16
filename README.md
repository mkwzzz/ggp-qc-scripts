# ggp-qc-scripts

Zip file contains the following: 
close.xml (closing xml fragment)
exp_fits_combine.bat (Windows batch script that combines separate FITS xml files)
fart.exe (copy of Find And Replace Text, a Windows executable that finds and replaces text)
open.xml (opening xml fragment)
saxon9he.jar (Saxon XSL Processor-- requires Java)
summarize_fits.xsl (XSLT stylesheet that parses combined wellformed xml into spreadsheet friendly form)

These are ad-hoc scripts developed for a very niche purpose. I'm sharing them here in the hopes that they will be useful, but I make no claims that they work for any partiuclar purpose or situation. Feel free to use them however you want, but use them at your own risk.
This method requires Java to use the Saxon XSLT processor. You could also use any other XSLT processor you want. The fart.exe file is included as a legacy from a previous project-- it doesn't really do anything that useful here, but the .bat file does call it so I left it in.
