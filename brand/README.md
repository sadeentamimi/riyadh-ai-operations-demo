# Brand assets

The header renders the official marks from this folder:

    ntt-data.png   NTT DATA global logo (Future Blue RGB), cropped to content
    cisco.svg      Cisco logo (2016 mark), transparent vector

Both are the official artwork in their standard blue. The header applies a
`brightness(0) invert(1)` filter, so they render as clean white on the navy
shell without the source files being re-coloured.

Replacing them
--------------
Drop in a replacement with the same base name — `.png` or `.svg` both work
(`ntt-data.*` is tried as .png then .svg; `cisco.*` as .svg then .png). Supply
the standard blue artwork on a transparent background, cropped tightly with no
baked-in padding. Aspect ratio is preserved (fixed height, `width: auto`), so
the marks can never be stretched. No rebuild needed — just refresh.
