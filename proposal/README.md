# CouchSmurfing

[Heroku link][heroku] **Note:** This should be a link to your production site

[Trello link][trello]

[heroku]: http://www.herokuapp.com
[trello]: https://trello.com/b/Dlrfvj2Q/couchsmurfing

## Minimum Viable Product

CouchSmurfing is a web application inspired by CouchSurfing built using Ruby on Rails
and React/Redux.  By the end of Week 9, this app will, at a minimum, satisfy the
following criteria with smooth, bug-free navigation, adequate seed data and
sufficient CSS styling:

- [ ] Hosting on Heroku
- [ ] New account creation, login, and guest/demo login
- [ ] Hosts
- [ ] Bookings
- [ ] Hosts search (by location & availability) & Google Maps on search
- [ ] Reviews
- [ ] [Production README](docs/production_readme.md)

## Design Docs
* [View Wireframes][wireframes]
* [React Components][components]
* [API endpoints][api-endpoints]
* [DB schema][schema]
* [Sample State][sample-state]

[wireframes]: docs/wireframes
[components]: docs/component-hierarchy.md
[sample-state]: docs/sample-state.md
[api-endpoints]: docs/api-endpoints.md
[schema]: docs/schema.md

## Implementation Timeline

### Phase 1: Backend setup and Front End User Authentication (2 days)

**Objective:** Functioning rails project with front-end Authentication

### Phase 2: Hosts Model, API, and components (2 days)

**Objective:** Hosts can be created, read, edited and destroyed through
the API. Hosts can be populated to the page and scrolled through.

### Phase 3: Details and Requests (2 days)

**Objective:** Hosts can be clicked in for details. Hosts can be
requested for range of dates.

### Phase 4: Host Filter (2 days)

**Objective:** Hosts can be filtered by date and other criteria and be
selected through the GoogleMaps API.

### Phase 5: Reviews (1 day, W2 Th 6pm)

**Objective:** Hosts can have reviews left on them and persisted to the DB.

### Phase 6: - Fix issues, finish styling (1 day, W2 F 6pm)

**Objective:** Finish all pending tasks.

### Bonus Features (TBD)
- [ ] Messaging
- [ ] User profiles
