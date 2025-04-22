*** Manual Test Cases for My Login Page

// Positive Test Case

| Test Case ID | Description      | Steps                                                                 | Expected Result                  |
|--------------|------------------|-----------------------------------------------------------------------|----------------------------------|
| TC001        | Valid Login      | Enter username: admin → password: 1234 → click Login                  | Shows success message or moves to next page |

// Negative Test Cases

| Test Case ID | Description        | Steps                                                           | Expected Result                         |
|--------------|--------------------|------------------------------------------------------------------|-----------------------------------------|
| TC002        | Invalid Password   | Enter username: admin → password: wrongpass → click Login       | Show error: "Invalid credentials"       |
| TC003        | Empty Fields       | Leave both fields blank → click Login                           | Show error: "Please enter credentials"  |
| TC004        | No Password        | Enter username: admin → leave password blank → click Login      | Show error: "Password required"         |
| TC005        | No Username        | Leave username blank → enter password: 1234 → click Login       | Show error: "Username required"         |
