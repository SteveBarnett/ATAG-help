# ATAG notes - just Level A - SC checklist

## Part A: Make the authoring tool user interface accessible

- **A.2.1.1 Text Alternatives for Rendered Non-Text Content** If an editing-view renders non-text content, then any programmatically associated text alternatives for the non-text content can be programmatically determined.
- **A.2.1.2 Alternatives for Rendered Time-Based Media** If an editing-view renders time-based media, then it can be previewed or render for preview in another user agent.
- **A.2.2.1 Editing-View Status Indicators** If an editing-view adds status indicators (e.g. errors, tracked changes, hidden elements) to the content being edited, then the information being conveyed by the status indicators can be programmatically determined.
- **A.3.1.1 Keyboard Access (Minimum)** All functionality of the authoring tool is operable through a keyboard interface without requiring specific timings.
- **A.3.1.2 No Keyboard Traps** If keyboard focus can be moved to a component using a keyboard interface, then focus can be moved away from that component using only a keyboard interface.
- **A.3.2.1 Auto-Save (Minimum)** No session time limits or the automatically save edits made before the session time limits are reached.
- **A.3.2.2 Timing Adjustable** No time limits or at least one of the following is true: Turn Off, Adjust, Extend time limit.
- **A.3.2.3 Static Input Components** No moving UI input components that cannot be paused.
- **A.3.3.1 Static View Option** Any visual time-based content (e.g. real-time rendering) can be paused.
- **A.3.6.1 Independence of Display** If there are display settings for editing-views, then they're adjustable without modifying the web content being edited.
- **A.3.7.1 Preview (Minimum)** If a preview is provided, then it's render by an in-marke user agent (e.g. in the browser!)
- **A.4.1.1 Content Changes Reversible (Minimum)** All authoring actions are either reversible or the authoring tool requires author confirmation to proceed. E.g. Undo, or Cancel (to reverse changes) with a confirmation dialog.
- **A.4.1.2 Settings Change Confirmation** If there are authoring settings, they can be undone or restored to default.
- **A.4.2.1 Describe Accessibility Features** Accessibility Features are described in the documentation or the UI itself (e.g. keyboard shortcuts, how to search).

## Part B: Support the production of accessible content

- **B.1.2.3 Optimizations Preserve Accessibility** If the authoring tool provides optimizing web content transformations, then any accessibility information (WCAG) in the input is preserved in the output.
- **B.1.2.4 Text Alternatives for Non-Text Content are Preserved** If the authoring tool provides web content transformations that preserve non-text content in the output, then any text alternatives are preserved.
- **B.2.3.2 Automating Repair of Text Alternatives** If the authoring tool attempts to repair text alternatives for non-text content it has: No Generic or Irrelevant Strings; In-Session Repairs; Out-of-Session Repairs.
- **B.3.1.2 Help Authors Decide** If the authoring tool provides accessibility checking that relies on authors to decide whether potential web content accessibility problems (WCAG) are correctly identified (i.e. manual checking and semi-automated checking), then the process provides instructions that describe how to decide.
- **B.3.1.3 Help Authors Locate** If the authoring tool provides checks that require authors to decide whether a potential web content accessibility problem (WCAG) is correctly identified, then the relevant content is identified to the authors, e.g. By line number or underlining.
- **B.4.1.1 Features Active by Default** All accessible content support features are turned on by default.
- **B.4.1.2 Option to Reactivate Features** The authoring tool does not include the option to turn off its accessible content support features or features which have been turned off can be turned back on.
- **B.4.2.2 Feature Instructions** Instructions for using any accessible content support features appear in the documentation, as other features would.
