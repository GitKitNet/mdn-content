---
title: mathvariant
slug: Web/MathML/Global_attributes/mathvariant
tags:
  - Global attributes
  - MathML
  - Reference
browser-compat: mathml.global_attributes.mathvariant
---

{{MathMLRef("Global_attributes")}}

The **`mathvariant`** [global attribute](/en-US/docs/Web/MathML/Global_attributes) attribute sets a logical class for textual elements, which is visually
distinguished by using special [Mathematical Alphanumeric Symbols](https://en.wikipedia.org/wiki/Mathematical_Alphanumeric_Symbols).
With the exception of [`mi`](/en-US/docs/Web/MathML/Element/mi) elements with a single character,
which are by convention italic, no special classes are used by default.

> **Note:** When possible, directly use [Mathematical Alphanumeric Symbols](https://en.wikipedia.org/wiki/Mathematical_Alphanumeric_Symbols) instead of an explicit `mathvariant` attribute.

## Syntax

```html
<math>
<!-- a normal "A" -->
<mtext>A</mtext>

<!-- an italic "A" i.e. "๐ด" -->
<mtext mathvariant="italic">A</mtext>

<!-- an italic "A" i.e. "๐ด"
     (automatic italicization for mi elements with one character) -->
<mi>A</mi>

<!-- a normal "A" -->
<mi mathvariant="normal">A</mi>

<!-- a normal "cos" -->
<mi>cos</mi>

<!-- a bold "cos" i.e. "๐๐จ๐ฌ" -->
<mi mathvariant="bold">cos</mi>

<!-- a double-struck "A" i.e. "๐ธ" -->
<mi mathvariant="double-struck">A</mi>

<!-- a fraktur "A" i.e. "๐" -->
<mi mathvariant="fraktur">A</mi>

<!-- a looped "ุจ" i.e. "๐บ" -->
<mi mathvariant="looped">ุจ</mi>

<!-- a stretched "ุจ" i.e. "๐นก" -->
<mi mathvariant="stretched">ุจ</mi>
</math>
```

### Values

- `normal`
  - : Use default rendering (no transformations applied).
- `bold`
  - : Try and use bold characters e.g. "๐".
- `italic`
  - : Try and use italic characters e.g. "๐ด".
- `bold-italic`
  - : Try and use bold-italic characters e.g. "๐จ".
- `double-struck`
  - : Try and use double-struck characters e.g. "๐ธ".
- `bold-fraktur`
  - : Try and use bold-fraktur characters e.g. "๐ฌ".
- `script`
  - : Try and use script characters e.g. "๐".
- `bold-script`
  - : Try and use bold-script characters e.g. "๐".
- `fraktur`
  - : Try and use fraktur characters e.g. "๐".
- `sans-serif`
  - : Try and use sans-serif characters e.g. "๐?".
- `bold-sans-serif`
  - : Try and use bold-sans-serif characters e.g. "๐".
- `sans-serif-italic`
  - : Try and use sans-serif-italic characters e.g. "๐".
- `sans-serif-bold-italic`
  - : Try and use sans-serif-bold-italic characters e.g. "๐ผ".
- `monospace`
  - : Try and use monospace characters e.g. "๐ฐ".
- `initial`
  - : Try and use initial characters e.g. "๐ธข".
- `tailed`
  - : Try and use tailed characters e.g. "๐น".
- `looped`
  - : Try and use looped characters e.g. "๐บ".
- `stretched`
  - : Try and use stretched characters e.g. "๐นข".

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- All [global attributes](/en-US/docs/Web/MathML/Global_attributes).
- {{cssxref("text-transform")}}
