We give a couple of mock-up examples for lenses.

Here is the meaning of the fields:
* `name`: the name/identifier of the lens
* `author`: who did it
* `created`, `date`: first/last edit
* `description`, `teaser`: a short/one-line description of the purpose and "charter" of the lens
* `paths`: a tree of path descriptions that are approved in this lens
* `nopaths`: a list of path components that are excluded here (at most one of `path` or `nopath` can be present)
* `path`: a path component name, this is a component of the MMT URI
* `note`: a comment
* `weight` the rate of approval, an float between 0 and 1
