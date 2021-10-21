---
id: page-header-fields
title: Page header/frontmatter field
---
# Page header/frontmatter field

Each page requires a header, or 'frontmatter'. The frontmatter contains the metadata about the document, and is not displayed on the web page.

Frontmatter example:

```
---
id: usually-file-name
title: Page header/frontmatter field
---
```

### Contents
The frontmatter should contain:

`---`

Three dashes to mark the start and end of the frontmatter. They are always on separate lines. There are no spaces between the dashes.

`id:`

The page identification. This should be the file name.

`title:`

The title of the page. This should be the same as the header 1 title (# heading1)

`weight:`

This number sorts where the page will display in its section on the sidebar menu. The lower the number of the weight, the higher the position it will be in that section. See [**File organisation**](writing/file-organisation.md) for further details.

`last_reviewed_on`

This date has a yyyy-mm-dd format. When you change or review content, you must enter the date.

It is important this is kept up to date, as regular reviews of the content are scheduled and alerts sent, based on that date.

`review_in:`

The length of time between reviews is decided upon by the page owner or writer.

This is set by the original writer, and varies depending on how often the team thinks the content will need review. The system will alert the Owner when this is due (either by email or in relevant Slack channel?). This date length may be changed if required. The format for entering the review length is: 'number weeks', 'number months', 'number years'.

`owner:`

The owner of the team. This field is used to generate review alerts and Slack channel help links. The page will not publish if this field is left empty, or is incorrect.
