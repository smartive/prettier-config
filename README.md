# Prettier configuration provided by smartive

The following rules differ from Prettier's default configuration:

### Quotes (`singleQuote: true`)

Use single quotes instead of double quotes.

### Print Width (`printWidth: 125`)

The maximum line length got extended to 125 characters in order to match TypeScript's demand of
longer lines due to type declarations.

### Trailing Commas (`trailingComma: all`)

Add trailing commas wherever possible. Please note that this requires node 8 or some sort of
transformation.

### End of Line (`endOfLine: lf`)

Use Line Feed only.
