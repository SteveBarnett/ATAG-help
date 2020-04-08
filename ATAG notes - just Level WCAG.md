# ATAG notes - just WCAG level

## Part A: Make the authoring tool user interface accessible

### Principle A1 The authoring tool user interface follows applicable accessibility guidelines

#### Guideline B.1.1 Ensure that web-based functionality is accessible

A.1.1.1 Web-Based Accessible (WCAG):

If the authoring tool contains web-based user interfaces, then those web-based user interfaces meet the WCAG 2.0 success criteria.

## Part B: Support the production of accessible content

### Principle B1 Fully automatic processes produce accessible content

#### Guideline B.1.1 Ensure that automatically-specified content is accessible

B.1.1.1 Content Auto-Generation After Authoring Sessions (WCAG): The authoring tool does not automatically generate web content after the end of an authoring session, or, authors can specify that the content be accessible web content (WCAG). - e.g. No automatic content generation after authoring sessions: An authoring tool only makes edits to content as directed by the author when the content file is open for authoring (i.e. during an authoring session)

B.1.1.2 Content Auto-Generation During Authoring Sessions (WCAG): If the authoring tool provides the functionality for automatically generating web content during an authoring session, then at least one of the following is true: (**Level A** to meet WCAG 2.0 Level A success criteria; Level AA to meet WCAG 2.0 Level A and AA success criteria; Level AAA to meet all WCAG 2.0 success criteria)

- (a) Accessible: The content is accessible web content (WCAG) without author input; or
- (b) Prompting: During the automatic generation process, authors are prompted for any required accessibility information (WCAG); or
- (c) Automatic Checking: After the automatic generation process, accessibility checking is automatically performed; or
- (d) Checking Suggested: After the automatic generation process, the authoring tool prompts authors to perform accessibility checking.

e.g. Markup behind WYSIWYG: A WYSIWYG web page authoring tool provides authors with a toolbar of options for formatting text. Following the WYSIWYG (what-you-see-is-what-you-get) paradigm, the options are labeled with the visual result (e.g. a bold "B" to represent bold, an italicized "I" to represent italics) of performing the action however, the content that is automatically-generated from those actions actually conforms to WCAG 2.0 (e.g. using strong for bold and em for emphasis), meeting (a).

#### Guideline B.1.2 Ensure that accessibility information is preserved

B.1.2.1 Restructuring and Recoding Transformations (WCAG): If the authoring tool provides restructuring transformations or re-coding transformations, and if equivalent mechanisms exist in the web content technology of the output, then at least one of the following is true ...

B.1.2.2 Copy-Paste Inside Authoring Tool (WCAG): If the authoring tool supports copy and paste of structured content, then any accessibility information (WCAG) in the copied content is preserved when the authoring tool is both the source and destination of the copy-paste and the source and destination use the same web content technology. - Plain text clipboard format, HTML clipboard format. including any accessibility information, and rendered for the author.

### B2 Authors are supported in producing accessible content

#### Guideline B.2.1 Ensure that accessible content production is possible

B.2.1.1 Accessible Content Possible (WCAG): The authoring tool does not place restrictions on the web content that authors can specify or those restrictions do not prevent WCAG 2.0 success criteria from being met. - e.g. No restrictions (source content editing-view): An authoring tool is designed around a source editing-view, allowing motivated and knowledgeable authors to control every detail of the content produced, including following accessible authoring practices. e.g. Accessible workflow exists: An authoring tool is designed such that accessible web content (in this case conforming to WCAG 2.0 Level A) will result.

#### Guideline B.2.2 Guide authors to produce accessible content

B.2.2.1 Accessible Option Prominence (WCAG): If authors are provided with a choice of authoring actions for achieving the same authoring outcome (e.g. styling text), then options that will result in accessible web content (WCAG) are at least as prominent as options that will not. - e.g. Structural markup: A WYSIWYG HTML editor does not include any authoring action options that will necessarily result in web content that will not meet the WCAG 2.0 Level A success criteria. With a toolbar.

B.2.2.2 Setting Accessibility Properties (WCAG): If the authoring tool provides mechanisms to set web content properties (e.g. attribute values), then mechanisms are also provided to set web content properties related to accessibility information (WCAG). - e.g. Context sensitive properties e.g ask for alt for images, Data table for a bar graph.

#### Guideline B.2.3 Assist authors with managing alternative content for non-text content

B.2.3.1 Alternative Content is Editable (WCAG): If the authoring tool provides functionality for adding non-text content, then authors are able to modify programmatically associated text alternatives for non-text content. - e.g. Source content editing-view, Properties dialog

#### Guideline B.2.4 Assist authors with accessible templates

B.2.4.1 Accessible Template Options (WCAG): If the authoring tool provides templates, then there are accessible template (WCAG) options for a range of template uses.

### B3 Authors are supported in improving the accessibility of existing content

#### Guideline B.3.1 Assist authors in checking for accessibility problems

B.3.1.1 Checking Assistance (WCAG): !!! If the authoring tool provides authors with the ability to add or modify web content in such a way that a WCAG 2.0 success criterion can be violated, then accessibility checking for that success criterion is provided (e.g. an HTML authoring tool that inserts images should check for alternative text; a video authoring tool with the ability to edit text tracks should check for captions). Note: Automated and semi-automated checking is possible (and encouraged) for many types of web content accessibility problems (WCAG). However, manual checking is the minimum requirement to meet this success criterion. In manual checking, the authoring tool provides authors with instructions for detecting problems, which authors carry out by themselves. !!!

#### Guideline B.3.2 Assist authors in repairing accessibility problems

B.3.2.1 Repair Assistance (WCAG):

If checking (see Success Criterion B.3.1.1) can detect that a WCAG 2.0 success criterion is not met, then repair suggestion(s) are provided. Note: Automated and semi-automated repair is possible (and encouraged) for many types of web content accessibility problems (WCAG). However, manual repair is the minimum requirement to meet this success criterion. In manual repair, the authoring tool provides authors with instructions for repairing problems, which authors carry out by themselves. - e.g. Combined check-repair feature

### B4 Authoring tools promote and integrate their accessibility features

#### Guideline B.4.2 Ensure that documentation promotes the production of accessible content

B.4.2.1 Model Practice (WCAG): A range of examples in the documentation (e.g. markup, screen shots of WYSIWYG editing-views) demonstrate accessible authoring practices (WCAG). - e.g. Reference examples are accessible, Screen shots show accessibility features in use
