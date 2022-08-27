# margin-collapse |
Margin collapsing only happens in the block-direction. |
The largest margin “wins” |
Any element in between will nix the collapsing |
Margins can collapse even when they aren’t from sibling elements. |
Margins in the same direction from different elements can also collapse. |
Margins from any number of elements can collapse. |
Negative margins also collapse, but it’s the larger-negative number that wins. |
If it’s a bunch of elements all with different margins, you have to basically learn an algorithm to understand what happens and why.
