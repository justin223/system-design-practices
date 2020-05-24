# TinyURL
Design a system to take user-provided URL and transform them to a shortened URL that can be redirected back to original one when referenced.

## Requirements
### Functional
1. Given an original URL, the system can generate a short and unique URL, which should be short enouth to be easily copied and pasted into applications.
2. When user visits a short URL, the system should redirect it to the original link.
3. Users can set custom short URLs for their URLs.
4. The short URLs expire after the default time interval, and this time interval can be set by users.

### Non-functional
1. The system must be highly available, since all URL redirects will fail if our service goes down.
2. URL redirection should be performed in real time with minimal delay.
3. Short URLs should not be unpredictable.

### Extras
1. The system should have functions of data statistics and reports.
2. The system should provide RESTful APIs to other systems.

