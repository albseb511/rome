# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-destructuring-assignment-object-pattern > invalid-pattern-with-method`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
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
			index: 12
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "js-parser"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: "Object pattern cannot contains methods"}
			}
			location: Object {
				filename: "input.js"
				mtime: undefined
				sourceType: "script"
				end: Object {
					column: 3
					index: 3
					line: 1
				}
				start: Object {
					column: 2
					index: 2
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 11
					index: 11
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 11
						index: 11
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				right: JSNumericLiteral {
					value: 0
					format: undefined
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 11
							index: 11
							line: 1
						}
						start: Object {
							column: 10
							index: 10
							line: 1
						}
					}
				}
				left: JSAssignmentObjectPattern {
					rest: undefined
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 8
							index: 8
							line: 1
						}
						start: Object {
							column: 1
							index: 1
							line: 1
						}
					}
					properties: Array [
						JSAssignmentObjectPatternProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "X"
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 7
											index: 7
											line: 1
										}
										start: Object {
											column: 2
											index: 2
											line: 1
										}
									}
								}
								loc: Object {
									filename: "input.js"
									end: Object {
										column: 7
										index: 7
										line: 1
									}
									start: Object {
										column: 2
										index: 2
										line: 1
									}
								}
							}
							value: JSAssignmentIdentifier {
								name: "X"
								loc: Object {
									filename: "input.js"
									end: Object {
										column: 7
										index: 7
										line: 1
									}
									start: Object {
										column: 2
										index: 2
										line: 1
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 7
									index: 7
									line: 1
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
		}
	]
}
```
