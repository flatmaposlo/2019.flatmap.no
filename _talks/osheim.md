---
title: "Galaxy brain: type-dependence and state-dependence in property-based testing"
layout: talk
lookAndFeel: indigo
page_name: "van-geest"
type: "Presentation"
level: "All"
tags:
  - Scala
  - Path Dependant Types
  - Property Based Testing
abstract:
   "<p>Property-based testing is a powerful tool to validate our code, but it is only as good as the random generators which produce its test cases. This talk will demonstrate several techniques to take random generators to the next level and expand the universe of useful types that can be generated.
   </p>"
description: >
   <p>Property-based testing treats tests as functions from generated inputs to an expected result. This testing strategy is effective because the generated inputs often exercise edge cases or unexpected interactions which the author might not have accounted for. Each property represent a set of test cases, and over time random sampling from this set will likely reveal any cases where the property is true (i.e. a bug).</p>
   <p>One potential weakness of property-based testing is that it relies on generating input data that has the appropriate shape to fully exercise code and expose bugs. For example, a bug which only manifests on a list of more than 100 elements will never be found if our generator has no chance of generating lists that are that long. Cases that are harder to handle include: parallel associative structures that need to share a keyspace, directed graphs with interesting internal structure, GADTs, syntax trees, and so on. It can be quite difficult to generate valid instances of these cases that are interesting enough to validate real properties and catch real bugs.</p>
   <p>
   These problems are real and affect the properties and laws of many software projects. However, these problems are also tractable! Taking ScalaCheck as an example we’ll work through these problems together, covering:
   </p>
   <ul>
    <li>how generators work</li>
    <li>techniques for simple recursive generators</li>
    <li>using the state monad in generators to cache and reuse generated values</li>
    <li>how generators work</li>
    <li>generating values with type members to support polymorphic properties</li>
   </ul>
   <p>You will come away from this talk armed with more tools for using property-based testing to validate complex, “real-world” examples which are traditionally difficult to generate.</p>
speakers:
-
  name: "Erik Osheim"
  bio: >
   <p>Erik Osheim is one of the founders of Typelevel, and helps maintains several Scala libraries including Cats, Spire, Jawn, and others. He hacks Scala for a living at Stripe, and is committed to having his cake and eating it too when it comes to functional programming. Besides programming he spends time playing music, drinking tea, thinking about games, and cycling around Providence, Rhode Island.</p>
  image: "osheim.jpg"
  twitter: d6
---
