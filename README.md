# Postman API Practice Collection

## Overview

This collection demonstrates **API testing of a mock student management system** using **JSON Server**.

It includes requests to:

* Get all students
* Get an individual student
* Add a new student
* Update a student
* Delete a student

Each request has **test snippets** to check status codes, response time, and JSON response content.

---

## Prerequisites

* Node.js installed: [https://nodejs.org](https://nodejs.org)
* Postman installed: [https://www.postman.com/downloads/](https://www.postman.com/downloads/)
* JSON Server installed globally:

```bash
npm install -g json-server
```

---

## How to Use

1. **Start JSON Server**:

```bash
npx json-server student.json
```

2. **Import the collection** in Postman:

   * Open Postman → Click **Import** → Select `students-api-postman-collection.json`

3. **Run requests**:

   * `GET /students` → All students
   * `GET /students/:id` → Individual student
   * `POST /students` → Add student
   * `PUT /students/:id` → Update student
   * `DELETE /students/:id` → Delete student

4. **Check test results**:

   * Status code
   * Response time
   * JSON content

