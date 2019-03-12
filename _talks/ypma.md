---
title: "Building a reactive multi-user document editor in ScalaJS"
layout: talk
lookAndFeel: deep-orange
page_name: "ypma"
type: "Presentation"
level: "Intermediate"
tags:
  - scalajs
  - outwatch
  - akka
  - scala
  - eventsourcing
abstract: >
   <p>Recently, reactive architectures have “graduated” from being backend-only, to also enriching frontend applications. This talk describes the creation of a multi-user structured document editor, which allows full real-time collaboration business documents, using ScalaJS, Outwatch, and Akka. </p>
description: >
   <p>At Tradeshift, we want to enable our users to work more closely together with their colleagues, suppliers, and customers. Real-time communication is becoming a growing feature that enables this, and we found a reactive architecture is a good implementation fit. </p>

   <p>In that context, we are experimenting with a front-end architecture that embraces event-sourcing all the way into the web browser. By exchanging fine-grained events between clients, one can guarantee that all users eventually see the same document, as close to real-time as possible. </p>

   <p>We realize this vision by using functional programming and streaming techniques, which we found a great fit for event sourcing. Outwatch and ScalaJS power the front-end part, with a clustered Akka application as back-end, storing events in a Cassandra cluster. </p>
speakers:
-
  name: "Jan Ypma"
  bio: >
   <p>Jan Ypma is a full-stack software architect at Tradeshift, focusing on developing at scale. He has designed Java enterprise systems at international level in a variety of domains. His background in electrical engineering and embedded software gives him a fresh out-of-box perspective. Jan is a contributor to the Akka framework and other open source projects, and a regular speaker on event sourcing with Java and Scala. </p>
  image: "ypma.png"
---
