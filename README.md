# CSS filter: blur() Inconsistency

This repository demonstrates a bug where the CSS `filter: blur()` property exhibits unexpected behavior in certain browser versions or when used in conjunction with other filter effects.  The blur might not apply, or it may interact strangely with other filters, producing unintended visual outcomes.

The `bug.css` file contains the problematic CSS code.  The `bugSolution.css` file offers potential workarounds, such as using vendor prefixes or alternative techniques to achieve the desired blur effect.

**Testing:**

Test the code in various browsers (especially older versions) to observe the inconsistency.  Different browsers might show varying levels of blur, or no blur at all.

**Solutions:**

The solution may involve using vendor prefixes (-webkit-, -moz-, etc.), employing JavaScript-based blurring techniques, or exploring alternative CSS approaches to achieve a cross-browser compatible blur effect.