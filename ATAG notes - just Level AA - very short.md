# ATAG notes - just Level AA - very short

## Part A: Make the authoring tool user interface accessible

### Principle A.2 Editing-views are perceivable

- If an editing-view renders any text formatting properties that authors can also edit using the editing-view, then the properties can be programmatically determined.

### Principle A.3 Editing-views are operable

- The authoring tool includes mechanisms to make keyboard access more efficient than sequential keyboard access, e.g. WAI-ARIA landmarks.
- If editing-views expose the markup elements in the web content being edited, then the markup elements are selectable and navigation mechanisms are provided to move the selection focus between elements, e.g. Source editing-view, Search by headings, Search by element, Outline view.
- If the authoring tool provides an editing-view of text-based content, then the editing-view enables text search, such that: all text content searchable (including alternative content); matching results can be presented to authors and given focus; authors are informed when no results are found; and the search can be made forwards or backwards.
- If the authoring tool includes display and/or control settings, then these settings can be saved between authoring sessions.
- The authoring tool respects changes in platform display and control settings, unless authors select more specific display and control settings using the authoring tool.

### Principle A.4 Editing-views are understandable

- For each authoring tool feature, at least one of the following is true: use of the feature is explained in the documentation; use of the feature is explained in the authoring tool user interface.

## Part B: Support the production of accessible content

### Principle B2 Authors are supported in producing accessible content

- If the authoring tool provides templates, then there are accessible template options for a range of template uses. 
- If the authoring tool includes a template selection mechanism and provides any non-accessible template options, then distinctions between the accessible and non-accessible options are shown.
- If the authoring tool includes a template selection mechanism and allows authors to create new non-accessible templates, then authors can mark the new template as accessible or non-accessible.
- If the authoring tool provides pre-authored content, then a range of accessible pre-authored content (to WCAG Level AA) options are provided.
- If the authoring tool includes a pre-authored content selection mechanism and provides any non-accessible pre-authored content (WCAG Level AA) options, then the selection mechanism can display distinctions between the accessible and non-accessible options.

### Principle B3 Authors are supported in improving the accessibility of existing content

- If the authoring tool provides checks, then authors can receive an accessibility status report in some format.
- If the authoring tool provides checks, then the authoring tool can programmatically associate accessibility checking results with the web content that was checked.

### Principle B4 Authoring tools promote and integrate their accessibility features

- The authoring tool does not include the option to turn off its accessible content support features or, if these features can be turned off, authors are informed that this may increase the risk of content accessibility problems.
- All accessible content support features are at least as prominent as features related to either invalid markup, syntax errors, spelling errors or grammar errors. 

