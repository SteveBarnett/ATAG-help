# ATAG notes - just WCAG level - short

## Part A: Make the authoring tool user interface accessible

### Principle A1 The authoring tool user interface follows applicable accessibility guidelines

#### Guideline A.1.1 Ensure that web-based functionality is accessible

- If the authoring tool contains web-based user interfaces, then those web-based user interfaces meet the WCAG 2.0 success criteria.

## Part B: Support the production of accessible content

### Principle B1 Fully automatic processes produce accessible content

#### Guideline B.1.1 Ensure that automatically-specified content is accessible

- The authoring tool does not automatically generate web content after the end of an authoring session, or, authors can specify that the content be accessible web content.
- If the authoring tool provides the functionality for automatically generating web content during an authoring session, then at least one of the following is true: the content is accessible without author input (e.g. a bold button in a toolbar uses `strong`); authors are prompted for any required accessibility information; accessibility checking is automatically performed; the authoring tool prompts authors to perform accessibility checking.

#### Guideline B.1.2 Ensure that accessibility information is preserved

- If the authoring tool provides restructuring transformations or re-coding transformations, and if equivalent mechanisms exist in the web content technology of the output, then at least one of the following is true: accessibility information is preserved in the output; authors have the default option to be warned that accessibility information may be lost; accessibility checking is automatically performed; the authoring tool prompts authors to perform accessibility checking. 
- If the authoring tool supports copy and paste of structured content, then any accessibility information is preserved when the authoring tool is both the source and destination and the source and destination use the same web content technology.

### Principle B2 Authors are supported in producing accessible content

#### Guideline B.2.1 Ensure that accessible content production is possible

- The authoring tool does not place restrictions on the web content that authors can specify or those restrictions do not prevent WCAG 2.0 success criteria from being met, e.g. a source content editing-view us available or the output is accessible to WCAG 2.0 Level AA.

#### Guideline B.2.2 Guide authors to produce accessible content

- If authors are provided with a choice of authoring actions for achieving the same authoring outcome (e.g. styling text), then options that will result in accessible web content (WCAG) are at least as prominent as options that will not. 
- If the authoring tool provides mechanisms to set web content properties (e.g. attribute values), then mechanisms are also provided to set web content properties related to accessibility information (WCAG).

#### Guideline B.2.3 Assist authors with managing alternative content for non-text content

- If the authoring tool provides functionality for adding non-text content, then authors are able to modify programmatically associated text alternatives for non-text content. e.g. source content editing-view, Properties dialog

#### Guideline B.2.4 Assist authors with accessible templates

- If the authoring tool provides templates, then there are accessible template (WCAG) options for a range of template uses. 

### Principle B3 Authors are supported in improving the accessibility of existing content

#### Guideline B.3.1 Assist authors in checking for accessibility problems

- !!! If the authoring tool provides authors with the ability to add or modify web content in such a way that a WCAG 2.0 success criterion can be violated, then accessibility checking for that success criterion is provided (e.g. an HTML authoring tool that inserts images should check for alternative text; a video authoring tool with the ability to edit text tracks should check for captions).
	- Note: Automated and semi-automated checking is possible (and encouraged) for many types of web content accessibility problems (WCAG). However, manual checking is the minimum requirement to meet this success criterion. In manual checking, the authoring tool provides authors with instructions for detecting problems, which authors carry out by themselves.!!!

#### Guideline B.3.2 Assist authors in repairing accessibility problems

- If checking can detect that a WCAG 2.0 success criterion is not met, then repair suggestion(s) are provided.
	- Note: Automated and semi-automated repair is possible (and encouraged) for many types of web content accessibility problems (WCAG). However, manual repair is the minimum requirement to meet this success criterion. In manual repair, the authoring tool provides authors with instructions for repairing problems, which authors carry out by themselves.

### Principle B4 Authoring tools promote and integrate their accessibility features

#### Guideline B.4.2 Ensure that documentation promotes the production of accessible content

- A range of examples in the documentation (e.g. markup, screen shots of WYSIWYG editing-views) demonstrate accessible authoring practices (WCAG). e.g. Reference examples are accessible, Screen shots show accessibility features in use