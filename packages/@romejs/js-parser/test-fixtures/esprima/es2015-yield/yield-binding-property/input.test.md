# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-yield > yield-binding-property`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 24
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
				filename: "input.js"
				end: Object {
					column: 23
					index: 23
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
					filename: "input.js"
					end: Object {
						column: 23
						index: 23
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
						id: JSBindingObjectPattern {
							rest: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 16
									index: 16
									line: 1
								}
								start: Object {
									column: 4
									index: 4
									line: 1
								}
							}
							properties: Array [
								JSBindingObjectPatternProperty {
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "yield"
											loc: Object {
												filename: "input.js"
												identifierName: "yield"
												end: Object {
													column: 11
													index: 11
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
											filename: "input.js"
											end: Object {
												column: 11
												index: 11
												line: 1
											}
											start: Object {
												column: 6
												index: 6
												line: 1
											}
										}
									}
									value: JSBindingIdentifier {
										name: "x"
										loc: Object {
											filename: "input.js"
											identifierName: "x"
											end: Object {
												column: 14
												index: 14
												line: 1
											}
											start: Object {
												column: 13
												index: 13
												line: 1
											}
										}
									}
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 14
											index: 14
											line: 1
										}
										start: Object {
											column: 6
											index: 6
											line: 1
										}
									}
								}
							]
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 22
								index: 22
								line: 1
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
						init: JSReferenceIdentifier {
							name: "foo"
							loc: Object {
								filename: "input.js"
								identifierName: "foo"
								end: Object {
									column: 22
									index: 22
									line: 1
								}
								start: Object {
									column: 19
									index: 19
									line: 1
								}
							}
						}
					}
				]
			}
		}
	]
}
```
