# ATAG notes - just Level AA

## Part A: Make the authoring tool user interface accessible

### Principle A.2 Editing-views are perceivable

#### Guideline A.2.2 Ensure that editing-view presentation can be programmatically determined

A.2.2.2 Access to Rendered Text Properties: If an editing-view renders any text formatting properties that authors can also edit using the editing-view, then the properties can be programmatically determined. (**Level AA**)

### Principle A.3 Editing-views are operable

#### Guideline A.3.1 **Provide keyboard access to authoring features**

A.3.1.3 Efficient Keyboard Access: The authoring tool user interface includes mechanisms to make keyboard access more efficient than sequential keyboard access. (**Level AA**)
	- e.g. In a web-based environment: A web-based CMS uses WAI-ARIA landmarks (e.g. banner, main, navigation, search) to allow authors to navigate more quickly.

#### Guideline A.3.4 **Enhance navigation and editing via content structure**

A.3.4.1 Navigate By Structure: If editing-views expose the markup elements in the web content being edited, then the markup elements (e.g. source code, content renderings) are selectable and navigation mechanisms are provided to move the selection focus between elements. (**Level AA**)
	- e.g. Source editing-view, Search by headings, Search by element, Outline view, WYSIWYG web page editor: A WYSIWYG editing-view allows authors to select and manipulate elements as objects. When an element is selected, any content (including sub-elements) of the element are also selected.


#### Guideline A.3.5 **Provide text search of the content**

A.3.5.1 Text Search: If the authoring tool provides an editing-view of text-based content, then the editing-view enables text search, such that all of the following are true: (**Level AA**)

- (a) All Editable Text: Any text content that is editable by the editing-view is searchable (including alternative content); and
- (b) Match: Matching results can be presented to authors and given focus; and
- (c) No Match: Authors are informed when no results are found; and
- (d) Two-way: The search can be made forwards or backwards.

e.g. Basic text search: An authoring tool provides both WYSIWYG and source editing-views. The authoring tool provides two-way searching for plain text sequences within both editing-views. The default search option is to search only within the editing-view that the author is currently working within. However, there is an option to search both editing-views simultaneously. When this option is selected, the search results are all displayed in a selectable list that labels each as "Text" or "Source Code", reflecting which editing-view will become active when the author selects the search result. 

#### Guideline A.3.6 Allow users to manage preference settings

A.3.6.2 Save Settings: If the authoring tool includes display and/or control settings, then these settings can be saved between authoring sessions. (**Level AA**)
	- e.g. Storing preferences with author account: A web-based authoring tool requires that authors log in to their accounts before authoring sessions can begin. Because preference settings are associated with author accounts, the settings are applied as soon as authors log in.
A.3.6.3 Apply Platform Settings: The authoring tool respects changes in platform display and control settings, unless authors select more specific display and control settings using the authoring tool. (**Level AA**)
	-e.g. Web-based authoring tool: A web-based authoring tool respects the display and control settings of the user agent on which it is running.

### Principle A.4 Editing-views are understandable

#### Guideline A.4.1 Help authors avoid and correct mistakes

#### Guideline A.4.2 Document the user interface, including all accessibility features

A.4.2.2 Document All Features: For each authoring tool feature, at least one of the following is true: (**Level AA**) (a) Described in the Documentation: Use of the feature is explained in the authoring tool's documentation; or (b) Described in the Interface: Use of the feature is explained in the authoring tool user interface; or ...
	- e.g. All features documented: An authoring tool includes documentation for all of its available features. The documentation conforms to WCAG 2.0 Level A.


## Part B: Support the production of accessible content

### Principle B2 Authors are supported in producing accessible content

#### Guideline B.2.4 Assist authors with accessible templates

B.2.4.1 Accessible Template Options (WCAG): If the authoring tool provides templates, then there are accessible template (WCAG) options for a range of template uses. 

B.2.4.2 Identify Template Accessibility: If the authoring tool includes a template selection mechanism and provides any non-accessible template (WCAG) options, then the template selection mechanism can display distinctions between the accessible and non-accessible options. (**Level AA**) Note: The distinction can involve providing information for the accessible templates, the non-accessible templates or both.
	- e.g. Variety of accessible templates: A web page authoring tool provides several template choices for home pages, guest books, and on-line albums. For each type of functionality, the basic template option is accessible (see the definition of "accessible template (WCAG)"). Content management system: A content management system offers a variety of templates to authors for different purposes (e.g. information page, interactive form page, registration page). All of the templates are accessible.

B.2.4.3 Author-Created Templates: If the authoring tool includes a template selection mechanism and allows authors to create new non-accessible templates (WCAG), then authors can enable the template selection mechanism to display distinctions between accessible and non-accessible templates that they create. (**Level AA**) Note: The distinction can involve providing information for the accessible templates (WCAG), the non-accessible templates or both.

#### Guideline B.2.5 Assist authors with accessible pre-authored content

B.2.5.1 Accessible Pre-Authored Content Options: If the authoring tool provides pre-authored content, then a range of accessible pre-authored content (to WCAG Level AA) options are provided. (**Level AA**)
	- e.g. Clip art collection

B.2.5.2 Identify Pre-Authored Content Accessibility: If the authoring tool includes a pre-authored content selection mechanism and provides any non-accessible pre-authored content (WCAG Level AA) options, then the selection mechanism can display distinctions between the accessible and non-accessible options. (**Level AA**) Note: The distinction can involve providing information for the accessible pre-authored content, the non-accessible pre-authored content or both.

### Principle B3 Authors are supported in improving the accessibility of existing content

#### Guideline B.3.1 Assist authors in checking for accessibility problems

B.3.1.4 Status Report: If the authoring tool provides checks, then authors can receive an accessibility status report based on the results of the accessibility checks. (**Level AA**) Note: The format of the accessibility status report is not specified and they might include a listing of problems detected or a WCAG 2.0 conformance level, etc.
	- e.g. List of accessibility problems, Conformance level report

B.3.1.5 Programmatic Association of Results: If the authoring tool provides checks, then the authoring tool can programmatically associate accessibility checking results with the web content that was checked. (**Level AA**)

### Principle B4 Authoring tools promote and integrate their accessibility features

#### Guideline B.4.1 Ensure the availability of features that support the production of accessible content

B.4.1.3 Feature Deactivation Warning: The authoring tool does not include the option to turn off its accessible content support features or, if these features can be turned off, authors are informed that this may increase the risk of content accessibility problems (WCAG). (**Level AA**)

B.4.1.4 Feature Prominence: All accessible content support features are at least as prominent as features related to either invalid markup, syntax errors, spelling errors or grammar errors. (**Level AA**) 

