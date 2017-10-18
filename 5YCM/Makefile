5YCM_Report.pdf: 5YCM_Report.md
	pandoc -S -o $@ -V geometry:margin=.90in --filter pandoc-citeproc --latex-engine=xelatex --variable urlcolor=blue $<
	pandoc -S -o 5YCM_Report.docx --filter pandoc-citeproc -V geometry:margin=.90in $<
