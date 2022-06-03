# Simple Subscription App

## Task Description
Create a simple subscription app (only ***RESTful APIs*** with MySQL) in which users can subscribe to a website (there can be multiple websites in the system). Whenever a new post is published on a particular website, all it's subscribers shall receive an email with the post title and description in it. (no authentication of any kind is required)


## Requirements

### Must
- Use ***PHP 7.**** (i.e. use ***Laravel 8*** as ***Laravel 9*** requires PHP 8.0)
- Write migrations for the required tables.
- Endpoint to create a "post" for a "particular website".
- Endpoint to make a user subscribe to a "particular website" with all the tiny validations included in it.
- Use of command to send email to the subscribers.
- Use of queues to schedule sending in background.
- No duplicate stories should get sent to subscribers.
- Fork this repo. When you're done, open a new branch and pull request.

### Optional

- Seeded data of the websites.
- Open API documentation (or) Postman collection demonstrating available APIs & their usage.
- Use of contracts & services.
- Use of caching wherever applicable.
- Use of events/listeners.

### Note
1. Please provide special instructions(if any) to make to code base run on our local/remote platform.
2. Only implement what is mentioned in brief, i.e. only the API, no front-end things etc. 
3. If anything isn't clear, just implement it according to your understanding. As long as it doesn't contradict the briefing, it's fine. 
