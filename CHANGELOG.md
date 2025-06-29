# Changelog

## Recent Changes (Latest First)

### Elided Fallback Name Improvements (PR #52)
- **Fixed**: Ensure that the name is explicitly a dict, as fonttools requires this (commit ee42ae1)
- **Added**: Document elided fallback name ID in example stylespace (commit d8d396d)
- **Added**: Test coverage for invalid and NameRecord elided fallbacks, and existing behaviour (commit 0f0a4f2)
- **Fixed**: Error if the raw ID specified for the elided fallback is not in the TTF (commit 9fe7365)
- **Enhancement**: Allow elided fallback to be provided as a NameRecord instead of a raw ID (commit ed40a1f)

### Documentation & Build Updates
- **Added**: uv + tox instructions in documentation (commit a1c7885)
- **Fixed**: CLI typo (commit 1493c4e)
- **Updated**: Lock file (commit bc8860b)

### Mac Names Support Changes (PR #48)
- **Change**: Dropped automatic Mac name generation by default
- Mac names are now opt-in via `--mac-names` CLI flag

### CI/CD Improvements
- **Updated**: GitHub Actions workflow for better test coverage
- **Added**: Support for PyPy in test matrix
- **Fixed**: Various CI/CD issues with publishing and testing

### Development Infrastructure
- **Migration**: Moved to uv for dependency management
- **Updated**: Support for Python 3.13
- **Enhanced**: Test coverage configuration

## Version History

The project follows semantic versioning and is currently at a stable release (Development Status :: 5 - Production/Stable).