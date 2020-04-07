# ATAG notes - just Level A - short

## Part A: Make the authoring tool user interface accessible

### Principle A.2 Editing-views are perceivable

#### Guideline A.2.2 Ensure that editing-view presentation can be programmatically determined.

- If an editing-view adds status indicators (e.g. errors, tracked changes, hidden elements) to the content being edited, then the information being conveyed by the status indicators can be programmatically determined.

### Principle A.3 Editing-views are operable

#### Guideline A.3.1 **Provide keyboard access to authoring features**

- All functionality of the authoring tool is operable through a keyboard interface without requiring specific timings.
- No Keyboard Traps

#### Guideline A.3.2 Provide authors with enough time

- No session time limits or the automatically save edits made before the session time limits are reached.
- No time limits or at least one of the following is true: Turn Off, Adjust, Extend time limit.
- No moving UI input components that cannot be paused.

#### Guideline A.3.3 Help authors avoid flashing content that could cause seizures

- Any visual time-based content (e.g. real-time rendering) can be paused.

#### Guideline A.3.6 Allow users to manage preference settings

- If there are display settings for editing-views, then they're adjustable without modifying the web content being edited.

#### Guideline A.3.7 Ensure that previews are at least as accessible as user agents

- If a preview is provided, then it's render by an in-marke user agent (e.g. in the browser!)

### Principle A.4 Editing-views are understandable

#### Guideline A.4.1 Help authors avoid and correct mistakes

- All authoring actions are either reversible or the authoring tool requires author confirmation to proceed. E.g. Undo, or Cancel (to reverse changes) with a confirmation dialog.
- If there are authoring settings, they can be undone or restored to default.

##### Guideline A.4.2 Document the user interface, including all accessibility features

- Accessibility Features are described in the documentation or the UI itself (e.g. keyboard shortcuts, how to search).

## Part B: Support the production of accessible content

### Principle B.1 Fully automatic processes produce accessible content

#### Guideline B.1.2 Ensure that accessibility information is preserved

- If the authoring tool provides optimizing web content transformations, then any accessibility information (WCAG) in the input is preserved in the output.
- If the authoring tool provides web content transformations that preserve non-text content in the output, then any text alternatives are preserved.

### Principle B.2 Authors are supported in producing accessible content

#### Guideline B.2.3 Assist authors with managing alternative content for non-text content

- If the authoring tool attempts to repair text alternatives for non-text content it has: No Generic or Irrelevant Strings; In-Session Repairs; Out-of-Session Repairs.

### Principle B.3 Authors are supported in improving the accessibility of existing content

#### Guideline B.3.1 Assist authors in checking for accessibility problems

- If the authoring tool provides accessibility checking that relies on authors to decide whether potential web content accessibility problems (WCAG) are correctly identified (i.e. manual checking and semi-automated checking), then the process provides instructions that describe how to decide.
- If the authoring tool provides checks that require authors to decide whether a potential web content accessibility problem (WCAG) is correctly identified, then the relevant content is identified to the authors, e.g. By line number or underlining.

### Principle B.4 Authoring tools promote and integrate their accessibility features

#### Guideline B.4.1 Ensure the availability of features that support the production of accessible content

- All accessible content support features are turned on by default. 
- The authoring tool does not include the option to turn off its accessible content support features or features which have been turned off can be turned back on.

#### Guideline B.4.2 Ensure that documentation promotes the production of accessible content

- Instructions for using any accessible content support features appear in the documentation, as other features would.
