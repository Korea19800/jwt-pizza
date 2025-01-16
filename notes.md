# Learning notes

## JWT Pizza code study and debugging

As part of `Deliverable ⓵ Development deployment: JWT Pizza`, start up the application and debug through the code until you understand how it works. During the learning process fill out the following required pieces of information in order to demonstrate that you have successfully completed the deliverable.

| User activity                                       | Frontend component | Backend endpoints | Database SQL |
| --------------------------------------------------- | ------------------ | ----------------- | ------------ |
| View home page                                      | home.jsx	         | none              | none         |
| Register new user<br/>(t@jwt.com, pw: test)         | register.jsx       | [POST] /api/auth	 |INSERT INTO user (name, email, password) VALUES (?, ?, ?)INSERT INTO userRole (userId, role, objectId) VALUES (?, ?, ?)|
| Login new user<br/>(t@jwt.com, pw: test)            |     afasdfasfadfs               |         asdfdsf          |    adfadsdasf          |
| Order pizza                                         |             a       |            a       |          a    |
| Verify pizza                                        |           a         |           a        |          a    |
| View profile page                                   |            a        |            a       |       a       |
| View franchise<br/>(as diner)                       |           a         |              a     |           a   |
| Logout                                              |            a        |           a        |         a     |
| View About page                                     |          a          |             a      |        a      |
| View History page                                   |           a         |            a       |     a         |
| Login as franchisee<br/>(f@jwt.com, pw: franchisee) |           a         |           a        |       a       |
| View franchise<br/>(as franchisee)                  |            a        |            a       |      a        |
| Create a store                                      |            a        |              a     |        a      |
| Close a store                                       |            a        |             a      |       a       |
| Login as admin<br/>(a@jwt.com, pw: admin)           |            a        |              a     |         a     |
| View Admin page                                     |            a        |            a       |     a         |
| Create a franchise for t@jwt.com                    |         a           |           a        |       a       |
| Close the franchise for t@jwt.com                   |            a        |           a        |       a       |
