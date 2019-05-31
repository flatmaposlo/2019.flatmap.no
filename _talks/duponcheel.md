---
title: "Program Description Based Programming"
layout: talk
lookAndFeel: red
page_name: "duponcheel"
type: "Presentation"
level: "Intermediate"
youtube: "by7To8QCX9M"
tags: 
  - Dotty
  - Scala
  - FP
abstract: >
   <p>This is about a library, Program Description Based Programming (PDBP), written using Dotty.
      PDBP implements FP, the language presented by John Backus during his Turing Award winning lecture.
      During my 2018 Scala eXchange talk I concentrated the design of PDBP. During this talk I will concentrate on the usage of PDBP.</p>
description: >
   <h4>Like FP</h4>
   <ul><li>PDBP promotes a pointfree functional programming style</li></ul>
   <h4>Unlike FP</h4>
   <ul>
      <li>PDBP separates the description of a program from possible meanings of the program</li>
      <li>PDBP can be extended with extra programming capabilities</li>
      <li>PDBP effects are pure (they are described rather than executed)</li>
   </ul>
   <h4>Foundations</h4>
   <p>The foundations of the library are monads (generalizing expressions) and arrows (generalizing functions).</p>
   <p>Monads promote a pointful programming style. Arrows promote a pointfree programming style.</p>

   <h4>PDBP offers</h4>
   <ul>
    <li>a monad based computation API for library developers</li>
    <li>an arrow based programming API for application developers</li>
   </ul>
   <p>Using Dotty it is possible to flavor the programming API with convenient programming DSL syntax.</p>
speakers:
-
  name: "Luc Duponcheel"
  bio: >
    <p>Luc is a Functional Programming Veteran. He has a Phd in Mathematics.</p>
    <p>He has been a Trainer and Consultant for Java and Scala related projects.</p>
    <p>Luc has worked, among others, with Erik Meijer and Mark P. Jones on Monads.</p>
    <p>His PDBP library is part of the Dotty community build. Moreover he is a passionate cyclist and gardener.</p
  image: "duponcheel.jpg"
  twitter: LucDup
---
