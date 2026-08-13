# Database Design


## Users Table


| Column | Description |
|-|-|
| id | Primary key |
| google_id | Google account ID |
| email | User email |
| name | User name |
| created_at | Account creation date |
| storage_used | Used storage |
| storage_limit | Maximum storage |



## OTP Records Table


| Column | Description |
|-|-|
| id | Primary key |
| user_id | Connected user |
| service_name | OTP service |
| sender | Email sender |
| otp_code | Extracted OTP |
| subject | Email subject |
| gmail_message_id | Gmail message ID |
| received_at | OTP received time |
| created_at | Database entry time |



## Relationship


Users

1

|

Many

|

OTP Records