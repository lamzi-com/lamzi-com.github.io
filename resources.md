---
layout: default
title: Resources
---

This page collects tools, libraries and references that I regularly use or find particularly valuable. Most of them 
revolve around software architecture, automation and living documentation, as I believe the best tools are the ones 
that quietly remove friction. The list is intentionally small and curated. I only include resources that I would happily 
recommend.


## ArchUnit

More than an architecture testing library, I see ArchUnit as a way to reduce cognitive load.
By expressing design and architectural decisions as executable rules rather than written guidelines, it helps keep
systems consistent over time while removing the need to constantly remember
conventions. - [ArchUnit](https://www.archunit.org/)

## AssertJ

AssertJ provides a fluent and expressive assertion API that makes tests easier to read and understand. I particularly
appreciate its support for soft assertions and descriptive failure messages, which help produce more informative test
reports than a simple pass/fail result. -  [AssertJ](https://assertj.github.io/doc/)

## Checkstyle

Checkstyle enforces coding conventions through executable rules, ensuring they are applied consistently without relying
on manual review. By automating these checks, reviewers can focus on design and implementation rather than policing
conventions. - [Checkstyle](https://checkstyle.sourceforge.io/)

## JavaParser

An excellent library for parsing and analyzing Java source code. It is particularly useful for building code-driven
tools and documentation generators. - [GitHub](https://github.com/javaparser/javaparser)

## jsqlparser

I primarily use JSqlParser as a foundation for automation: generating documentation from SQL schemas, producing testing
utilities, and analyzing queries captured through tools such as
P6Spy. - [GitHub](https://github.com/jsqlparser/jsqlparser)

## Mermaid

Mermaid is a convenient text-based diagramming language for quickly creating readable diagrams that follow familiar
conventions. Its JavaScript-based rendering model can be limiting when integrating it into static or Java-based
documentation pipelines, but its widespread support across platforms such as GitHub, GitLab and Confluence makes it a
practical choice for documentation-as-code workflows. - [Mermaid](https://mermaid.js.org/)

## mermaid-java-dsl

A type-safe Java DSL for building Mermaid diagrams through a fluent API instead of manually assembling strings.
By modelling Mermaid concepts directly in Java, it makes diagram generation easier to write, refactor and validate
while avoiding many classes of syntax errors. - [GitHub](https://github.com/lamzi-com/mermaid-java-dsl)

## Mustache.Java

A lightweight templating engine that I find particularly useful for generating code and documentation.
Its simplicity makes it easy to integrate into custom tooling without getting in the
way. - [GitHub](https://github.com/spullara/mustache.java)

## P6Spy

P6Spy makes database interactions observable by exposing the SQL actually executed by the application.
It removes much of the guesswork when debugging ORM behavior and investigating performance
issues - [GitHub](https://github.com/p6spy/p6spy)

## Renovate 

Renovate continuously updates dependencies through small, automated pull requests, making maintenance a routine 
activity instead of an occasional large-scale effort. I find this approach much easier to review, validate and integrate
than infrequent bulk upgrades. - [Renovate](https://www.mend.io/renovate/)

## Spotless

Spotless automatically applies consistent formatting, preventing large formatting diffs from obscuring meaningful
changes in code reviews. It integrates seamlessly with IDEs and build pipelines. I use it together with
[palantir-java-format](https://github.com/palantir/palantir-java-format), which I find opinionated enough to ensure
consistency while remaining unobtrusive in day-to-day development. - [GitHub](https://github.com/diffplug/spotless)

## Structurizr

My preferred approach for architecture documentation using the C4 model. By deriving multiple views from a single 
underlying model, Structurizr helps keep diagrams consistent with one another while its Java API integrates naturally 
into automated documentation workflows. - [Structurizr](https://structurizr.com/)

## swagger-parser
Swagger Parser provides a rich object model for OpenAPI specifications, making it easy to build custom tooling and 
documentation. I find it particularly valuable for presenting APIs in a more accessible way, helping both technical 
and non-technical stakeholders spot inconsistencies, omissions and design issues that are less obvious in the raw 
specification. - [GitHub](https://github.com/swagger-api/swagger-parser)