Lightweight APIs with harvester.js
==========
Or *how I learned to stop worrying and love Node.js APIs*


Disclaimer
----------
This presentation *is* a sales pitch


The why of APIs
---------------
* simple
* composable
* scalable


on simplicity...


![Soap is much more polite than rest](/images/rest-vs-soap.png "Soap is much more polite than rest")


The why of node.js & mongodb
----------------------------
* simple
* scalable
* expressive


The why of jsonapi
------------------
* existing, documented standard
* *no* bikeshedding


on standards...


![XKCD: competing standards](/images/xkcd-standards.png "XKCD: competing standards")


on bikeshedding...


![Alt text](/images/bikeshedding00.png "Reactors are easy to discuss")

 
![Alt text](/images/bikeshedding01.png "Bikesheds, on the other hand, are really hard")


The why of harvester.js
-----------------------
* all of the above +
* *no* boilerplate


on harvester.js...


The what of harvester.js
------------------------
* [an AGCO-backed open-source project](http://developer.agcocorp.com)
* a clone of [fortune.js](http://fortunejs.com/)
* a routing/mapping library
* [an npm package](https://www.npmjs.com/package/harvesterjs)


enough talk, show me the code!


[resource relationships*](http://jsonapi.org/format/#document-structure-resource-relationships)


filtering*


inclusion of linked resources*


but wait, there's more!
-----------------------
* sparse fieldsets*
* sorting*
* errors*
* offset-based pagination
* node-swagger-express ready


lessons from the trenches...



automated testing is your best friend
(especially for dynamic languages)



e2e tests: great fit for APIs 


break the heavy, bloated cycle


fullstack js: great, but no silver bullet


promises: easy to make, hard to keep.
definitely worth it, though



Extending harvester.js
-----------------------
* elastic-harvesterjs: harvester.js meets ElasticSearch
* passport-openam
* event-source-stream

