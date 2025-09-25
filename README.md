# APIs
allows your backend (like a Lambda function) to send a message to a connected WebSocket client.
###Think of it like: client sends → Lambda receives → Lambda replies using post_to_connection.


1. Client (mobile/web) → API Gateway → Backend (Lambda, EC2, DynamoDB, S3)
