[![Board Status](https://volvogroup.visualstudio.com/c0c50237-a3c8-42a0-b44c-114e2c8cf2ea/98296034-d8f0-4a30-8b09-29bd4654a170/_apis/work/boardbadge/0057c2f2-927e-485d-8315-74c4ccf15978)](https://volvogroup.visualstudio.com/c0c50237-a3c8-42a0-b44c-114e2c8cf2ea/_boards/board/t/98296034-d8f0-4a30-8b09-29bd4654a170/Microsoft.FeatureCategory)
# Testing Conferences
[![CircleCI](https://circleci.com/gh/TestingConferences/testingconferences.github.io.svg?style=shield)](https://circleci.com/gh/TestingConferences/testingconferences.github.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)

This is a simple list of software testing conferences and workshops published collaboratively with the testing community.


## Contributing Guidelines
The list of events is driven by files in the ```_data``` folder - if you have an update for those things, just change the ```current.yml``` and ```past.yml``` files and send a PR.
  - The _order_ of the events listed in ```current.yml``` and ```past.yml``` dictates the _order_ displayed, please make sure to properly insert events.
  - If possible, spell out the conference name and add the abbreviation. Otherwise just use the abbreviation:
    - Example: Workshop on Performance and Reliability (WOPR)
  - Include the year
    - Sometimes workshops use a version instead of a the year
      - Example: Workshop on Performance and Reliability (WOPR) 24
  - Don't include the @ symbol for the twitter handle. If there is no twitter option, leave it blank
  - Optionally include a status such as:
    - CFP is open (CFP == Call for Proposal)
    - CFP is closed
    - Registration is open
    - Registration is closed
  - Optionally include a link to a conference video playlist. This will only appear for past conferences and can be added directly to the ```past.yml``` file.
    - These should be videos from the conference presentations or talks. No marketing videos please.  

## Eligible Conferences and Workshops

Focus is a goal of this project and as a result, only conferences, un-conferences and workshops that are specifically for software testing are listed. That means that if a conference covers software testing, but is not specifically for testers, then it is left out.

A good rule of thumb for whether a conference should be included is if its name includes either Testing or Test and how it describes itself.

## License

TC.org is released under the [MIT License](MIT-LICENSE).
