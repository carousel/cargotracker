# Changelog
All notable changes to this project will be documented in this file.

## [0.0.1] - 2019-09-26
### Added
- README.md by [Miroslav Trninic](https://github.com/carousel)
- CHANGELOG.md
- build.gradle 
- .gitignore
- directory for legacy documents

### Changed
- build.gradle dependency for JAX-RS org.glassfish.jersey.media:jersey-media-moxy:2.0 (for REST API to work)
- servlet entry into web.xml for rest api context

### Removed
- pom.xml (using gradle instead, need opinions about this)

## [0.0.2] - 2019-09-27
### Changed
- add destinationCoordinates property to Track class (it was missing in original app) [Miroslav Trninic](https://github.com/carousel)
- replace call to `track.destinationCoordinates` with  `track.cargo.destinationCoordinates` in `admin/track.xhtml` (bug from original app)
- update .gitignore 



