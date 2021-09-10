# test_release_published

Some tests for github actions and when/how they are triggering events:

Release directly:
 - `published`
 - `released`

Pre-release:
- `published`
- `prereleased`

Promote to a release:
- `released`

Save as draft:
- nothing

Release from draft:
- `released`
- `published`

Pre-release from draft:
- `published`

Promote pre-release that was drafted:
- `released`
