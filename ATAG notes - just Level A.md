# ATAG notes - just Level A

## Part A: Make the authoring tool user interface accessible

### Principle A.2 Editing-views are perceivable

#### Guideline A.2.1 Make alternative content available to authors

A.2.2.1 Editing-View Status Indicators: If an editing-view adds status indicators to the content being edited, then the information being conveyed by the status indicators can be programmatically determined. (**Level A**)
Note: Status indicators may indicate errors (e.g. spelling errors), tracked changes, hidden elements, or other information.

### Principle A.3 Editing-views are operable

#### Guideline A.3.1 **Provide keyboard access to authoring features**

A.3.1.1 Keyboard Access (Minimum):  (**Level A**)
A.3.1.2 No Keyboard Traps: (**Level A**)

#### Guideline A.3.2 Provide authors with enough time

A.3.2.1 Auto-Save (Minimum): The authoring tool does not include session time limits or the authoring tool can automatically save edits made before the session time limits are reached. (**Level A**)
A.3.2.2 Timing Adjustable: The authoring tool does not include time limits or at least one of the following is true: (Turn Off, Adjust, Extend) (**Level A**)
A.3.2.3 Static Input Components: The authoring tool does not include moving user interface components that accept input where the movement of these components cannot be paused by authors. (**Level A**)
	- e.g. No moving user interface controls

#### Guideline A.3.3 Help authors avoid flashing content that could cause seizures

A.3.3.1 Static View Option: If an editing-view can play visual time-based content, then playing is not necessarily automatic upon loading the content and playing can be paused. (**Level A**) 
	- e.g.s  Blog: A blogging tool allows authors to import video files. Authors have the option to turn off an auto-play feature, so that the video files are not played until a "Play" button is activated. Once playing, a pause button is always available. WYSIWYG web page editor: A WYSIWYG editing-view is capable of rendering JavaScript in real-time. Authors have the option to turn off the real-time rendering feature, so that the JavaScript is not rendered until a "Play" button is activated. Once playing, a pause button is always available.

#### Guideline A.3.6 Allow users to manage preference settings

A.3.6.1 Independence of Display: If the authoring tool includes display settings for editing-views, then the authoring tool allows authors to adjust these settings without modifying the web content being edited. (**Level A**)
	- e.g. Setting an authoring style sheet: A WYSIWYG authoring tool has preference settings that enable authors to set an "authoring" style sheet. This style sheet is only used to control the rendering of the web content in the author's editing-view. The style sheet does not make changes to the content markup being edited and is not published to end users.

#### Guideline A.3.7 Ensure that previews are at least as accessible as user agents

A.3.7.1 Preview (Minimum): If a preview is provided, then at least one of the following is true: (**Level A**)

- (a) In-Market User Agent: The preview renders content using a user agent that is in-market; or
- (b) UAAG (**Level A**): The preview conforms to the User Agent Accessibility Guidelines 1.0 Level A [UAAG10].

e.g. Preview in a user agent: A web-based authoring tool performs previews by opening the web content in a new user agent tab or window, meeting (a). Preview in a user agent component: A non-web-based authoring tool performs previews using a user agent component that is built directly into the authoring tool, meeting (a).

### Principle A.4 Editing-views are understandable

#### Guideline A.4.1 Help authors avoid and correct mistakes

A.4.1.1 Content Changes Reversible (Minimum): All authoring actions are either reversible or the authoring tool requires author confirmation to proceed. (**Level A**)
	- e.g. Web-based content management system: A web-based content management system supports two types of reversible actions. Firstly, text entry actions in text fields can be reversed using the "Undo" feature of the user agent. Secondly, "Cancel" buttons are available that allow authors to reverse changes that have already been committed. However, to avoid the "Cancel" button being pressed accidentally, authors have the option of having confirmation dialogs displayed when "Cancel" is activated

A.4.1.2 Settings Change Confirmation: If the authoring tool provides mechanisms for changing authoring tool user interface settings, then those mechanisms can reverse the setting changes, or the authoring tool requires author confirmation to proceed. (**Level A**)
	- e.g.s All reversible: All of the preference setting changes in an authoring tool can be reversed by revisiting the preference setting utility and adjusting the settings. Restore defaults: In a preference setting utility, a "restore default settings" button is always available.

##### Guideline A.4.2 Document the user interface, including all accessibility features

A.4.2.1 Describe Accessibility Features: For each authoring tool feature that is used to meet Part A of ATAG 2.0, at least one of the following is true: (**Level A**). (a) Described in the Documentation: Use of the feature is explained in the authoring tool's documentation; or (b) Described in the Interface: Use of the feature is explained in the authoring tool user interface; or ...
	- e.g. Accessibility features documented: An authoring tool includes a help system that is always available to authors, is searchable by keyword and is also linked in context from the various features within the authoring tool.

## Part B: Support the production of accessible content

### Principle B.1 Fully automatic processes produce accessible content

#### Guideline B.1.2 Ensure that accessibility information is preserved

B.1.2.3 Optimizations Preserve Accessibility: If the authoring tool provides optimizing web content transformations, then any accessibility information (WCAG) in the input is preserved in the output. (**Level A**).
	- e.g. Pretty-print: A "pretty-print" tool reformats markup code to make it easier to read by programmers. The tool never makes changes to the markup tags.

B.1.2.4 Text Alternatives for Non-Text Content are Preserved: If the authoring tool provides web content transformations that preserve non-text content in the output, then any text alternatives for that non-text content are also preserved, if equivalent mechanisms exist in the web content technology of the output. (**Level A**). Note: This success criterion only applies when the output technology is "included" for conformance.

### Principle B.2 Authors are supported in producing accessible content

#### Guideline B.2.3 Assist authors with managing alternative content for non-text content

B.2.3.2 Automating Repair of Text Alternatives:

The authoring tool does not attempt to repair text alternatives for non-text content or the following are all true: (**Level A**)

- (a) No Generic or Irrelevant Strings: Generic strings (e.g. "image") and irrelevant strings (e.g. the file name, file format) are not used as text alternatives; and
- (b) In-Session Repairs: If the repair attempt occurs during an authoring session, authors have the opportunity to accept, modify, or reject the repair attempt prior to insertion of the text alternative into the content; and
- (c) Out-of-Session Repairs: If the repair attempt occurs after an authoring session has ended, the repaired text alternatives are indicated during subsequent authoring sessions (if any) and authors have the opportunity to accept, modify, or reject the repair strings prior to insertion in the content.

e.g. No repair

### Principle B.3 Authors are supported in improving the accessibility of existing content

#### Guideline B.3.1 Assist authors in checking for accessibility problems

B.3.1.2 Help Authors Decide: If the authoring tool provides accessibility checking that relies on authors to decide whether potential web content accessibility problems (WCAG) are correctly identified (i.e. manual checking and semi-automated checking), then the accessibility checking process provides instructions that describe how to decide. (**Level A**)
	- e.g. Variety of views

B.3.1.3 Help Authors Locate: If the authoring tool provides checks that require authors to decide whether a potential web content accessibility problem (WCAG) is correctly identified (i.e. manual checking and semi-automated checking), then the relevant content is identified to the authors. (**Level A**) Note: Depending on the nature of the editing-view and the scope of the potential web content accessibility problem (WCAG), identification might involve highlighting elements or renderings of elements, displaying line numbers, or providing instructions.
	- e.g. By line number, Underlining, Site-wide checking

### Principle B.4 Authoring tools promote and integrate their accessibility features

#### Guideline B.4.1 Ensure the availability of features that support the production of accessible content

B.4.1.1 Features Active by Default: All accessible content support features are turned on by default. (**Level A**) 

B.4.1.2 Option to Reactivate Features: The authoring tool does not include the option to turn off its accessible content support features or features which have been turned off can be turned back on. (**Level A**)
	- e.g. Toggle in preferences area

#### Guideline B.4.2 Ensure that documentation promotes the production of accessible content

B.4.2.2 Feature Instructions: Instructions for using any accessible content support features appear in the documentation. (**Level A**)
	- e.g. Documentation of accessible content support features
