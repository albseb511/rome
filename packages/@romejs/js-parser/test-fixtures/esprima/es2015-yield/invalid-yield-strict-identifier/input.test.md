# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-yield > invalid-yield-strict-identifier`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
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
			index: 37
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
				filename: "input.js"
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
			origins: Array [Object {category: "js-parser"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "yield is a reserved word"}
			}
			location: Object {
				filename: "input.js"
				mtime: undefined
				sourceType: "script"
				end: Object {
					column: 34
					index: 34
					line: 1
				}
				start: Object {
					column: 29
					index: 29
					line: 1
				}
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "f"
				loc: Object {
					filename: "input.js"
					identifierName: "f"
					end: Object {
						column: 24
						index: 24
						line: 1
					}
					start: Object {
						column: 23
						index: 23
						line: 1
					}
				}
			}
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 36
					index: 36
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
				generator: false
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 26
						index: 26
						line: 1
					}
					start: Object {
						column: 24
						index: 24
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 36
						index: 36
						line: 1
					}
					start: Object {
						column: 27
						index: 27
						line: 1
					}
				}
				body: Array [
					JSExpressionStatement {
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 34
								index: 34
								line: 1
							}
							start: Object {
								column: 29
								index: 29
								line: 1
							}
						}
						expression: JSReferenceIdentifier {
							name: "yield"
							loc: Object {
								filename: "input.js"
								identifierName: "yield"
								end: Object {
									column: 34
									index: 34
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
	]
}
```
