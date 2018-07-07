# Post-Icon Subsplits for LiveSplit
This project is a modified version of the Subsplits component for LiveSplit. My motivation in creating the component was speedrunning Crash Bandicoot 2, where I wanted to display icons for colored gems over my existing subsplits without a bunch of ugly, unnecessary indenting. Here's the change list:

- If an icon is set for a split, the icon displays after the split name (i.e. to the right) rather than before (i.e. to the left).
- The normal Subsplits component scales each icon based on the largest width of all icons. This version leaves icons unscaled.
- To complement these changes, the configuration page (within Edit Layout) has the "Indent Blank Icons" checkbox and "Size" slider removed (under the Icons section).

That's it. Note that I only tested this component using vertically-stacked splits.
