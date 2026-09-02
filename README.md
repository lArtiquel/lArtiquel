# Artyom Tsvirko

Senior backend engineer on the JVM. Java and Kotlin since 2017, mostly in domains where a wrong write is expensive: banking (BaaS lending), retail data pipelines, IoT, construction tech, healthcare, e-commerce.

Based in Warsaw, working remotely on B2B.

## What I do

- Design and run microservices on Spring Boot / WebFlux and Micronaut, with Kafka, PostgreSQL and Elasticsearch underneath.
- Event-driven and CQRS systems, including the migrations nobody wants (AWS to GCP, Teradata to BigQuery).
- Public APIs and the plumbing around them: onboarding flows over email and SMS, timezone-aware digest emails, one error contract for internal and external clients.
- Ship to Kubernetes with Terraform and own the pipeline as much as the code.
- Review, mentor, and take the on-call that comes with the above.

## AI

I do most of my day-to-day work through Claude Code and have built up a set of skills around it over the past year: how we review, how a PR gets described, how a Jira ticket is written, how to seed a test database on an ephemeral environment. They talk to Jira, Datadog, Sentry, GitHub and Slack over MCP. For incident investigations I run one agent to dig and a second one that only sees the report and has to check every citation. For slow-moving PRs there is a loop that picks up review-bot comments overnight and fixes them. This summer I went through how our review bot actually reads the repo's guidance files and rewrote mine based on what I found. Outside work I built a Telegram mini-app that turns photos into stylised images and short clips with fal.ai models.

## Stack

Java · Kotlin · Spring Boot · WebFlux · Micronaut · Kafka / Kafka Streams · PostgreSQL · Elasticsearch · Kubernetes · AWS · GCP · Terraform · Docker

TypeScript/React when the backend needs a face. Python and C++ when the problem calls for it.

## Contact

[artware.me](https://artware.me) · tsvirkoartem@gmail.com
