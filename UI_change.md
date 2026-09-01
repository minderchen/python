> Update the expand/collapse controls for all tutorial sections.
>
> The current UI uses the text **“click to expand”** together with `+` or `×`, which is confusing because `×` normally means close rather than collapse.
>
> Please change the interaction to the following:
>
> * When a section is **collapsed**, show: `▶ Show explanation`
> * When a section is **expanded**, show: `▼ Hide explanation`
> * Remove the `+` and `×` icons.
> * The text and arrow should both be clickable.
> * Keep the existing expand/collapse animation and section content unchanged.
> * Apply this consistently to all expandable tutorial sections.
> * Preserve the current visual style, colors, spacing, and typography as much as possible.
> * Make sure the control is keyboard accessible and uses an appropriate `aria-expanded` value.
>
> Example:
>
> ```text
> 07  assert statements and a first test             ▶ Show explanation
> ```
>
> After clicking:
>
> ```text
> 07  assert statements and a first test             ▼ Hide explanation
> ```
>
> Do not use `×` as the collapse indicator.

I would actually recommend **“Show explanation / Hide explanation”** rather than the more generic **“Show details / Hide details”** because this is a teaching tutorial and it tells students exactly what will appear.

If some sections reveal different kinds of material, you can also tell the coding agent to use context-specific labels such as:

* `▶ Show example`
* `▶ Show code`
* `▶ Show explanation`
* `▶ Show debugging steps`

with the corresponding `▼ Hide ...` state.
