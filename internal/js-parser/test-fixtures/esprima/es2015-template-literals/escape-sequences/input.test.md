# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-template-literals > escape-sequences`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-template-literals/escape-sequences/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-template-literals/escape-sequences/input.js"
		end: Object {
			column: 0
			index: 31
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-template-literals/escape-sequences/input.js"
				end: Object {
					column: 30
					index: 30
					line: 1
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
					filename: "esprima/es2015-template-literals/escape-sequences/input.js"
					end: Object {
						column: 30
						index: 30
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				quasis: Array [
					JSTemplateElement {
						cooked: "\\n\\r\\b\\v\\t\\f\\\n\\\r\n"
						raw: "\\\\n\\\\r\\\\b\\\\v\\\\t\\\\f\\\\\\n\\\\\\r\\n"
						tail: true
						loc: Object {
							filename: "esprima/es2015-template-literals/escape-sequences/input.js"
							end: Object {
								column: 29
								index: 29
								line: 1
							}
							start: Object {
								column: 1
								index: 1
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
