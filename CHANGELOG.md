CHANGELOG
=========


Version 0.3.0 (released in 2013-03-18)
-------------------------------

* [(fea1326)](https://github.com/versatica/JsSIP/commit/fea1326) Don't validate configuration.password against SIP URI password BNF grammar (fix #74).
* [(3f84b30)](https://github.com/versatica/JsSIP/commit/3f84b30) Make RTCSession local_identity and remote_identity NameAddrHeader instances
* [(622f46a)](https://github.com/versatica/JsSIP/commit/622f46a) remove 'views' argument from UA.call()
* [(940fb34)](https://github.com/versatica/JsSIP/commit/940fb34) Refactored Session
* [(71572f7)](https://github.com/versatica/JsSIP/commit/71572f7) Rename causes.IN_DIALOG_408_OR_481 to causes.DIALOG_ERROR and add causes.RTP_TIMEOUT.
* [(c79037e)](https://github.com/versatica/JsSIP/commit/c79037e) Added 'registrar_server' UA configuration parameter.
* [(2584140)](https://github.com/versatica/JsSIP/commit/2584140) Don't allow SIP URI without username in configuration.uri.
* [(87357de)](https://github.com/versatica/JsSIP/commit/87357de) Digest authentication refactorized.
* [(6867f51)](https://github.com/versatica/JsSIP/commit/6867f51) Add 'cseq' and 'call_id' attributes to OutgoingRequest.
* [(cc97fee)](https://github.com/versatica/JsSIP/commit/cc97fee) Fix. Delete session from UA sessions collection when closing
* [(947b3f5)](https://github.com/versatica/JsSIP/commit/947b3f5) Remove RTCPeerConnection.onopen event handler
* [(6029e45)](https://github.com/versatica/JsSIP/commit/6029e45) Enclose every JsSIP component with an inmediate function
* [(7f523cc)](https://github.com/versatica/JsSIP/commit/7f523cc) JsSIP.Utils.MD5() renamed to JsSIP.Utils.calculateMD5() (a more proper name for a function).
* [(1b1ab73)](https://github.com/versatica/JsSIP/commit/1b1ab73) Fix. Reply '200' to a CANCEL 'before' replying 487 to the INVITE
* [(88fa9b6)](https://github.com/versatica/JsSIP/commit/88fa9b6) New way to handle Streams
* [(38d4312)](https://github.com/versatica/JsSIP/commit/38d4312) Add Travis CI support.
* [(50d7bf1)](https://github.com/versatica/JsSIP/commit/50d7bf1) New `grunt grammar` task for automatically building customized Grammar.js and Grammar.min.js.
* [(f19842b)](https://github.com/versatica/JsSIP/commit/f19842b) Fix #60, #61. Add optional parameters to ua.contact.toString(). Thanks @ibc
* [(8f5acb1)](https://github.com/versatica/JsSIP/commit/8f5acb1) Enhance self contact handling
* [(5e7d815)](https://github.com/versatica/JsSIP/commit/5e7d815) Fix. ACK was being replied when not pointing to us. Thanks @saghul
* [(1ab6df3)](https://github.com/versatica/JsSIP/commit/1ab6df3) New method JsSIP.NameAddrHeader.parse() which returns a JsSIP.NameAddrHeader instance.
* [(a7b69b8)](https://github.com/versatica/JsSIP/commit/a7b69b8) Use a random user in the UA's contact.
* [(f67872b)](https://github.com/versatica/JsSIP/commit/f67872b) Extend the use of the 'options' argument
* [(360c946)](https://github.com/versatica/JsSIP/commit/360c946) Test units for URI and NameAddrHeader classes.
* [(826ce12)](https://github.com/versatica/JsSIP/commit/826ce12) Improvements and some bug fixes in URI and NameAddrHeader classes.
* [(e385840)](https://github.com/versatica/JsSIP/commit/e385840) Make JsSIP.URI and JsSIP.NameAddrHeader more robust.
* [(b0603e3)](https://github.com/versatica/JsSIP/commit/b0603e3) Separate qunitjs tests with and without WebRTC. Make "grunt test" to run "grunt testNoWebRTC".
* [(659c331)](https://github.com/versatica/JsSIP/commit/659c331) New way to handle InvalidTargetErorr and WebRtcNotSupportedError
* [(d3bc91a)](https://github.com/versatica/JsSIP/commit/d3bc91a) Don't run qunit task by default (instead require "grunt test").
* [(e593396)](https://github.com/versatica/JsSIP/commit/e593396) Added qunitjs based test unit (for now a parser test) and integrate it in grunt.js.
* [(da58bff)](https://github.com/versatica/JsSIP/commit/da58bff) Enhance URI and NameAddrHeader
* [(df6dd98)](https://github.com/versatica/JsSIP/commit/df6dd98) Automate qunit tests into grunt process
* [(babc331)](https://github.com/versatica/JsSIP/commit/babc331) Fix. Accept multiple headers with same hader name in SIP URI.
* [(716d164)](https://github.com/versatica/JsSIP/commit/716d164) Pass full multi-header header fields to the grammar
* [(2e18a6b)](https://github.com/versatica/JsSIP/commit/2e18a6b) Fix contact match in 200 response to REGISTER
* [(3f7b02f)](https://github.com/versatica/JsSIP/commit/3f7b02f) Fix stun_host grammar rule.
* [(7867baf)](https://github.com/versatica/JsSIP/commit/7867baf) Allow using a JsSIP.URI instance everywhere specting a destination.
* [(a370c78)](https://github.com/versatica/JsSIP/commit/a370c78) Fix 'maddr' and 'method' URI parameters handling
* [(537d2f2)](https://github.com/versatica/JsSIP/commit/537d2f2) Give some love to "console.log|warn|info" messages missing the JsSIP class/module prefix.
* [(8cb6963)](https://github.com/versatica/JsSIP/commit/8cb6963) In case null, emptry string, undefined or NaN is passed as parameter value then its default value is applied. Also print to console the processed value of all the parameters after validating them.
* [(f306d3c)](https://github.com/versatica/JsSIP/commit/f306d3c) hack_ip_in_contact now generates a IP in the range of Test-Net as stated in RFC 5735 (192.0.2.0/24).
* [(528d989)](https://github.com/versatica/JsSIP/commit/528d989) Add DTMF feature
* [(777a48f)](https://github.com/versatica/JsSIP/commit/777a48f) Change API methods to make use of generic 'options' argument
* [(3a6971d)](https://github.com/versatica/JsSIP/commit/3a6971d) Fix #26. Fire 'unregistered' event correctly.
* [(5616837)](https://github.com/versatica/JsSIP/commit/5616837) Rename 'outbound_proxy_set' parameter by 'ws_servers'
* [(37fe9f4)](https://github.com/versatica/JsSIP/commit/37fe9f4) Fix #54. Allow configuration.uri username start with 'sip'
* [(a612987)](https://github.com/versatica/JsSIP/commit/a612987) Add 'stun_servers' and 'turn_servers' configuration parameters
* [(9fad09b)](https://github.com/versatica/JsSIP/commit/9fad09b) Add JsSIP.URI and JsSIP.NameAddrHeader classes
* [(f35376a)](https://github.com/versatica/JsSIP/commit/f35376a) Add 'Content-Length' header to every SIP response
* [(3081a21)](https://github.com/versatica/JsSIP/commit/3081a21) Enhance 'generic_param' grammar rule
* [(e589002)](https://github.com/versatica/JsSIP/commit/e589002) Fix. Allow case-insentivity in SIP grammar, when corresponds
* [(aec55a2)](https://github.com/versatica/JsSIP/commit/aec55a2) Enhance transport error handling
* [(d0dbde3)](https://github.com/versatica/JsSIP/commit/d0dbde3) New stun_servers and turn_servers parameters
* [(47cdb66)](https://github.com/versatica/JsSIP/commit/47cdb66) Add 'extraHeaders' parameter to UA.register() and UA.unregister() methods
* [(69fbdbd)](https://github.com/versatica/JsSIP/commit/69fbdbd) Enhance in-dialog request management
* [(da23790)](https://github.com/versatica/JsSIP/commit/da23790) Fix 'UTF8-NONASCII' grammar rule
* [(3f86b94)](https://github.com/versatica/JsSIP/commit/3f86b94) Require a single grunt task for packaging
* [(81595be)](https://github.com/versatica/JsSIP/commit/81595be) Add some log lines into sanity check code for clarity
* [(a8a7627)](https://github.com/versatica/JsSIP/commit/a8a7627) Enhance RTCPeerconnection SDP error handling. Thanks @ibc for reporting.
* [(3acc474)](https://github.com/versatica/JsSIP/commit/3acc474) Add turn configuration parameters for RTCPeerConnection
* [(9fccaf5)](https://github.com/versatica/JsSIP/commit/9fccaf5) Enhance 'boolean' comparison
* [(24fcdbb)](https://github.com/versatica/JsSIP/commit/24fcdbb) Make preloaded Route header optional.
* [(defeabe)](https://github.com/versatica/JsSIP/commit/defeabe) Automatic connection recovery.
* [(a45293b)](https://github.com/versatica/JsSIP/commit/a45293b) Improve reply() method.
* [(f05795b)](https://github.com/versatica/JsSIP/commit/f05795b) Fix. Prevent outgoing CANCEL messages from being authenticated
* [(5ed6122)](https://github.com/versatica/JsSIP/commit/5ed6122) Update credentials with the new authorization upon 401/407 reception
* [(2c9a310)](https://github.com/versatica/JsSIP/commit/2c9a310) Do not allow reject-ing a Message or Session with an incorrect status code
* [(35e5874)](https://github.com/versatica/JsSIP/commit/35e5874) Make optional the reason phrase when reply-ing
* [(85ca354)](https://github.com/versatica/JsSIP/commit/85ca354) Implement credential reuse
* [(351ca06)](https://github.com/versatica/JsSIP/commit/351ca06) Fix Contact header aggregation for incoming messages
* [(d6428e7)](https://github.com/versatica/JsSIP/commit/d6428e7) Fire UA 'newMessage' event for incoming MESSAGE requests regardless they are out of dialog or in-dialog.
* [(1ab3423)](https://github.com/versatica/JsSIP/commit/1ab3423) Intelligent 'Allow' header field value. Do not set a method in the 'Allow' header field if its corresponding event is not defined or has zero listeners.
* [(4e70a25)](https://github.com/versatica/JsSIP/commit/4e70a25) Allow 'text/plain' and 'text/html' content types for incoming SIP MESSAGE Fixed incoming SIP MESSAGE processing when the Content-Type header contains parameters
* [(d5f3432)](https://github.com/versatica/JsSIP/commit/d5f3432) Fixed the message header split when a parsing error occurs. Parsing error log enhanced.

Version 0.2.1 (released in 2012-11-15)
-------------------------------

* [(24e32c0)](https://github.com/versatica/JsSIP/commit/24e32c0d16ff5fcefd2319fc445a59d6fc2bcb59) UA configuration `password` parameter is now optional.
* [(ffe7af6)](https://github.com/versatica/JsSIP/commit/ffe7af6276915695af9fd00db281af51fec2714f) Bug fix: UA configuration `display_name` parameter.
* [(aa51291)](https://github.com/versatica/JsSIP/commit/aa512913733a4f63af066b0a9e12a8e38f2a5acb) Bug fix: Allows multibyte symbols in UA configuration `display_name` parameter (and require not to write it between double quotes).
* [(aa48201)](https://github.com/versatica/JsSIP/commit/aa48201) Bug fix: "cnonce" value value was not being quoted in Digest Authentication (reported by [vf1](https://github.com/vf1)).
* [(1ecabf5)](https://github.com/versatica/JsSIP/commit/1ecabf5) Bug fix: Fixed authentication for in-dialog requests (reported by [vf1](https://github.com/vf1)).
* [(11c6bb6)](https://github.com/versatica/JsSIP/commit/11c6bb6aeef9de3bf2a339263f620b1caf60d634) Allow receiving WebSocket binary messages (code provided by [vf1](https://github.com/vf1)).
* [(0e8c5cf)](https://github.com/versatica/JsSIP/commit/0e8c5cf) Bug fix: Fixed Contact and Record-Route header split (reported by Davide Corda).
* [(99243e4)](https://github.com/versatica/JsSIP/commit/99243e4) Fixed BYE and ACK error handling.
* [(0c91285)](https://github.com/versatica/JsSIP/commit/0c91285) Fixed failure causes in 'registrationFailed' UA event.

Version 0.2.0 (released in 2012-11-01)
--------------------------------------

* First stable release with full website and documentation.
* Refactored sessions, message and events API.


Version 0.1.0 (released in 2012-09-27)
--------------------------------------

* First release. No documentation.

