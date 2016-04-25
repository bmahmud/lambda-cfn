# Change Log
All notable changes to this project will be documented in this file. For change log formatting, see http://keepachangelog.com/

## Unreleased

## 0.0.10 2016-04-22
- Uses newly released CFN support for Cloudwatch Event Rules
- Update from `queue-async` to `d3-queue`
- Removed lambda-rules binary
- Rules are namespaced with their repository name
- Parameters are namespaced with repository name and rule name
- version incremented for bad v0.0.9 npm release
  
## 0.0.9 2016-04-21
- Not for use, published version is broken
  
## 0.0.8 2016-04-08

### Added
- SNS topic name added to template output to ease configuring snsRules

### Fixed
- Outputs were not being included in final template output
