# Wrapper

The wrapper object constrains the width of content.

```HTML
<div class="o-wrapper">
	…
</div>
```

The `div` will now have a `max-width` applied and be horizontally centered using auto left/right margins as well as padded by the base spacing unit.

To remove padding enable the flush wrapper and add the `o-wrapper--flush` modifier class.

As well as the standard wrapper width you can also enable a wide and/or narrow variant, applied with `o-wrapper--wide` and `o-wrapper--narrow` modifiers.

Widths for all sized wrappers can be set by modifying the `$creepy-wrapper-width`, `$creepy-wrapper-width-narrow` and `$creepy-wrapper-width-wide` variables. Padding defaults to the base spacing unit but can be changed with `$creepy-wrapper-padding`.