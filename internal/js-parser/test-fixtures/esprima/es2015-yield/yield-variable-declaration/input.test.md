# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-yield > yield-variable-declaration`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-yield/yield-variable-declaration/input.js"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-yield/yield-variable-declaration/input.js"
		end: Object {
			column: 0
			index: 11
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "esprima/es2015-yield/yield-variable-declaration/input.js"
				end: Object {
					column: 10
					index: 10
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "esprima/es2015-yield/yield-variable-declaration/input.js"
					end: Object {
						column: 10
						index: 10
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "yield"
							loc: Object {
								filename: "esprima/es2015-yield/yield-variable-declaration/input.js"
								identifierName: "yield"
								end: Object {
									column: 9
									index: 9
									line: 1
								}
								start: Object {
									column: 4
									index: 4
									line: 1
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "esprima/es2015-yield/yield-variable-declaration/input.js"
							end: Object {
								column: 9
								index: 9
								line: 1
							}
							start: Object {
								column: 4
								index: 4
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
