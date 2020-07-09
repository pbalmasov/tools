# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `es2019 > json-strings > template-line-separator`

### `ast`

```javascript
JSRoot {
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 102
			line: 4
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	comments: Array [
		CommentLine {
			id: "0"
			value: "      ^ That's a U+2028 LINE SEPARATOR UTF-16 char (between 'before' and 'after')"
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 83
					index: 101
					line: 3
				}
				start: Object {
					column: 0
					index: 18
					line: 3
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			trailingComments: Array ["0"]
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 8
					index: 17
					line: 2
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSTemplateLiteral {
				expressions: Array []
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 6
						index: 15
						line: 2
					}
					start: Object {
						column: 1
						index: 1
						line: 1
					}
				}
				quasis: Array [
					JSTemplateElement {
						cooked: "before\u2028after"
						raw: "before\u2028after"
						tail: true
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 5
								index: 14
								line: 2
							}
							start: Object {
								column: 2
								index: 2
								line: 1
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```