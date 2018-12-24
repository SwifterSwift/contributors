# Changelog Guidelines

Here you can find the general guidelines for maintaining the Changelog (or adding new entry). We follow the guidelines from [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) with few additions. 

## Guiding Principles
- Changelogs are for humans, not machines.
- There should be an entry for every single version.
- The same types of changes should be grouped.
- Versions and sections should be linkable.
- The latest version comes first.
- The release date of each versions is displayed.
- Mention whether you follow Semantic Versioning.

... with Moya-specific additions:
- Keep an unreleased section at the top.
- Add PR number and a GitHub tag at the end of each entry.
- Each breaking change entry should have **Breaking Change** label at the beginning of this entry.
- **Breaking Change** entries should be placed at the top of the section it's in.

## Types of changes
- **Added** for new features.
- **Changed** for changes in existing functionality.
- **Deprecated** for soon-to-be removed features.
- **Removed** for now removed features.
- **Fixed** for any bug fixes.
- **Security** in case of vulnerabilities.

## Example:

## [v9.0.0]
### Added
- **FileManager**
  - `createTemporaryDirectory()` to create a directory for saving temporary files. [#615](https://github.com/SwifterSwift/SwifterSwift/pull/615) by [guykogus](https://github.com/guykogus)

### Changed
- **Array**
  - **Breaking Change** `indexes(of:)` has been renamed to `indices(of:)`. [#355](https://github.com/SwifterSwift/SwifterSwift/pull/355) by [Najdan](https://github.com/Najdan)
- **UIView**:
  - Improved performance in `fillToSuperview()` UIView extension. [#540](https://github.com/SwifterSwift/SwifterSwift/pull/540) by [viktart](https://github.com/viktart)
