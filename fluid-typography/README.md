# Fluid typography

#### fluid-typography.scss
Holds a mixin which allows us to have a fluid typography using units such as:
**vw** and **em**.

We can also set **min-font-size** and **max-font-size** with this mixin.

¡¡ **You'll want to import 'strip-units' to get this mixin working** !!

---

>@mixin fluid-type (
>    $properties, // can hold multiple props: 'margin-top padding-top'
>    $min-vw,     // min viewport width (can hold both **px** and **em**)
>    $max-vw,     // max viewport width (can hold both **px** and **em**)
>    $min-value,  // min value (can hold both **px** and **em**)
>    $max-value   // max value (can hold both **px** and **em**)
>  )
