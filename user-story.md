---
name: User Story
about: This template defines a user story
title: ''
labels: ''
assignees: ''

---

**As a** [role]
**I need** [function]
**So that** [benefit]

### Details and Assumptions
* [document what you know]

### Acceptance Criteria
```gherkin
Feature: Gift Management

Scenario: User views gift details successfully
  Given the user is on the gift listing page
  When the user selects a gift
  Then the system should display the full details of the selected gift

Scenario: Search gifts by category
  Given the user is on the search page
  When the user enters category "Furniture"
  Then the system should return a list of matching gifts

Scenario: User registers an account
  Given the user is on the registration page
  When the user submits valid credentials
  Then the system should create a new user account successfully
```
