**Below are Predefined Function**

`__construct ($username, $hash, $apiKey=false)`

`getLastRequest ()`

`sendSms ($numbers, $message, $sender, $sched=null, $test=false, $receiptURL=null, $custom=null, $optouts=false, $simpleReplyService=false)`

`sendSmsGroup ($groupId, $message, $sender=null, $sched=null, $test=false, $receiptURL=null, $custom=null, $optouts=false, $simpleReplyService=false)`

`getUsers ()`

`transferCredits ($user, $credits)`

`getTemplates ()`

`checkKeyword ($keyword)`

`createGroup ($name)`

`getContacts ($groupId, $limit, $startPos=0)`

`createContacts ($numbers, $groupid= '5')`

`createContactsBulk ($contacts, $groupid= '5')`

`getGroups ()`

`getMessageStatus ($messageid)`

`getBatchStatus ($batchid)`

`getSenderNames ()`

`getInboxes ()`

`getBalance ()`

`getMessages ($inbox)`

`cancelScheduledMessage ($id)`

`getScheduledMessages ()`

`deleteContact ($number, $groupid=5)`

`deleteGroup ($groupid)`

`getSingleMessageHistory ($start, $limit, $min_time, $max_time)`

`getAPIMessageHistory ($start, $limit, $min_time, $max_time)`

`getEmailToSMSHistory ($start, $limit, $min_time, $max_time)`

`getGroupMessageHistory ($start, $limit, $min_time, $max_time)`

`getSurveys ()`

`getSurveyDetails ()`

`getSurveyResults ($surveyid, $start, $end)`

`getOptouts ($time=null)`