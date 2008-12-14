# po2html, html2po are part of the translate-toolkit, found
# at http://translate.sourceforge.net/wiki/toolkit/index
#
# If you have some problems with Unicode in the generated 
# HTML files, see https://lists.ubuntu.com/archives/ubuntu-translators/2008-November/001906.html
#
LANG = el

all: $(LANG)

el:
	po2html -t ../index.html $@.po ../index.html.$@

index.pot:
	html2po ../index.html index.pot
