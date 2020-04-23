# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-primary-array > migrated_0012`

```javascript
Program {
  comments: Array []
  corrupt: true
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 28
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
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Invalid Unicode escape'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 18
          index: 18
          line: 1
        }
        start: Object {
          column: 18
          index: 18
          line: 1
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 27
          index: 27
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: AssignmentExpression {
        operator: '='
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 27
            index: 27
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        left: AssignmentIdentifier {
          name: '\u2163\u2161\u200a'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 18
              index: 18
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
        }
        right: MemberExpression {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 27
              index: 27
              line: 1
            }
            start: Object {
              column: 19
              index: 19
              line: 1
            }
          }
          object: ReferenceIdentifier {
            name: '\u2009'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 25
                index: 25
                line: 1
              }
              start: Object {
                column: 19
                index: 19
                line: 1
              }
            }
          }
          property: ComputedMemberProperty {
            value: ReferenceIdentifier {
              name: 'INVALID_PLACEHOLDER'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 27
                  index: 27
                  line: 1
                }
                start: Object {
                  column: 26
                  index: 26
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
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
        }
      }
    }
  ]
}
```