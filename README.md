Github Issues MediaWiki Extension
=================================

Adds a tag to render a list of Github issues inline.

Usage
-----

```html
<githubissues src="https://github.com/aaronpk/p3k/issues?labels=priority%3Aitching">
```

The base URL must be of the format `https://github.com/{user}/{repo}/issues`. Any of
the filters on the [issues list API endpoint](http://developer.github.com/v3/issues/#list-issues-for-a-repository) 
are accepted in the query string. 

When the page is rendered, the titles and description of all referenced issues will
be rendered in place of the tag. You can set the header level for the titles with 
the `header` attribute (the default is h3). For example:

```html
<githubissues header="h2" src="https://github.com/aaronpk/p3k/issues?labels=priority%3Aitching">
```


License
-------

Copyright 2013 by Aaron Parecki

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.



