# Terminal cheatsheet

!! -> Wiederhole letzter Command

!v -> Wiederhole lezter Command der mit 'v' startet

cd -> wechsle ins Home Directory

cd - -> wechsle ins vorherige Directory


### Insert page to pdf
convert xc:none -page A4 blank.pdf -> erstellt eine leere pdf-Seite

pdfseparate -f <first_page> -l <last_page> <file_name>.pdf out_%d.pdf -> separiere das pdf in der range first_page - last_page in einzelne pdfs

pdfunite <ordered list of pdf> <output_filename>.pdf -> merge pdf zu 1 pdf
  
