# Identifier

CASC uses the following regular expression to lex an identifier token: `[a-zA-Z_][a-zA-Z0-9_]*`. In other words:
- CASC allows identifier starts with underscroll `_`
- CASC forbids identifier with non-alphabet characters
