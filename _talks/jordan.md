---
title: "Tagless Final: Purity And Performance In Scala"
layout: talk
lookAndFeel: orange
page_name: "jordan"
type: "Workshop"
level: "Intermediate"

tags:
  - scala
  - tagless-final
  - effects

abstract: >
   <p>Effect capture is a core tenant of pure FP. But what effect capture style should you use in Scala?</p>    
   <p>Monad Transformers work well in Haskell, but perform poorly on the JVM. Free Monads allow great abstraction, but involve complex types.</p>
   <p>All hope is not lost! Tagless Final is here to save the day.</p>

description: >
    <p>The workshop is made up of practical exercises that introduce the tagless final style, and demonstrate how this style can be used in real world use cases.</p>
    <p>The workshop is in two parts. The first is a practical introduction to the concept of “Tagless Final Interpreters” with a simple first order language that can express integer arithmetic. Attendees will implement a simple evaluator for this language in the “tagless final” style, and show that the final and initial encodings are equivalent.</p>
    <p>The second part consists of several exercises that build out a simple reading list application, that allows the storage of users, books and reading lists for each user, using the tagless final style.</p>
    <p>
        The exercises will demonstrate;
        <ul>
            <li>The use of tagless final encoding</li>
            <li>Composing tagless final algebras</li>
        </ul>
    </p>
    <p>Using typeclass constraints to abstract over what capabilities are needed in different scenarios. Including, sequential computations with cats.Monad, error handling with cats.MonadError and parallelism with cats.Parallel</p>
    <p>I have run a similar workshop internally at my company. The resources are available <a href="https://github.com/eli-jordan/tagless-final-jam">here</a></p>
    <p>The workshop should take 90-120 minutes</p>

speakers:
- name: "Eli Jordan"
  bio: <p>Elias Jordan, Senior Software Engineer at Tapad, is a Scala developer with 9 years of experience, and a passion for functional programming. Before moving from Sydney, Australia to Oslo, Norway to join the Tapad team, Elias spent 7 years at IBM working as a Lead Developer. In addition to his extensive experience writing in Scala, Elias has also specialized in using programming languages, Haskell and Java. Elias graduated from the University of New South Wales in 2011 with a degree in Computer Science and Mechanical Engineering.</p>
  image: "jordan.jpeg"
---
