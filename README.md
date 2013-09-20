# A Collection of .tfignore Templates

For use with Team Foundation Server||Service

Please feel free to contribute additional templates or modification to existing ones via fork + pull request.

Similar to .gitignore files, the following rules apply to a .tfignore file:

- `#` begins a comment line
- The `*` and `?` wildcards are supported.
- A filespec is recursive unless prefixed by the \ character.
- ! negates a filespec (files that match the pattern are not ignored)

The effects are recursive with .tfignore files in sub directories overriding the parent. Further details available here http://msdn.microsoft.com/en-us/library/ms245454.aspx
