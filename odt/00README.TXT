Note that 1030.ods is a LibreOffice Calc file.
All the other *.odt files are LibreOffice Writer

Convert *.odt and *.ods files to PDFs:

$ lowriter --convert-to pdf *.odt
$ lomath --convert-to pdf 1030.ods

Concatenate PDFs into one PDF:

$ pdftk *.pdf cat output newFileName.pdf
