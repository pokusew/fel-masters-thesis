# useful shortcuts

.PHONY: pdf
pdf:
	@echo "running OpTeX on index.tex ..."
	optex index.tex

.PHONY: open
open: pdf
	@echo "opening PDF build ..."
	open index.pdf

.PHONY: copy
copy: pdf
	@echo "copying PDF build to the final destination ..."
	cp index.pdf ../FIDO2_USB_Security_Key.pdf

.PHONY: clean
clean:
	rm -rf index.log index.pdf index.ref texput.log
