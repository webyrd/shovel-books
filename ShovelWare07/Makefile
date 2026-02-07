BOOK = book

all: ${BOOK}.pdf

${BOOK}.pdf: ${BOOK}.md
	pandoc book.md -o book.pdf --toc
	pandoc -s book.md --toc > book.html

squeaky:
	rm -f ${BOOK}.pdf
