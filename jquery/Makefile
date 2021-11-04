file := ../tokens/lichess/read_preferences.token
token := $(shell cat ${file})

prefs:
	curl -H "Authorization: Bearer $(token)" https://lichess.org/api/account
