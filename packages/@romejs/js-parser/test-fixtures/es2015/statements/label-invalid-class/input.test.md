# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > statements > label-invalid-class`

```javascript
Program {
  comments: Array []
  corrupt: false
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
      index: 16
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
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unexpected token'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 10
          index: 10
          line: 1
        }
        start: Object {
          column: 5
          index: 5
          line: 1
        }
      }
    }
  ]
  body: Array [
    LabeledStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 15
          index: 15
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      label: Identifier {
        name: 'foo'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 3
            index: 3
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
      }
      body: ClassDeclaration {
        id: BindingIdentifier {
          name: 'X'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 12
              index: 12
              line: 1
            }
            start: Object {
              column: 11
              index: 11
              line: 1
            }
          }
        }
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 15
            index: 15
            line: 1
          }
          start: Object {
            column: 5
            index: 5
            line: 1
          }
        }
        meta: ClassHead {
          body: Array []
          implements: undefined
          superClass: undefined
          superTypeParameters: undefined
          typeParameters: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 15
              index: 15
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
  ]
}
```