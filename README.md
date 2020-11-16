# gantt_bug_in_ff
Minimal repro of stucked scrollbars in FF using DHTMLX Gantt.

This is the minimal structure I was able to use in order to reproduce a Firefox bug - unfortunately it's quite noisy.
If you open the page, you'll see that it's not possible to drag the horizontal or vertical scrollbar.
However, if you remove either `transform` CSS property from the code, it'll work.
