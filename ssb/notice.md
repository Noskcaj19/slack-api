# Notice

## `winssb.notice`
Exposes a function `notify` which is used to send native desktop notifications.

### Parameters
Accepts a single object
Known fields are:
* title
* content

### Example

```js
// Send alert to user
winssb.notice.notify({ title: 'foo', content: 'bar' })
```