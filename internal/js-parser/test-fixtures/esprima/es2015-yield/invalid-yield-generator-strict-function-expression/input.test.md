# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-yield > invalid-yield-generator-strict-function-expression`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
		end: Object {
			column: 0
			index: 59
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	directives: Array [
		JSDirective {
			value: "use strict"
			loc: Object {
				filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
				end: Object {
					column: 13
					index: 13
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
		}
	]
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						"yield"
						RAW_MARKUP {value: " is a reserved word"}
					]
				}
			}
			location: Object {
				filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 51
					index: 51
					line: 1
				}
				start: Object {
					column: 46
					index: 46
					line: 1
				}
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "g"
				loc: Object {
					filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
					identifierName: "g"
					end: Object {
						column: 25
						index: 25
						line: 1
					}
					start: Object {
						column: 24
						index: 24
						line: 1
					}
				}
			}
			loc: Object {
				filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
				end: Object {
					column: 58
					index: 58
					line: 1
				}
				start: Object {
					column: 14
					index: 14
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: true
				hasHoistedVars: true
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
					end: Object {
						column: 27
						index: 27
						line: 1
					}
					start: Object {
						column: 25
						index: 25
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
					end: Object {
						column: 58
						index: 58
						line: 1
					}
					start: Object {
						column: 27
						index: 27
						line: 1
					}
				}
				body: Array [
					JSVariableDeclarationStatement {
						loc: Object {
							filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
							end: Object {
								column: 56
								index: 56
								line: 1
							}
							start: Object {
								column: 29
								index: 29
								line: 1
							}
						}
						declaration: JSVariableDeclaration {
							kind: "var"
							loc: Object {
								filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
								end: Object {
									column: 56
									index: 56
									line: 1
								}
								start: Object {
									column: 29
									index: 29
									line: 1
								}
							}
							declarations: Array [
								JSVariableDeclarator {
									id: JSBindingIdentifier {
										name: "y"
										loc: Object {
											filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
											identifierName: "y"
											end: Object {
												column: 34
												index: 34
												line: 1
											}
											start: Object {
												column: 33
												index: 33
												line: 1
											}
										}
									}
									loc: Object {
										filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
										end: Object {
											column: 55
											index: 55
											line: 1
										}
										start: Object {
											column: 33
											index: 33
											line: 1
										}
									}
									init: JSFunctionExpression {
										id: JSBindingIdentifier {
											name: "yield"
											loc: Object {
												filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
												identifierName: "yield"
												end: Object {
													column: 51
													index: 51
													line: 1
												}
												start: Object {
													column: 46
													index: 46
													line: 1
												}
											}
										}
										loc: Object {
											filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
											end: Object {
												column: 55
												index: 55
												line: 1
											}
											start: Object {
												column: 37
												index: 37
												line: 1
											}
										}
										body: JSBlockStatement {
											body: Array []
											directives: Array []
											loc: Object {
												filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
												end: Object {
													column: 55
													index: 55
													line: 1
												}
												start: Object {
													column: 53
													index: 53
													line: 1
												}
											}
										}
										head: JSFunctionHead {
											async: false
											generator: false
											hasHoistedVars: false
											params: Array []
											rest: undefined
											returnType: undefined
											thisType: undefined
											typeParameters: undefined
											loc: Object {
												filename: "esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js"
												end: Object {
													column: 53
													index: 53
													line: 1
												}
												start: Object {
													column: 51
													index: 51
													line: 1
												}
											}
										}
									}
								}
							]
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

 esprima/es2015-yield/invalid-yield-generator-strict-function-expression/input.js:1:46 parse/js ━━━━

  ✖ yield is a reserved word

    "use strict"; function *g(){ var y = function yield(){}; }
                                                  ^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
