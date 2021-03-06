# `tabindexNoPositive.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/compiler/lint/rules/jsx-a11y/tabindexNoPositive.test.ts --update-snapshots` to update.

## `avoid positive tab index`

### `0`

```

 unknown:1 lint/jsx-a11y/tabindexNoPositive ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid positive integer values for tabIndex.

    <span tabIndex='5'>foo</span>
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
<span tabIndex='5'>foo</span>;

```

### `1`

```

 unknown:1 lint/jsx-a11y/tabindexNoPositive ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid positive integer values for tabIndex.

    <span tabIndex={5}>foo</span>
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1: formatted`

```
<span tabIndex={5}>foo</span>;

```

### `2`

```
✔ No known problems!

```

### `2: formatted`

```
<span tabIndex={0}>baz</span>;

```

### `3`

```
✔ No known problems!

```

### `3: formatted`

```
<span tabIndex={-1}>baz</span>;

```

### `4`

```
✔ No known problems!

```

### `4: formatted`

```
<span tabIndex='-1'>baz</span>;

```

### `5`

```
✔ No known problems!

```

### `5: formatted`

```
<span tabIndex='0'>baz</span>;

```

## `no tabindex positive`

### `0`

```

 unknown:1 lint/jsx-a11y/tabindexNoPositive ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid positive integer values for tabIndex.

    <span tabIndex='5'>foo</span>
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
<span tabIndex='5'>foo</span>;

```

### `1`

```

 unknown:1 lint/jsx-a11y/tabindexNoPositive ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid positive integer values for tabIndex.

    <span tabIndex={5}>foo</span>
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1: formatted`

```
<span tabIndex={5}>foo</span>;

```

### `2`

```
✔ No known problems!

```

### `2: formatted`

```
<span tabIndex={0}>baz</span>;

```

### `3`

```
✔ No known problems!

```

### `3: formatted`

```
<span tabIndex={-1}>baz</span>;

```

### `4`

```
✔ No known problems!

```

### `4: formatted`

```
<span tabIndex='-1'>baz</span>;

```

### `5`

```
✔ No known problems!

```

### `5: formatted`

```
<span tabIndex='0'>baz</span>;

```
