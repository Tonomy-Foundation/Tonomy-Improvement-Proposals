---
name: User Story
about: User Story to describe a new TIP
title: ''
labels: ''
assignees: ''

---

| <!-- -->    | <!-- -->    |
|-------------|-------------|
| **Author** | @theblockstalk |
| **Product(s)** | Tonomy ID |
| **Status** | Idea, Draft, Proposal, In Progress, Done, Closed |

**User Story:**

As a {{ subject }}
I want to {{ action }}
So that I can {{ purpose }}

Tip: be explicit!

**How do you see this being acomplished?**

Who should do this work (e.g. business team, developers...) and what would they do. Share your vision to help us understand the story.

**How does this help the Tonomy Foundation mission?**

How will this help the goals of the product, its users and/or the Tonomy Foundation? Who does it impact?

Mission: https://discord.com/channels/1029385699071381524/1035461305089396756/1044647425178079384

Definition of Done (DoD) is a list of requirements that a user story must adhere to for the team to call it complete. 
While the Acceptance Criteria of a User Story consist of set of Test Scenarios that are to be met to confirm that the software is working as expected.

Test Scenario


Feature: 

 

  Background:

    Given 

    And 

    And 

    And


  Scenario: 

    Given
    When 
    Then 

Feature: Multiple site support

  Only blog owners can post to a blog, except administrators,

  who can post to all blogs.

  Background:

    Given a global administrator named "Greg"

    And a blog named "Greg's anti-tax rants"

    And a customer named "Dr. Bill"

    And a blog named "Expensive Therapy" owned by "Dr. Bill"


  Scenario: Dr. Bill posts to his own blog

    Given I am logged in as Dr. Bill

    When I try to post to "Expensive Therapy"

    Then I should see "Your article was published."


  Scenario: Dr. Bill tries to post to somebody else's blog

    Given I am logged in as Dr. Bill

    When I try to post to "Greg's anti-tax rants"

    Then I should see "Hey! That's not your blog!"


  Scenario: Greg posts to a client's blog

    Given I am logged in as Greg

    When I try to post to "Expensive Therapy"

    Then I should see "Your article was published."



    Independent: Should be self-contained in a way that allows to be released without depending on one another.
    Negotiable: Only capture the essence of user’s need, leaving room for conversation. User story should not be written like contract.
    Valuable: Delivers value to end user.
    Estimable: User stories have to able to be estimated so it can be properly prioritized and fit into sprints.
    Small: A user story is a small chunk of work that allows it to be completed in about 3 to 4 days.
    Testable: A user story has to be confirmed via pre-written acceptance criteria.
