# Changelog
All notable changes to the StayHome project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]
### Added
- support additional question types needed for exposure questionnaire

## [0.4] - 2020-03-22
### Added
- help text to added to profile page
- call/text preferred contact methods
- Add a new next page for guest user
- fix favoricon color to purple
- support simple notifications
- add refresh and logout buttons in app bar on calendar page (for convenience, possibly temporary)

### Changed
- Go back to on-the-fly validation for temperature field
- Go back to login page if terms are declined in keycloak
- Resource links now open in a new tab

### Fixed
- fixed profile saving
A
### Removed
- removed terms and conditions from about page

## [0.3] - 2020-03-18
### Added
- "Terms and Conditions" to Keycloak registration flow per https://www.pivotaltracker.com/story/show/171828917

### Changed
- fix logout issue on web platform
- updated trends page chart headers
- allow temperature entry in degrees Celsius (will be converted to degrees Fahrenheit)
- validate questionnaire responses only when submitting questionnaire, rather than in real time
- allow groups of items in learning center

## [0.2] - 2020-03-17
### Changed
- reStyled the Stayhome KeyCloak login page.
- allow learning center page to show resources even when accessed via URL

## [0.1] - 2020-03-16
### Added
- A formal changelog.
- Ability to generate new Patient FHIR and associated FHIR records.

### Changed
- Users can now self register (pre-existing account no longer required).
- Start using "v<MAJOR>.<MINOR> versioning, at v0.1.
- Migrate to new `Stayhome` keycloak realm for authentication.
 
## [20.3.16] - 2020-03-16
### Added
- Validating temperature field in Questionnaire.
- Label added to chart when a point is selected.
- "What's Stayhome" link and backing pages added.
 
## [2020.3.12.0] - 2020-03-12
### Changed
- Font styles used on front page and within app.
- Applied new style and layout to login page.