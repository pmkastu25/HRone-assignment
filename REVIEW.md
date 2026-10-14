# REVIEW.md

List every defect you found in the starter `app/main.py` (helpers and endpoints). For each one:

| # | Where (function / line) | What is wrong | How you'd notice it (test, input, or symptom) | How you fixed it |
|---|---|---|---|---|
| 1 | Function: list_employees | items key contains empty array of elements when get request is made even if the (total employees count > 0) from all departments | Postman: test @GET /employees route | Issue: Skips the first 20 employees even when page=1, Fix: Changed skip logic to (page-1) * page_size| 

Also note anything you looked at and decided was **not** a defect, and why.

