# List of installed "official" plugins from
# http://5digits.org/pentadactyl/plugins#sect-official-plugins
DACTYL_PLUGINS := browser-improvements curl http-headers jQuery jscompletion noscript tab-options

# noscript-interactive.js: http://code.google.com/p/vimperator-labs/issues/detail?id=1

update:
	for f in $(DACTYL_PLUGINS); do \
		wget http://5digits.org/plugins/$$f-dev.js -O $$f.js; \
	done

