# Lenses for MathHub
These are mostly for testing the implementation, Lenses are essentially play-lists for MathHub

## Examples
We give a couple of mock-up examples for lenses.
* `MiKo.json`: a relatively deeply structured tree supposedly of personal favorites.
* `educational.json`: a filter that restricts to educational materials, note that it also contains repository groups that are private, and thus need not be visible in a public MathHub.
* `thlib.json`: a filter that restricts to theorem prover libraries. 

## Other possible Lenses
We have not implemented the following yet.
* a lens that represents a scientific journal
* a lens of materials endorsed by an academic society
* a lens for suggested reading for a particular course. 

## Format

Here is the meaning of the fields:
* `name`: the name/identifier of the lens
* `author`: who did it
* `badg`: the badge to be used in the MathHub FrontEnd
* `created`, `date`: first/last edit
* `description`, `teaser`: a short/one-line description of the purpose and "charter" of the lens
* `paths`: a tree of path descriptions that are approved in this lens
* `nopaths`: a list of path components that are excluded here (at most one of `path` or `nopath` can be present)
* `path`: a path component name, this is a component of the MMT URI
* `note`: a comment
* `weight` the rate of approval, an float between 0 and 1, the default value is 1.0
