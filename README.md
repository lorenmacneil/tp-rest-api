## Installation

```
yarn add tp-rest-api
```

## Usage

```typescript
import { TP } from "tp-rest-api";

// initialise the API
const api = new TP("subdomain", "yourusername", "yourpassword");

// get a user story
const story = await getStory(123);

// get a task
const task = await getTask(456);

// get a bug
const bug = await getBug(789);

// add a time entry to an entity
const time = await addTime(456, 0.75, 4.25, new Date('2018-09-01'), "Integration testing");

// get a custom value for a project
const value = await getCustomValueForProject(123, "Some Custom Value");
```
