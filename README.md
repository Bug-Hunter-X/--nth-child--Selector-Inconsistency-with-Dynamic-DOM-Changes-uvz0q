# :nth-child Selector Inconsistency with Dynamic DOM Changes

This repository demonstrates a common issue encountered when using the CSS `:nth-child` selector with dynamically updated DOM elements. The `:nth-child` selector is evaluated only once when the stylesheet is parsed and applied. Any subsequent DOM changes won't automatically trigger a re-evaluation of the selector.  This can lead to unexpected styling outcomes.

The `dynamic-nth-child-bug.css` file shows the problem, where styles are not correctly applied to newly added elements. The `dynamic-nth-child-solution.css` file offers a solution using JavaScript to update the styles after DOM manipulation.