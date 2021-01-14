.PHONY: test-all test-gauche test-sagittarius test-chibi

test-all: test-gauche test-sagittarius test-chibi

test-gauche:
	gosh -I. tests.scm

test-sagittarius:
	sash -c -r7 -L. tests.scm

test-chibi:
	chibi-scheme tests.scm
