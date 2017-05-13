A Rest Service Test

Purpose:

This Service will recieve a message in XML format with the following data:

UserName
Password
Message

This service will only accept messages from the following users:

UserName: Paul
Password: 2588

UserName: Jeremy
Password: 8787

Try entering a username or password not valid above to recieve a failure message from the service.

The format to send a request to the service should be:

<MessageRequest>
  <Username><Username>
  <Password><Password>
  <Message><Message>
<MessageRequest/>
