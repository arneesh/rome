# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-private-properties > invalid-destructuring`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "experimental/class-private-properties/invalid-destructuring/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/class-private-properties/invalid-destructuring/input.js"
		end: Object {
			column: 0
			index: 60
			line: 7
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: Object {
					filename: "experimental/class-private-properties/invalid-destructuring/input.js"
					identifierName: "C"
					end: Object {
						column: 7
						index: 7
						line: 1
					}
					start: Object {
						column: 6
						index: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "experimental/class-private-properties/invalid-destructuring/input.js"
				end: Object {
					column: 1
					index: 59
					line: 6
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "experimental/class-private-properties/invalid-destructuring/input.js"
					end: Object {
						column: 1
						index: 59
						line: 6
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				body: Array [
					JSClassPrivateProperty {
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "experimental/class-private-properties/invalid-destructuring/input.js"
									identifierName: "x"
									end: Object {
										column: 4
										index: 14
										line: 2
									}
									start: Object {
										column: 3
										index: 13
										line: 2
									}
								}
							}
							loc: Object {
								filename: "experimental/class-private-properties/invalid-destructuring/input.js"
								end: Object {
									column: 4
									index: 14
									line: 2
								}
								start: Object {
									column: 2
									index: 12
									line: 2
								}
							}
						}
						value: JSNumericLiteral {
							value: 1
							format: undefined
							loc: Object {
								filename: "experimental/class-private-properties/invalid-destructuring/input.js"
								end: Object {
									column: 8
									index: 18
									line: 2
								}
								start: Object {
									column: 7
									index: 17
									line: 2
								}
							}
						}
						typeAnnotation: undefined
						loc: Object {
							filename: "experimental/class-private-properties/invalid-destructuring/input.js"
							end: Object {
								column: 9
								index: 19
								line: 2
							}
							start: Object {
								column: 2
								index: 12
								line: 2
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 2
								index: 12
								line: 2
							}
							loc: Object {
								filename: "experimental/class-private-properties/invalid-destructuring/input.js"
								end: Object {
									column: 4
									index: 14
									line: 2
								}
								start: Object {
									column: 2
									index: 12
									line: 2
								}
							}
						}
					}
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "m"
								loc: Object {
									filename: "experimental/class-private-properties/invalid-destructuring/input.js"
									identifierName: "m"
									end: Object {
										column: 3
										index: 23
										line: 3
									}
									start: Object {
										column: 2
										index: 22
										line: 3
									}
								}
							}
							loc: Object {
								filename: "experimental/class-private-properties/invalid-destructuring/input.js"
								end: Object {
									column: 3
									index: 23
									line: 3
								}
								start: Object {
									column: 2
									index: 22
									line: 3
								}
							}
						}
						loc: Object {
							filename: "experimental/class-private-properties/invalid-destructuring/input.js"
							end: Object {
								column: 3
								index: 57
								line: 5
							}
							start: Object {
								column: 2
								index: 22
								line: 3
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
								filename: "experimental/class-private-properties/invalid-destructuring/input.js"
								end: Object {
									column: 5
									index: 25
									line: 3
								}
								start: Object {
									column: 3
									index: 23
									line: 3
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 2
								index: 22
								line: 3
							}
							loc: Object {
								filename: "experimental/class-private-properties/invalid-destructuring/input.js"
								end: Object {
									column: 3
									index: 23
									line: 3
								}
								start: Object {
									column: 2
									index: 22
									line: 3
								}
							}
						}
						body: JSBlockStatement {
							directives: Array []
							loc: Object {
								filename: "experimental/class-private-properties/invalid-destructuring/input.js"
								end: Object {
									column: 3
									index: 57
									line: 5
								}
								start: Object {
									column: 6
									index: 26
									line: 3
								}
							}
							body: Array [
								JSVariableDeclarationStatement {
									loc: Object {
										filename: "experimental/class-private-properties/invalid-destructuring/input.js"
										end: Object {
											column: 25
											index: 53
											line: 4
										}
										start: Object {
											column: 4
											index: 32
											line: 4
										}
									}
									declaration: JSVariableDeclaration {
										kind: "const"
										loc: Object {
											filename: "experimental/class-private-properties/invalid-destructuring/input.js"
											end: Object {
												column: 25
												index: 53
												line: 4
											}
											start: Object {
												column: 4
												index: 32
												line: 4
											}
										}
										declarations: Array [
											JSVariableDeclarator {
												id: JSBindingObjectPattern {
													rest: undefined
													loc: Object {
														filename: "experimental/class-private-properties/invalid-destructuring/input.js"
														end: Object {
															column: 17
															index: 45
															line: 4
														}
														start: Object {
															column: 10
															index: 38
															line: 4
														}
													}
													properties: Array [
														JSBindingObjectPatternProperty {
															key: JSStaticPropertyKey {
																value: JSPrivateName {
																	id: JSIdentifier {
																		name: "x"
																		loc: Object {
																			filename: "experimental/class-private-properties/invalid-destructuring/input.js"
																			identifierName: "x"
																			end: Object {
																				column: 13
																				index: 41
																				line: 4
																			}
																			start: Object {
																				column: 12
																				index: 40
																				line: 4
																			}
																		}
																	}
																	loc: Object {
																		filename: "experimental/class-private-properties/invalid-destructuring/input.js"
																		end: Object {
																			column: 13
																			index: 41
																			line: 4
																		}
																		start: Object {
																			column: 11
																			index: 39
																			line: 4
																		}
																	}
																}
																loc: Object {
																	filename: "experimental/class-private-properties/invalid-destructuring/input.js"
																	end: Object {
																		column: 13
																		index: 41
																		line: 4
																	}
																	start: Object {
																		column: 11
																		index: 39
																		line: 4
																	}
																}
															}
															value: JSBindingIdentifier {
																name: "x"
																loc: Object {
																	filename: "experimental/class-private-properties/invalid-destructuring/input.js"
																	identifierName: "x"
																	end: Object {
																		column: 16
																		index: 44
																		line: 4
																	}
																	start: Object {
																		column: 15
																		index: 43
																		line: 4
																	}
																}
															}
															loc: Object {
																filename: "experimental/class-private-properties/invalid-destructuring/input.js"
																end: Object {
																	column: 16
																	index: 44
																	line: 4
																}
																start: Object {
																	column: 11
																	index: 39
																	line: 4
																}
															}
														}
													]
												}
												loc: Object {
													filename: "experimental/class-private-properties/invalid-destructuring/input.js"
													end: Object {
														column: 24
														index: 52
														line: 4
													}
													start: Object {
														column: 10
														index: 38
														line: 4
													}
												}
												init: JSThisExpression {
													loc: Object {
														filename: "experimental/class-private-properties/invalid-destructuring/input.js"
														end: Object {
															column: 24
															index: 52
															line: 4
														}
														start: Object {
															column: 20
															index: 48
															line: 4
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
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
