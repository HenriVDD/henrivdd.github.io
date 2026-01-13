# CV
This is or will or may be my future cv

Generate html:
pandoc --standalone -c style.css --from markdown --to html -s -o index.html header.html footer.html index.md

Generate PDF: 
Warning 1: install a recent version of wkhtmltopdf (see github page https://github.com/wkhtmltopdf/packaging/releases)
Warning 2: Need to remove the credit for the PDF generation in the html (keep the footer beacons but remove the content)

wkhtmltopdf --encoding UTF-8 --enable-local-file-access --load-error-handling ignore -B 0 -L 0 -R 0 -T 5 index_pdf.html index.pdf
/usr/local/bin/wkhtmltopdf --encoding UTF-8 --enable-local-file-access --load-error-handling ignore -B 0 -L 0 -R 0 -T 5 index_pdf.html --footer-html footer_pdf.html index.pdf


https://henrivdd.github.io/

To Do:
- creative commons
- auto-remove credits for PDF generation
- add a photo ?

grey : 545454
light turquoise: c5d9d9
light violet: a985bb
violet: 50548f
blue: 2d5a91
grey blue: 6c99ad