# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > modules > duplicate-named-export-destructuring17`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
		end: Object {
			column: 0
			index: 57
			line: 4
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExportLocalDeclaration {
			exportKind: "value"
			specifiers: undefined
			loc: Object {
				filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
				end: Object {
					column: 33
					index: 33
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclarationStatement {
				loc: Object {
					filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
					end: Object {
						column: 33
						index: 33
						line: 1
					}
					start: Object {
						column: 7
						index: 7
						line: 1
					}
				}
				declaration: JSVariableDeclaration {
					kind: "const"
					loc: Object {
						filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
						end: Object {
							column: 33
							index: 33
							line: 1
						}
						start: Object {
							column: 7
							index: 7
							line: 1
						}
					}
					declarations: Array [
						JSVariableDeclarator {
							id: JSBindingArrayPattern {
								loc: Object {
									filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
									end: Object {
										column: 26
										index: 26
										line: 1
									}
									start: Object {
										column: 13
										index: 13
										line: 1
									}
								}
								rest: JSBindingIdentifier {
									name: "bar"
									loc: Object {
										filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
										identifierName: "bar"
										end: Object {
											column: 25
											index: 25
											line: 1
										}
										start: Object {
											column: 22
											index: 22
											line: 1
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
											end: Object {
												column: 25
												index: 25
												line: 1
											}
											start: Object {
												column: 22
												index: 22
												line: 1
											}
										}
									}
								}
								elements: Array [
									JSBindingIdentifier {
										name: "foo"
										loc: Object {
											filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
											identifierName: "foo"
											end: Object {
												column: 17
												index: 17
												line: 1
											}
											start: Object {
												column: 14
												index: 14
												line: 1
											}
										}
										meta: JSPatternMeta {
											optional: undefined
											typeAnnotation: undefined
											loc: Object {
												filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
												end: Object {
													column: 17
													index: 17
													line: 1
												}
												start: Object {
													column: 14
													index: 14
													line: 1
												}
											}
										}
									}
								]
							}
							loc: Object {
								filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
								end: Object {
									column: 32
									index: 32
									line: 1
								}
								start: Object {
									column: 13
									index: 13
									line: 1
								}
							}
							init: JSReferenceIdentifier {
								name: "baz"
								loc: Object {
									filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
									identifierName: "baz"
									end: Object {
										column: 32
										index: 32
										line: 1
									}
									start: Object {
										column: 29
										index: 29
										line: 1
									}
								}
							}
						}
					]
				}
			}
		}
		JSExportLocalDeclaration {
			exportKind: "value"
			specifiers: undefined
			loc: Object {
				filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
				end: Object {
					column: 21
					index: 55
					line: 2
				}
				start: Object {
					column: 0
					index: 34
					line: 2
				}
			}
			declaration: JSVariableDeclarationStatement {
				loc: Object {
					filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
					end: Object {
						column: 21
						index: 55
						line: 2
					}
					start: Object {
						column: 7
						index: 41
						line: 2
					}
				}
				declaration: JSVariableDeclaration {
					kind: "const"
					loc: Object {
						filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
						end: Object {
							column: 21
							index: 55
							line: 2
						}
						start: Object {
							column: 7
							index: 41
							line: 2
						}
					}
					declarations: Array [
						JSVariableDeclarator {
							id: JSBindingIdentifier {
								name: "bar"
								loc: Object {
									filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
									identifierName: "bar"
									end: Object {
										column: 16
										index: 50
										line: 2
									}
									start: Object {
										column: 13
										index: 47
										line: 2
									}
								}
							}
							loc: Object {
								filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
								end: Object {
									column: 20
									index: 54
									line: 2
								}
								start: Object {
									column: 13
									index: 47
									line: 2
								}
							}
							init: JSNumericLiteral {
								value: 1
								format: undefined
								loc: Object {
									filename: "es2015/modules/duplicate-named-export-destructuring17/input.js"
									end: Object {
										column: 20
										index: 54
										line: 2
									}
									start: Object {
										column: 19
										index: 53
										line: 2
									}
								}
							}
						}
					]
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
