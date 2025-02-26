---
title: Output window
description: The Output window in Roblox Studio displays error messages, calls to print(), and calls to warn().
---

The **Output** window, accessible from the [View](./view-tab.md) tab, displays errors captured from running scripts, messages from Roblox Engine, messages from calls to `print()`, and errors from calls to `warn()`.

<img src="../assets/studio/general/View-Tab-Output.png" width="768" alt="Output button indicated in View tab of Studio" />

Plugins can interact with the Output window through `Class.LogService`, which can record and clear the Output window contents. You can customize the output through the following elements:

<img src="../assets/studio/general/Output-Window-Diagram.png" width="820" alt="Sections of Output window indicated by lettered pointers" />

<Grid container spacing={2}>
	<Grid item XSmall={2} Medium={1} Large={1} XLarge={1}><img src="../assets/misc/Box-Label-A.png" width="40" style={{float:"right"}} /></Grid>
	<Grid item XSmall={10} Medium={11} Large={11} XLarge={11} style={{marginTop:"4px"}}>
	Filters output by type, such as **Error** or **Warning**.
	</Grid>
</Grid>
<Grid container spacing={2}>
	<Grid item item XSmall={2} Medium={1} Large={1} XLarge={1}><img src="../assets/misc/Box-Label-B.png" width="40" style={{float:"right"}} /></Grid>
	<Grid item XSmall={10} Medium={11} Large={11} XLarge={11} style={{marginTop:"4px"}}>
	Filters output by context, such as **Client**, **Server**, or **User Plugin**.
	</Grid>
</Grid>
<Grid container spacing={2}>
	<Grid item item XSmall={2} Medium={1} Large={1} XLarge={1}><img src="../assets/misc/Box-Label-C.png" width="40" style={{float:"right"}} /></Grid>
	<Grid item XSmall={10} Medium={11} Large={11} XLarge={11} style={{marginTop:"4px"}}>
	Filters output by the text entered into the field, such as an object name.
	</Grid>
</Grid>
<Grid container spacing={2}>
	<Grid item item XSmall={2} Medium={1} Large={1} XLarge={1}><img src="../assets/misc/Box-Label-D.png" width="40" style={{float:"right"}} /></Grid>
	<Grid item XSmall={10} Medium={11} Large={11} XLarge={11} style={{marginTop:"4px"}}>
	Clears all output messages from the window. This action has a shortcut of <kbd>Ctrl</kbd><kbd>K</kbd> on Windows or <kbd>⌘</kbd><kbd>K</kbd> on Mac.
	</Grid>
</Grid>
<Grid container spacing={2}>
	<Grid item item XSmall={2} Medium={1} Large={1} XLarge={1}><img src="../assets/misc/Box-Label-E.png" width="40" style={{float:"right"}} /></Grid>
	<Grid item XSmall={10} Medium={11} Large={11} XLarge={11} style={{marginTop:"4px"}}>
	Controls the level of detail displayed for each output message.<ul><li>**Show Timestamp** &mdash; Shows a detailed timestamp in `HH:MM:SS.SSS` format.</li><li>**Show Context** &mdash; Shows the message context, such as **Client** or **Server**.</li><li>**Show Source** &mdash; If applicable, shows the associated script name and line number.</li><li>**Show Tables Expanded by Default** &mdash; For outputted tables, contents are expanded by default.</li><li>**Show Memory Address for Expandable Tables** &mdash; For expandable tables, shows the internal memory address, such as `0xb4f0417581144ec5`.</li><li>**Log Mode** &mdash; Simplifies output by removing options, such as expandable trees.</li></ul>
	</Grid>
</Grid>
