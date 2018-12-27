# Tools to make abuse less fun

Collections and code by Johannes Ridderstedt. Send updates and fixes to johannesl@46elks.com.

Use freely. Public domain.

### temporaryemailproviders.json / temporaryemailproviders.php

A collection of domain names used by disposable / temporary email providers. Useful if you want to block a big part of fake registrations on a website. Remember that this list will never be complete, and that black listing in this way is only a tool, not a complete solution.

Check if a domain matches this list with something like this:
```
if(isset($temporaryEmailProviders[$domain])) {
  doSomething();
}
```