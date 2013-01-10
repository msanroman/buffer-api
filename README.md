Bufferffer.
======

Node wrapper for the Buffer API.

Installation
------------

<pre>
	$ npm install buffer
</pre>

Usage
-----

### CoffeeScript

<pre>
  Buffer = require 'buffer'

  access_token = XXX
  api = new Buffer access_token

  api.getUserInfo (err, user) ->

    if err? then return console.log "Error: #{err}"

    console.log "Name: #{user.name}""
    console.log "Created: #{new Date user.created_at}"
    console.log "Activity: #{new Date user.activity_at}"
</pre>

Note
----

This library is very incomplete as it stands.

The only functionality available is to get the user object.

More functionality will come in time.

License
-------

MIT
