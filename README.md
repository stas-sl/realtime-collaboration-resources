# Realtime Collaboration Resources

## Contents
- [Papers](#papers)
- [Talks](#talks)
- [Articles](#articles)
- [Discussions](#discussions)
- [Sources](#sources)
- [Demos](#demos)
- [Examples in real world](#examples-in-real-world)

## Papers

* [A Conflict-Free Replicated JSON Datatype](https://arxiv.org/pdf/1608.03960.pdf)
* [Merging OT and CRDT Algorithms](https://hal.inria.fr/hal-00957167/document)
* [Near Real-Time Peer-to-Peer Shared Editing on Extensible Data Types (about y-js)](https://github.com/y-js/yjs/files/695979/yjs.pdf)
* [Scalable XML Collaborative Editing with Undo](https://arxiv.org/pdf/1010.3615.pdf)
* [An Algorithm for Selective Undo of Any Operation in Collaborative Applications](https://binshao.info/download/undo-group2010.pdf)

## Talks

- [Concurrent Data & OT Alternatives](https://www.youtube.com/watch?v=zo8uGlqQaCo)
- [How we built Synchrony, the engine behind collaborative editing in Confluence](https://www.youtube.com/watch?v=EgCYd6ei7QI)
- [Conflict Resolution for Eventual Consistency - Martin Kleppmann](https://www.youtube.com/watch?v=yCcWpzY8dIA)
- [(Russian) Виктор Грищенко — Swarm: синхронизируем рой устройств](https://www.youtube.com/watch?v=1ddm7WCMclA)
- [Strong Eventual Consistency and Conflict-free Replicated Data Types by Marc Shapiro](https://www.youtube.com/watch?v=oyUHd894w18)

## Articles

* [Understanding and Applying Operational Transformation](http://www.codecommit.com/blog/java/understanding-and-applying-operational-transformation)
* [CRDT Notes](https://github.com/pfrazee/crdt_notes) - Excerpts collected from papers and articles published on the Web
* [A simple approach to building realtime collaborative text editor](http://digitalfreepen.com/2017/10/06/simple-real-time-collaborative-text-editor.html) - Nice explanation of CRDTs
* [(Russian) Рождение, жизнь и смерть Волны - причины почему умер Google Wave](https://geektimes.ru/post/139475)

## Discussions

* [A Conflict-Free Replicated JSON Datatype on Hacker News](https://news.ycombinator.com/item?id=12303100)
* [Apache Wave on Hacker News](https://news.ycombinator.com/item?id=7532059)
* [ShareJS Google Group](https://groups.google.com/forum/#!forum/sharejs)

## Sources

* https://github.com/share/sharedb [JavaScript] - Realtime database backend based on Operational Transformation of JSON documents, uses MongoDB and Redis
* https://github.com/rizzoma [CoffeeScript/JavaScript] - Google Wave clone based on ShareDB
* https://github.com/gritzko/swarm [JavaScript] - CRDT implementation
* https://github.com/gulf [JavaScript] - Operational transformation control layer with several bindings to contenteditable, quill editor, socialcalc. Though the author says he found something better than OT - CRDT
* https://github.com/dmitryuv/atext-changeset [JavaScript] - A library for building collaborative rich-text editors using operational transformation. It's based on easysync spec from the Etherpad-Lite project
* https://github.com/goodow/realtime-store [Java] - Google Docs–style collaboration via the use of operational transforms. Documents are made of 4 types of collaborative elements: String, Lists, Maps and Custom objects. A Goodow Realtime Store collaborative document can have as many of these collaborative elements as they need
* https://github.com/Operational-Transformation/ot.js [JavaScript] - Operational Transformation Implementation (for text)
* https://github.com/automerge/automerge [JavaScript] - Automerge is a library of data structures for building collaborative applications in JavaScript
* https://github.com/automerge/trellis [JavaScript] - Trellis is a Trello clone built as an Electron desktop application. We built Trellis to demo MPL, a distributed persistence library that allows developers to build collaborative applications that are realtime, offline, and network partition tolerant. Uses [automerge](https://github.com/automerge/automerge) library
* https://github.com/goodow/realtime-operation
* https://github.com/marcelklehr/changesets
* https://github.com/hivejs
* https://github.com/marcelklehr/warp
* https://github.com/marcelklehr/dom-ot
* https://github.com/y-js/yjs
* https://github.com/kbadk/json0-ot-diff
* https://github.com/usecanvas
* https://github.com/Evercoder
* https://github.com/Ramonlord/moqups
* https://github.com/apache/incubator-wave 
* https://github.com/rudi-c/alchemy-book

## Demos
* http://alchemy.digitalfreepen.com
* http://realtimeplayground.goodow.com
* https://operational-transformation.github.io/visualization.html - Operational Transformation Visualization

## Examples in real world

* https://drive.google.com
* https://colab.research.google.com
* https://datastudio.google.com
* https://trello.com
* https://www.dropbox.com/paper
* https://www.figma.com
* https://rizzoma.com
* https://moqups.com
* http://etherpad.org
* https://www.nuclino.com
* https://quip.com
* https://mural.co
* https://realtimeboard.com

----

## Contributions

Have anything in mind that you think would fit in this list? Feel free to send a [pull request](https://github.com/stas-sl/awesome-realtime-collaboration/pulls).
