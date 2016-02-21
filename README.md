# Timestamp behavior for Meteor Astronomy

The `timestamp` behavior adds two fields that store information about document's creation and update dates.

A detailed information about behavior can be found [here](http://astronomy.jagi.io/#timestamp).

+ the `hasCustomCreated` option added.

```js
var post = new Post();
//You can set the createdAt if hasCustomCreated is true:
//Or the current time added.
post.set('createdAt', new Date());
post.save();

post.createdAt; // A document created time.
```
