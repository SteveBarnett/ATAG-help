# ATAG notes - just Level A - very very short

## Part A: Make the authoring tool user interface accessible

- All functionality is operable through a keyboard interface without requiring specific timings.
- There are no time limits or session time limits without them being adjustable or autosave.
- Edit-view status indicators can be programmatically determined.
- No moving UI input components or visual time-based content that cannot be paused.
- If there are edit-view settings, they don't modify the content output.
- If a preview is provided, it's rendered in the browser.
- All actions are either reversible or require confirmation.
- If there are authoring settings, they can be undone or restored to default.
- Accessibility features are described in the documentation or the UI itself (e.g. keyboard shortcuts, how to search).

## Part B: Support the production of accessible content

- If there are web content transformations, they preserve any accessibility information, including text alternatives.
- If the tool attempts to repair text alternatives it has: No Generic or Irrelevant Strings; In-Session Repairs; Out-of-Session Repairs.
- If the authoring tool provides accessibility checking that requires author decisions, there are instructions that describe how to decide.
- If the authoring tool provides checks then the relevant content is identified to the authors, e.g. By line number or underlining.
- All accessible content support features are turned on by default.
- The authoring tool does not include the option to turn off its accessible content support features or features which have been turned off can be turned back on.
- Instructions for using any accessible content support features appear in the documentation, as other features would.
