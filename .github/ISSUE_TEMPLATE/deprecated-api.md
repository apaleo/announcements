---
name: Do not post issues in this repo. Use apaleo/api instead. - Deprecated API Announcement
about: This repo is for announcements made by apaleo team members only.

---

!!! DO NOT POST ISSUES IN THIS REPO !!!

This repo is for team announcements only.

To file a bug or start a discussion, please go to https://github.com/apaleo/api and create a new issue.

-------

DELETE THIS, it's just to give you some pointers.

Consider following parts:

Title: What is deprecated or changed ("Distribution API changes [March 31st, 2019]", "Changes in the folio-actions API [May 1st, 2019]")
Labels: The section where you can find it, nsfw / v1, new feature
Description:

- What problems this solves / use cases;
- What changed / was removed (specific endpoints)
- Migration path
- Link to guide, if one exists

-------

We are deprecating LIST_OF_FIELDS fields / LIST_OF_ENDPOINTS from the NAME_OF_API API.

On DATE, these fields / endpoints will be removed.

### Affected endpoints:

- **MICROSERVICE1**
  - **API1**
    - ENDPOINT1
    - ENDPOINT2
  - **API2**
    - ENDPOINT3
- **MICROSERVICE2**
  - **API3**
    - ENDPOINT4

### Migration path:

...
