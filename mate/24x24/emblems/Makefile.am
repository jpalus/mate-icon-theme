NULL =

png_icons = \
	emblem-default.png \
	emblem-documents.png \
	emblem-downloads.png \
	emblem-favorite.png \
	emblem-generic.png \
	emblem-important.png \
	emblem-mail.png \
	emblem-new.png \
	emblem-package.png \
	emblem-photos.png \
	emblem-readonly.png \
	emblem-shared.png \
	emblem-symbolic-link.png \
	emblem-synchronizing.png \
	emblem-system.png \
	emblem-unreadable.png \
	emblem-urgent.png \
	emblem-web.png \
	$(NULL)

emblem-default.png: ../../../src/emblem-default.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:99:326:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-documents.png: ../../../src/emblem-documents.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:100:326:124 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-downloads.png: ../../../src/emblem-downloads.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:100:326:124 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-favorite.png: ../../../src/emblem-favorite.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:99:326:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-generic.png: ../../../src/emblem-generic.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:100:326:124 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-important.png: ../../../src/emblem-important.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:99:326:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-mail.png: ../../../src/emblem-mail.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:99:326:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-new.png: ../../../src/emblem-new.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:99:326:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-package.png: ../../../src/packages.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:101:326:125 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-photos.png: ../../../src/emblem-photos.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:100:326:124 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-readonly.png: ../../../src/emblems-fs.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=1102:99:1126:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-shared.png: ../../../src/emblem-shared.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:99:326:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-symbolic-link.png: ../../../src/emblems-fs.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:99:326:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-synchronizing.png: ../../../src/emblem-synchronizing.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:99:326:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-system.png: ../../../src/emblem-system.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:100:326:124 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-unreadable.png: ../../../src/emblems-fs.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=702:99:726:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-urgent.png: ../../../src/emblem-urgent.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:99:326:123 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

emblem-web.png: ../../../src/emblem-web.svg
	@echo "  "$@
	@inkscape -z $^ --export-area=302:100:326:124 -w=24 -h=24 -e=$@ 1> /dev/null
	@mogrify -quiet -strip $@

.PHONY: build-png-icons-local clean-png-icons-local
build-png-icons-local: $(png_icons)

clean-png-icons-local:
	@echo "  Cleaning icons..."
	@rm -f $(png_icons)
