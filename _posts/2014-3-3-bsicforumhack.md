---
layout: post
title: Basic Forum Hack!
---
As a red team, hacking RBAC forum. We were able to perform cross site scripting by executing malicious javascript as in popping up alerts into the forum. 
We could also perform unauthorised requests as a third person.
The code was vulnerable to SQL injection. We were able to access the details of the topic creation form.
We thought of taking it a step further and tried to insert random records in the table and performing batch queries to drop the table. 
Cross Site Request Forgery was possible. 
Also we could  perform keylogging by executing a malicious external script.

Collaborators : Vanshdeep Chauhan, Elton Mwale, Edwin Francois