# `noLabelVar.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/compiler/lint/rules/js/noLabelVar.test.ts --update-snapshots` to update.

## `no label var`

### `0`

```

 unknown:2 lint/js/noLabelVar ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Do not use the x variable name as a label.

    1 │ const x = 'test';
  > 2 │ x: const y = 'test';
      │ ^^^^^^^^^^^^^^^^^^^^

  ℹ Creating a label with the same name as an in-scope variable leads to confusion.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
const x = "test";
x: const y = "test";

```

### `1`

```
✔ No known problems!

```

### `1: formatted`

```
const x = "test";
z: const y = "test";

```
