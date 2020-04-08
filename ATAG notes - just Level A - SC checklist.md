# ATAG notes - just Level A - SC checklist

## Part A: Make the authoring tool user interface accessible

- **A.2.2.1** If an editing-view adds status indicators (e.g. errors, tracked changes, hidden elements) to the content being edited, then the information being conveyed by the status indicators can be programmatically determined.
- **A.3.1.1** All functionality of the authoring tool is operable through a keyboard interface without requiring specific timings.
- **A.3.1.2** No Keyboard Traps
- **A.3.2.1** No session time limits or the automatically save edits made before the session time limits are reached.
- **A.3.2.2** No time limits or at least one of the following is true: Turn Off, Adjust, Extend time limit.
- **A.3.2.3** No moving UI input components that cannot be paused.
- **A.3.3.1** Any visual time-based content (e.g. real-time rendering) can be paused.
- **A.3.6.1** If there are display settings for editing-views, then they're adjustable without modifying the web content being edited.
- **A.3.7.1** If a preview is provided, then it's render by an in-marke user agent (e.g. in the browser!)
- **A.4.1.1** All authoring actions are either reversible or the authoring tool requires author confirmation to proceed. E.g. Undo, or Cancel (to reverse changes) with a confirmation dialog.
- **A.4.1.2** If there are authoring settings, they can be undone or restored to default.
- **A.4.2.1** Accessibility Features are described in the documentation or the UI itself (e.g. keyboard shortcuts, how to search).

## Part B: Support the production of accessible content

- **B.1.2.3** If the authoring tool provides optimizing web content transformations, then any accessibility information (WCAG) in the input is preserved in the output.
- **B.1.2.4** If the authoring tool provides web content transformations that preserve non-text content in the output, then any text alternatives are preserved.
- **B.2.3.2** If the authoring tool attempts to repair text alternatives for non-text content it has: No Generic or Irrelevant Strings; In-Session Repairs; Out-of-Session Repairs.
- **B.3.1.2** If the authoring tool provides accessibility checking that relies on authors to decide whether potential web content accessibility problems (WCAG) are correctly identified (i.e. manual checking and semi-automated checking), then the process provides instructions that describe how to decide.
- **B.3.1.3** If the authoring tool provides checks that require authors to decide whether a potential web content accessibility problem (WCAG) is correctly identified, then the relevant content is identified to the authors, e.g. By line number or underlining.
- **B.4.1.1** All accessible content support features are turned on by default.
- **B.4.1.2** The authoring tool does not include the option to turn off its accessible content support features or features which have been turned off can be turned back on.
- **B.4.2.2** Instructions for using any accessible content support features appear in the documentation, as other features would.
