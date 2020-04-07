# ATAG notes

The Authoring Tool Accessibility Guidelines (ATAG) documents explain how to:

- make the authoring tools themselves accessible, so that people with disabilities can create web content, and
- help authors create more accessible web content — specifically: enable, support, and promote the production of content that conforms to Web Content Accessibility Guidelines (WCAG).

ATAG 2.0 has two main parts:

- Part A is about making the authoring tool itself accessible.
- Part B is about the authoring tool helping authors produce accessible content.

ATAG 2.0 is organized in layers:

- Principles provide high-level organization for the guidelines.
- Guidelines provide the framework and objectives for the success criteria.
- Success criteria are the accessibility requirements, which are written as testable statements, at three levels: A, AA, AAA.

## ATAG at a Glance

### Part A: Make the authoring tool user interface accessible

#### Principle A1 The authoring tool user interface follows applicable accessibility guidelines

##### Guideline A.1.1 Ensure that web-based functionality is accessible

#### Principle A2 Editing-views are perceivable

##### Guideline A.2.1 Make alternative content available to authors

A.2.2.1 Editing-View Status Indicators: If an editing-view adds status indicators to the content being edited, then the information being conveyed by the status indicators can be programmatically determined. (**Level A**)
Note: Status indicators may indicate errors (e.g. spelling errors), tracked changes, hidden elements, or other information.

##### Guideline A.2.2 Ensure that editing-view presentation can be programmatically determined

A.2.2.2 Access to Rendered Text Properties: If an editing-view renders any text formatting properties that authors can also edit using the editing-view, then the properties can be programmatically determined. (**Level AA**)

#### Principle A3 Editing-views are operable

##### Guideline A.3.1 **Provide keyboard access to authoring features**

A.3.1.1 Keyboard Access (Minimum):  (**Level A**)
A.3.1.2 No Keyboard Traps: (**Level A**)
A.3.1.3 Efficient Keyboard Access: The authoring tool user interface includes mechanisms to make keyboard access more efficient than sequential keyboard access. (**Level AA**)
	- e.g. In a web-based environment: A web-based CMS uses WAI-ARIA landmarks (e.g. banner, main, navigation, search) to allow authors to navigate more quickly.
A.3.1.4 Keyboard Access (Enhanced): All functionality of the authoring tool is operable through a keyboard interface without requiring specific timings for individual keystrokes. (**Level AAA**)
A.3.1.5 Customize Keyboard Access: If the authoring tool includes keyboard commands, then those keyboard commands can be customized. (**Level AAA**)
	- e.g. Web-based content management system: A web-based content management system has a keyboard setup utility that allows authors to change the access keys that are available during authoring. These access key rebindings are for the authors' use only and do not affect the web content being edited.
 A.3.1.6 Present Keyboard Commands: If the authoring tool includes keyboard commands, then the authoring tool provides a way for authors to determine the keyboard commands associated with authoring tool user interface components. (**Level AAA**)

##### Guideline A.3.2 Provide authors with enough time

A.3.2.1 Auto-Save (Minimum): The authoring tool does not include session time limits or the authoring tool can automatically save edits made before the session time limits are reached. (**Level A**)
A.3.2.2 Timing Adjustable: The authoring tool does not include time limits or at least one of the following is true: (Turn Off, Adjust, Extend) (**Level A**)
A.3.2.3 Static Input Components: The authoring tool does not include moving user interface components that accept input where the movement of these components cannot be paused by authors. (**Level A**)
	- e.g. No moving user interface controls
A.3.2.4 Content Edits Saved (Extended): The authoring tool can be set to automatically save web content edits made using the authoring tool. (**Level AAA**) 
	- e.g. Web-based content management system: The system includes an option to turn on asynchronous server communication to constantly save authoring actions into a backup file. If the authoring session ends unexpectedly, authors can retrieve backups during their next authoring session.

##### Guideline A.3.3 Help authors avoid flashing content that could cause seizures

A.3.3.1 Static View Option: If an editing-view can play visual time-based content, then playing is not necessarily automatic upon loading the content and playing can be paused. (**Level A**) 
	- e.g.s  Blog: A blogging tool allows authors to import video files. Authors have the option to turn off an auto-play feature, so that the video files are not played until a "Play" button is activated. Once playing, a pause button is always available. WYSIWYG web page editor: A WYSIWYG editing-view is capable of rendering JavaScript in real-time. Authors have the option to turn off the real-time rendering feature, so that the JavaScript is not rendered until a "Play" button is activated. Once playing, a pause button is always available.

##### Guideline A.3.4 **Enhance navigation and editing via content structure**

A.3.4.1 Navigate By Structure: If editing-views expose the markup elements in the web content being edited, then the markup elements (e.g. source code, content renderings) are selectable and navigation mechanisms are provided to move the selection focus between elements. (**Level AA**)
	- e.g. Source editing-view, Search by headings, Search by element, Outline view, WYSIWYG web page editor: A WYSIWYG editing-view allows authors to select and manipulate elements as objects. When an element is selected, any content (including sub-elements) of the element are also selected.

A.3.4.2 Navigate by Programmatic Relationships: If editing-views allow editing of programmatic relationships within web content, then mechanisms are provided that support navigation between the related content. (**Level AAA**)
Note: Depending on the web content technology and the nature of the authoring tool, relationships may include, but are not limited to, element nesting, headings, labeling, programmatic definitions, and ID relationships.
	- e.g. HTML/CSS editor: When a style is used in content being edited, authors can navigate directly to where that style is defined, even if an external style sheet must be opened. opened. HTML editor: When an id is used in content being edited, authors can navigate directly to where that id is defined. WAI-ARIA editor: Authors can navigate directly via WAI-ARIA relationships, such as aria-labeledby and aria-describedby

##### Guideline A.3.5 **Provide text search of the content**

A.3.5.1 Text Search: If the authoring tool provides an editing-view of text-based content, then the editing-view enables text search, such that all of the following are true: (**Level AA**)

- (a) All Editable Text: Any text content that is editable by the editing-view is searchable (including alternative content); and
- (b) Match: Matching results can be presented to authors and given focus; and
- (c) No Match: Authors are informed when no results are found; and
- (d) Two-way: The search can be made forwards or backwards.

e.g. Basic text search: An authoring tool provides both WYSIWYG and source editing-views. The authoring tool provides two-way searching for plain text sequences within both editing-views. The default search option is to search only within the editing-view that the author is currently working within. However, there is an option to search both editing-views simultaneously. When this option is selected, the search results are all displayed in a selectable list that labels each as "Text" or "Source Code", reflecting which editing-view will become active when the author selects the search result. 

##### Guideline A.3.6 Allow users to manage preference settings

A.3.6.1 Independence of Display: If the authoring tool includes display settings for editing-views, then the authoring tool allows authors to adjust these settings without modifying the web content being edited. (**Level A**)
	- e.g. Setting an authoring style sheet: A WYSIWYG authoring tool has preference settings that enable authors to set an "authoring" style sheet. This style sheet is only used to control the rendering of the web content in the author's editing-view. The style sheet does not make changes to the content markup being edited and is not published to end users.
A.3.6.2 Save Settings: If the authoring tool includes display and/or control settings, then these settings can be saved between authoring sessions. (**Level AA**)
	- e.g. Storing preferences with author account: A web-based authoring tool requires that authors log in to their accounts before authoring sessions can begin. Because preference settings are associated with author accounts, the settings are applied as soon as authors log in.
A.3.6.3 Apply Platform Settings: The authoring tool respects changes in platform display and control settings, unless authors select more specific display and control settings using the authoring tool. (**Level AA**)
	-e.g. Web-based authoring tool: A web-based authoring tool respects the display and control settings of the user agent on which it is running.

##### Guideline A.3.7 Ensure that previews are at least as accessible as user agents

A.3.7.1 Preview (Minimum): If a preview is provided, then at least one of the following is true: (**Level A**)

- (a) In-Market User Agent: The preview renders content using a user agent that is in-market; or
- (b) UAAG (**Level A**): The preview conforms to the User Agent Accessibility Guidelines 1.0 Level A [UAAG10].

e.g. Preview in a user agent: A web-based authoring tool performs previews by opening the web content in a new user agent tab or window, meeting (a). Preview in a user agent component: A non-web-based authoring tool performs previews using a user agent component that is built directly into the authoring tool, meeting (a).

A.3.7.2 Preview (Enhanced): If a preview is provided, then authors can specify which user agent performs the preview. (**Level AAA**)
	- e.g. Web-based authoring tool: A web-based authoring tool provides authors with a URI that can be entered into another user agent to perform the preview.

#### Principle A4 Editing-views are understandable

##### Guideline A.4.1 Help authors avoid and correct mistakes

A.4.1.1 Content Changes Reversible (Minimum): All authoring actions are either reversible or the authoring tool requires author confirmation to proceed. (**Level A**)
	- e.g. Web-based content management system: A web-based content management system supports two types of reversible actions. Firstly, text entry actions in text fields can be reversed using the "Undo" feature of the user agent. Secondly, "Cancel" buttons are available that allow authors to reverse changes that have already been committed. However, to avoid the "Cancel" button being pressed accidentally, authors have the option of having confirmation dialogs displayed when "Cancel" is activated

A.4.1.2 Settings Change Confirmation: If the authoring tool provides mechanisms for changing authoring tool user interface settings, then those mechanisms can reverse the setting changes, or the authoring tool requires author confirmation to proceed. (**Level A**)
	- e.g.s All reversible: All of the preference setting changes in an authoring tool can be reversed by revisiting the preference setting utility and adjusting the settings. Restore defaults: In a preference setting utility, a "restore default settings" button is always available.

A.4.1.3 Content Changes Reversible (Enhanced): Authors can sequentially reverse a series of reversible authoring actions. (**Level AAA**)
Note: It is acceptable to clear the authoring action history at the end of authoring sessions.
	- e.g. Undo queue: An authoring tool saves author actions in a "last-in-last-out" queue.

##### Guideline A.4.2 Document the user interface, including all accessibility features

A.4.2.1 Describe Accessibility Features: For each authoring tool feature that is used to meet Part A of ATAG 2.0, at least one of the following is true: (**Level A**). (a) Described in the Documentation: Use of the feature is explained in the authoring tool's documentation; or (b) Described in the Interface: Use of the feature is explained in the authoring tool user interface; or ...
	- e.g. Accessibility features documented: An authoring tool includes a help system that is always available to authors, is searchable by keyword and is also linked in context from the various features within the authoring tool.

A.4.2.2 Document All Features: For each authoring tool feature, at least one of the following is true: (**Level AA**) (a) Described in the Documentation: Use of the feature is explained in the authoring tool's documentation; or (b) Described in the Interface: Use of the feature is explained in the authoring tool user interface; or ...
	- e.g. All features documented: An authoring tool includes documentation for all of its available features. The documentation conforms to WCAG 2.0 Level A.


### Part B: Support the production of accessible content

#### Principle B1 Fully automatic processes produce accessible content

##### Guideline B.1.1 Ensure that automatically-specified content is accessible

B.1.1.1 Content Auto-Generation After Authoring Sessions (WCAG): The authoring tool does not automatically generate web content after the end of an authoring session, or, authors can specify that the content be accessible web content (WCAG).
	- e.g. No automatic content generation after authoring sessions: An authoring tool only makes edits to content as directed by the author when the content file is open for authoring (i.e. during an authoring session) 

B.1.1.2 Content Auto-Generation During Authoring Sessions (WCAG): If the authoring tool provides the functionality for automatically generating web content during an authoring session, then at least one of the following is true: (**Level A** to meet WCAG 2.0 Level A success criteria; Level AA to meet WCAG 2.0 Level A and AA success criteria; Level AAA to meet all WCAG 2.0 success criteria)

- (a) Accessible: The content is accessible web content (WCAG) without author input; or
- (b) Prompting: During the automatic generation process, authors are prompted for any required accessibility information (WCAG); or
- (c) Automatic Checking: After the automatic generation process, accessibility checking is automatically performed; or
- (d) Checking Suggested: After the automatic generation process, the authoring tool prompts authors to perform accessibility checking.

e.g. Markup behind WYSIWYG: A WYSIWYG web page authoring tool provides authors with a toolbar of options for formatting text. Following the WYSIWYG (what-you-see-is-what-you-get) paradigm, the options are labeled with the visual result (e.g. a bold "B" to represent bold, an italicized "I" to represent italics) of performing the action however, the content that is automatically-generated from those actions actually conforms to WCAG 2.0 (e.g. using strong for bold and em for emphasis), meeting (a). 

##### Guideline B.1.2 Ensure that accessibility information is preserved

B.1.2.1 Restructuring and Recoding Transformations (WCAG): If the authoring tool provides restructuring transformations or re-coding transformations, and if equivalent mechanisms exist in the web content technology of the output, then at least one of the following is true ...

B.1.2.2 Copy-Paste Inside Authoring Tool (WCAG): If the authoring tool supports copy and paste of structured content, then any accessibility information (WCAG) in the copied content is preserved when the authoring tool is both the source and destination of the copy-paste and the source and destination use the same web content technology.
	- Plain text clipboard format, HTML clipboard format. including any accessibility information, and rendered for the author.

B.1.2.3 Optimizations Preserve Accessibility: If the authoring tool provides optimizing web content transformations, then any accessibility information (WCAG) in the input is preserved in the output. (**Level A**).
	- e.g. Pretty-print: A "pretty-print" tool reformats markup code to make it easier to read by programmers. The tool never makes changes to the markup tags.

B.1.2.4 Text Alternatives for Non-Text Content are Preserved: If the authoring tool provides web content transformations that preserve non-text content in the output, then any text alternatives for that non-text content are also preserved, if equivalent mechanisms exist in the web content technology of the output. (**Level A**). Note: This success criterion only applies when the output technology is "included" for conformance.

#### Principle B2 Authors are supported in producing accessible content

##### Guideline B.2.1 Ensure that accessible content production is possible

B.2.1.1 Accessible Content Possible (WCAG): The authoring tool does not place restrictions on the web content that authors can specify or those restrictions do not prevent WCAG 2.0 success criteria from being met.
	- e.g. No restrictions (source content editing-view): An authoring tool is designed around a source editing-view, allowing motivated and knowledgeable authors to control every detail of the content produced, including following accessible authoring practices. e.g. Accessible workflow exists: An authoring tool is designed such that accessible web content (in this case conforming to WCAG 2.0 Level A) will result.

##### Guideline B.2.2 Guide authors to produce accessible content

B.2.2.1 Accessible Option Prominence (WCAG): If authors are provided with a choice of authoring actions for achieving the same authoring outcome (e.g. styling text), then options that will result in accessible web content (WCAG) are at least as prominent as options that will not. 
	- e.g. Structural markup: A WYSIWYG HTML editor does not include any authoring action options that will necessarily result in web content that will not meet the WCAG 2.0 Level A success criteria. With a toolbar.

B.2.2.2 Setting Accessibility Properties (WCAG): If the authoring tool provides mechanisms to set web content properties (e.g. attribute values), then mechanisms are also provided to set web content properties related to accessibility information (WCAG).
	- e.g. Context sensitive properties e.g ask for alt for images, Data table for a bar graph.

##### Guideline B.2.3 Assist authors with managing alternative content for non-text content

B.2.3.1 Alternative Content is Editable (WCAG): If the authoring tool provides functionality for adding non-text content, then authors are able to modify programmatically associated text alternatives for non-text content.
	- e.g. Source content editing-view, Properties dialog

B.2.3.2 Automating Repair of Text Alternatives:

The authoring tool does not attempt to repair text alternatives for non-text content or the following are all true: (**Level A**)

- (a) No Generic or Irrelevant Strings: Generic strings (e.g. "image") and irrelevant strings (e.g. the file name, file format) are not used as text alternatives; and
- (b) In-Session Repairs: If the repair attempt occurs during an authoring session, authors have the opportunity to accept, modify, or reject the repair attempt prior to insertion of the text alternative into the content; and
- (c) Out-of-Session Repairs: If the repair attempt occurs after an authoring session has ended, the repaired text alternatives are indicated during subsequent authoring sessions (if any) and authors have the opportunity to accept, modify, or reject the repair strings prior to insertion in the content.

e.g. No repair


B.2.3.3 Save for Reuse:

If the authoring tool provides the functionality for adding non-text content, when authors enter programmatically associated text alternatives for non-text content, then both of the following are true: (**Level AAA**)

- (a) Save and Suggest: The text alternatives are automatically saved and suggested by the authoring tool, if the same non-text content is reused; and
- (b) Edit Option: The author has the option to edit or delete the saved text alternatives.

##### Guideline B.2.4 Assist authors with accessible templates

B.2.4.1 Accessible Template Options (WCAG): If the authoring tool provides templates, then there are accessible template (WCAG) options for a range of template uses. 

B.2.4.2 Identify Template Accessibility: If the authoring tool includes a template selection mechanism and provides any non-accessible template (WCAG) options, then the template selection mechanism can display distinctions between the accessible and non-accessible options. (**Level AA**) Note: The distinction can involve providing information for the accessible templates, the non-accessible templates or both.
	- e.g. Variety of accessible templates: A web page authoring tool provides several template choices for home pages, guest books, and on-line albums. For each type of functionality, the basic template option is accessible (see the definition of "accessible template (WCAG)"). Content management system: A content management system offers a variety of templates to authors for different purposes (e.g. information page, interactive form page, registration page). All of the templates are accessible.

B.2.4.3 Author-Created Templates: If the authoring tool includes a template selection mechanism and allows authors to create new non-accessible templates (WCAG), then authors can enable the template selection mechanism to display distinctions between accessible and non-accessible templates that they create. (**Level AA**) Note: The distinction can involve providing information for the accessible templates (WCAG), the non-accessible templates or both.

B.2.4.4 Accessible Template Options (Enhanced): If the authoring tool provides templates, then all of the templates are accessible template (to WCAG Level AA). (**Level AAA**)

##### Guideline B.2.5 Assist authors with accessible pre-authored content

B.2.5.1 Accessible Pre-Authored Content Options: If the authoring tool provides pre-authored content, then a range of accessible pre-authored content (to WCAG Level AA) options are provided. (**Level AA**)
	- e.g. Clip art collection

B.2.5.2 Identify Pre-Authored Content Accessibility: If the authoring tool includes a pre-authored content selection mechanism and provides any non-accessible pre-authored content (WCAG Level AA) options, then the selection mechanism can display distinctions between the accessible and non-accessible options. (**Level AA**) Note: The distinction can involve providing information for the accessible pre-authored content, the non-accessible pre-authored content or both.

#### Principle B3 Authors are supported in improving the accessibility of existing content

##### Guideline B.3.1 Assist authors in checking for accessibility problems

B.3.1.1 Checking Assistance (WCAG): !!! If the authoring tool provides authors with the ability to add or modify web content in such a way that a WCAG 2.0 success criterion can be violated, then accessibility checking for that success criterion is provided (e.g. an HTML authoring tool that inserts images should check for alternative text; a video authoring tool with the ability to edit text tracks should check for captions). (**Level A** to meet WCAG 2.0 Level A success criteria; Level AA to meet WCAG 2.0 Level A and AA success criteria; Level AAA to meet all WCAG 2.0 success criteria) Note: Automated and semi-automated checking is possible (and encouraged) for many types of web content accessibility problems (WCAG). However, manual checking is the minimum requirement to meet this success criterion. In manual checking, the authoring tool provides authors with instructions for detecting problems, which authors carry out by themselves. !!!

B.3.1.2 Help Authors Decide: If the authoring tool provides accessibility checking that relies on authors to decide whether potential web content accessibility problems (WCAG) are correctly identified (i.e. manual checking and semi-automated checking), then the accessibility checking process provides instructions that describe how to decide. (**Level A**)
	- e.g. Variety of views

B.3.1.3 Help Authors Locate: If the authoring tool provides checks that require authors to decide whether a potential web content accessibility problem (WCAG) is correctly identified (i.e. manual checking and semi-automated checking), then the relevant content is identified to the authors. (**Level A**) Note: Depending on the nature of the editing-view and the scope of the potential web content accessibility problem (WCAG), identification might involve highlighting elements or renderings of elements, displaying line numbers, or providing instructions.
	- e.g. By line number, Underlining, Site-wide checking

B.3.1.4 Status Report: If the authoring tool provides checks, then authors can receive an accessibility status report based on the results of the accessibility checks. (**Level AA**) Note: The format of the accessibility status report is not specified and they might include a listing of problems detected or a WCAG 2.0 conformance level, etc.
	- e.g. List of accessibility problems, Conformance level report

B.3.1.5 Programmatic Association of Results: If the authoring tool provides checks, then the authoring tool can programmatically associate accessibility checking results with the web content that was checked. (**Level AA**)

##### Guideline B.3.2 Assist authors in repairing accessibility problems

B.3.2.1 Repair Assistance (WCAG):

If checking (see Success Criterion B.3.1.1) can detect that a WCAG 2.0 success criterion is not met, then repair suggestion(s) are provided: (**Level A** to meet WCAG 2.0 Level A success criteria; Level AA to meet WCAG 2.0 Level A and AA success criteria; Level AAA to meet all WCAG 2.0 success criteria) Note: Automated and semi-automated repair is possible (and encouraged) for many types of web content accessibility problems (WCAG). However, manual repair is the minimum requirement to meet this success criterion. In manual repair, the authoring tool provides authors with instructions for repairing problems, which authors carry out by themselves.
	- e.g. Combined check-repair feature

#### Principle B4 Authoring tools promote and integrate their accessibility features

##### Guideline B.4.1 Ensure the availability of features that support the production of accessible content

B.4.1.1 Features Active by Default: All accessible content support features are turned on by default. (**Level A**) 

B.4.1.2 Option to Reactivate Features: The authoring tool does not include the option to turn off its accessible content support features or features which have been turned off can be turned back on. (**Level A**)
	- e.g. Toggle in preferences area

B.4.1.3 Feature Deactivation Warning: The authoring tool does not include the option to turn off its accessible content support features or, if these features can be turned off, authors are informed that this may increase the risk of content accessibility problems (WCAG). (**Level AA**)

B.4.1.4 Feature Prominence: All accessible content support features are at least as prominent as features related to either invalid markup, syntax errors, spelling errors or grammar errors. (**Level AA**) 

##### Guideline B.4.2 Ensure that documentation promotes the production of accessible content

B.4.2.1 Model Practice (WCAG): A range of examples in the documentation (e.g. markup, screen shots of WYSIWYG editing-views) demonstrate accessible authoring practices (WCAG).
	- e.g. Reference examples are accessible, Screen shots show accessibility features in use

B.4.2.2 Feature Instructions: Instructions for using any accessible content support features appear in the documentation. (**Level A**)
	- e.g. Documentation of accessible content support features

B.4.2.3 Tutorial: The authoring tool provides a tutorial for an accessible authoring process that is specific to that authoring tool. (**Level AAA**)

B.4.2.4 Instruction Index: The authoring tool documentation contains an index to the instructions for using any accessible content support features. (**Level AAA**)