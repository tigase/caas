* Supported since Tigase XMPP Server 8.x.x
* Follow documentation for your version on https://docs.tigase.net/#tigase-server
* Make sure `urn:xmpp:mam:1` plugin is enabled in session manager:
~~~
'sess-man' () {
    'urn:xmpp:mam:1' () {}
}
~~~