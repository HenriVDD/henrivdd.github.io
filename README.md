# CV
This is or will or may be my future cv

Generate html:
pandoc --standalone -c style.css --from markdown --to html -s -o index.html header.html footer.html index.md

Generate PDF: Need to remove the credit for the PDF generation in the html
wkhtmltopdf --enable-local-file-access --load-error-handling ignore index.html style.css index.pdf
wkhtmltopdf --encoding UTF-8 --enable-local-file-access --load-error-handling ignore -B 0 -L 0 -R 0 -T 5 index_pdf.html index.pdf


https://henrivdd.github.io/

To Do:
- creative commons
- auto-remove credits for PDF generation

grey : 545454
light turquoise: c5d9d9
light violet: a985bb
violet: 50548f
blue: 2d5a91
grey blue: 6c99ad