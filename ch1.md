# Chapter 1: Give me data

Calling the server to get data is one of most common operation that frontend developers do as a part of their daily
job. It is also one of the easiest to understand using functional programming, so we will start with it.

Most of the code that I have seen or written for doing server/API calls have the below structure:

```javascript
HTTP.get({
    url: "/api/data",
    params: { /* parameters to send */ }
}).then(function (data) {
    // Do something with data, such
    // assign to state, publish an event.
});
```
