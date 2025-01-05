# CSS :nth-child Bug

This repository demonstrates a common issue with the CSS `:nth-child` selector when used in conjunction with dynamically updated DOM content.

The bug arises because `:nth-child` isn't automatically reevaluated after changes to the DOM. This can lead to inconsistent styling.  The provided solution offers a more robust alternative.