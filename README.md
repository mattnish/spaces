# Responsive Spaces

This is a set of responsive spacing classes.  Unfortunately, most spacing classes out there aren't responsive, 
so I threw this together modelled after bootstrap's media queries (mobile-first).

## Basics:

padding/margin + direction + amount

## Syntax:

pan = "padding all none"
pax = "padding all extra small"
pas = "padding all small"
pam = "padding all medium"
pal = "padding all large"

*Possible directions:* all/top/right/bottom/left

*Possible breakpoints:* xs, sm, md, lg


## Examples:

Padding top large at the extra small screen size, and padding top none at the medium screen size.
``
<div class="ptl-xs ptn-md">
</div>
``

Padding left none at the extra small screen size, and padding left medium at the small screen size.
``
<div class="pln-xs plm-sm">
</div>
``