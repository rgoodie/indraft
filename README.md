In Draft
=

Issue:
-
We typically launch surveys or other data gathering projects with Drupal 7 webforms. Sometimes clients don't really scale down the length of their forms, forcing us to expose the Save Draft button. People may save drafts but forget to comeback and submit the final copy. 

Solution:
-
This module provides a table for any given `nid` (or `nid`s) that contains submissions still in a draft status (`is_draft` is `true`) that I can show to non-admins. 

How? 
-
Configured permissions. There is no other configuration. Simply link to `indraft/%` either from another module or in the content. 

```
<a href="indraft/X">See drafts</a>
```