# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > optional-chaining > conditional-decimal`

```javascript
JSRoot {
	comments: Array []
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
			index: 25
			line: 4
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
				filename: "input.js"
				end: Object {
					column: 9
					index: 9
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSConditionalExpression {
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 9
						index: 9
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				test: JSBooleanLiteral {
					value: true
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 4
							index: 4
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
				}
				alternate: JSNumericLiteral {
					value: 0
					format: undefined
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 9
							index: 9
							line: 1
						}
						start: Object {
							column: 8
							index: 8
							line: 1
						}
					}
				}
				consequent: JSNumericLiteral {
					value: 0.3
					format: undefined
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 7
							index: 7
							line: 1
						}
						start: Object {
							column: 5
							index: 5
							line: 1
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 13
					index: 24
					line: 3
				}
				start: Object {
					column: 0
					index: 11
					line: 3
				}
			}
			expression: JSConditionalExpression {
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 13
						index: 24
						line: 3
					}
					start: Object {
						column: 0
						index: 11
						line: 3
					}
				}
				test: JSBooleanLiteral {
					value: true
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 4
							index: 15
							line: 3
						}
						start: Object {
							column: 0
							index: 11
							line: 3
						}
					}
				}
				alternate: JSNumericLiteral {
					value: 0
					format: undefined
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 13
							index: 24
							line: 3
						}
						start: Object {
							column: 12
							index: 23
							line: 3
						}
					}
				}
				consequent: JSNumericLiteral {
					value: 0.3
					format: undefined
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 9
							index: 20
							line: 3
						}
						start: Object {
							column: 7
							index: 18
							line: 3
						}
					}
				}
			}
		}
	]
}
```
