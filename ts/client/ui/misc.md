# Misc
`TS.client.ui` exposes a number of miscellaneous functions

---

## sendMsgFromUserFromSSB 
`TS.client.ui.sendMsgFromUserFromSSB(t, i, n)` sends a message from the current user to a given channel id

### Parameters
* `t` (channel id) a valid Channel ID as a `string`
* `i` (message) the message body
* `n` (timestamp) seems to be a time stamp for attaching `i` as a reaction 