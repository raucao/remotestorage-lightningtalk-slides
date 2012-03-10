!SLIDE

# Unhosted

## All power to the user

!SLIDE

This is not the Ruby you're looking for.

!SLIDE bullets incremental

So what is this about?

* It's about the Web.
* It's about your data.
* It's about regaining control.

!SLIDE bullets incremental

Disclaimer: may contain traces of JavaScript.

!SLIDE

The problem: personal computing has changed.

The cloud is taking over.

!SLIDE bullets incremental

People are losing control over their data.

Data is locked into a single app (and most APIs don't give you full access).

!SLIDE

What existed once on computers and external drives is now stored in the cloud.

!SLIDE

Most likely in the US.

!SLIDE

Data export is not a solution.

You don't want just a backup, you want control over the live data an app is using.

!SLIDE bullets incremental

A potential solution: remoteStorage.

!SLIDE bullets incremental

remoteWHAT?

* Proposing a protocol for letting users choose their own data store for an app
* Main part of the Unhosted open-source project (unhosted.org)
* WIP, but working quite well so far

!SLIDE bullets incremental

Ok, but really: what is it?

* Webfinger for storage discovery by user address
* OAuth for app authorization
* Storage API options: simple REST, CouchDB, ...
* Simple key-value storage – GET/PUT/DELETE

!SLIDE

Quick example...

!SLIDE bullets incremental

Implement in client-side apps with remoteStorage.js

http://github.com/unhosted/remoteStorage.js

!SLIDE

Doesn't have to be client-side.

Feel free to add support to your SaaS.

!SLIDE

Use your own implementation on the server. Or use Frank's favorite place for storing stuff:

http://github.com/5apps/liquor-cabinet

(Thank heavens, some Ruby after all)

!SLIDE bullets incremental

Compatible storage providers:

* OwnCloud – http://owncloud.org
* 5apps (for development) – http://5apps.com
* CouchDB (has to be bootstrapped)

!SLIDE bullets incremental

Any questions:

* You're very welcome in #unhosted on Freenode.
* Tutorial app: http://tutorial.unhosted.5apps.com
* @unhosted
* @skddc

!SLIDE

Participate, donate, or just follow.
