# Penetration Peer Testing

| Participant         | System URL                        | JWT Pizza Service Repo                              |
| ------------------- | --------------------------------- | --------------------------------------------------- |
| **KangJin Kim** | https://pizza.byulage.click/    |    |
| **Katie Greer**  |   |  |

## 1. Self Attack

### KangJin Kim 

#### Finding 1

| Item | Details |
|------|---------|
| Date | 4/8/2025 |
| Target | https://pizza.byulage.click/ |
| Classification | Injection |
| Severity | High |
| Description | SQL injection possible in the curl updateUser command |
| Images | const query = `UPDATE user SET ${params.join(', ')} WHERE id=${userId}`; This directly interpolates values into the SQL string, thus direct array interpolation could be exploited.  |
| Corrections | Added sanitization to Database.js to avoid injection attacks |


### Katie Greer 


## 2. Peer Attack

### Against KangJin Kim 


### Against Katie Greer



