---
title: <mover>
slug: Web/MathML/Reference/Element/mover
page-type: mathml-element
browser-compat: mathml.elements.mover
sidebar: mathmlref
---

The **`<mover>`** [MathML](/en-US/docs/Web/MathML) element is used to attach an accent or a limit over an expression. Use the following syntax: `<mover> base overscript </mover>`

## Attributes

This element's attributes include the [global MathML attributes](/en-US/docs/Web/MathML/Reference/Global_attributes) as well as the following attribute:

- `accent`
  - : A [`<boolean>`](/en-US/docs/Web/MathML/Reference/Values#mathml-specific_types) indicating whether the over script should be treated as an accent (i.e., drawn bigger and closer to the base expression).

## Examples

```html
<math display="block">
  <mover accent="true">
    <mrow>
      <mi>x</mi>
      <mo>+</mo>
      <mi>y</mi>
      <mo>+</mo>
      <mi>z</mi>
    </mrow>
    <mo>&#x23DE;<!--TOP CURLY BRACKET--></mo>
  </mover>
</math>
```

{{ EmbedLiveSample('mover_example', 700, 200, "", "") }}

## Technical summary

<table class="properties">
  <tr>
    <th scope="row">
      <a href="/en-US/docs/Web/Accessibility/ARIA/Reference/Roles">Implicit ARIA role</a>
    </th>
    <td>
      None
    </td>
  </tr>
</table>

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{ MathMLElement("munder") }} (Underscript)
- {{ MathMLElement("munderover") }} (Underscript-overscript pair)
