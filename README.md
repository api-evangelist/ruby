# Ruby Programming Language and Popular API Gems (ruby)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A profile of the Ruby programming language ecosystem from an API perspective: the language and its standard library HTTP surface (Net::HTTP), the rubygems.org package registry and its public v1/v2 REST API, Bundler, RBS type signatures, popular HTTP/REST client gems (Faraday, http.rb, HTTParty, Excon, Typhoeus, REST Client, HTTPClient), and the major Ruby frameworks used to build APIs (Rails API mode, Sinatra, Grape).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ruby/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ruby/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Programming Language
- Ruby
- HTTP
- REST
- API Clients
- Frameworks
- Libraries
- Package Registry

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Net::HTTP (Ruby Standard Library)

The HTTP client class shipped with the Ruby standard library. Provides class and instance methods for GET, POST, PUT, DELETE, HEAD, PATCH, OPTIONS, TRACE plus WebDAV methods (COPY, LOCK, MKCOL, MOVE, PROPFIND, PROPPATCH, UNLOCK), TLS, proxy support, and configurable timeouts. Backs many higher-level gems such as Faraday's default adapter.

- **Human URL:** [https://docs.ruby-lang.org/en/master/Net/HTTP.html](https://docs.ruby-lang.org/en/master/Net/HTTP.html)

#### Tags

- HTTP Client
- Standard Library
- Built-In

#### Properties

- [Documentation](https://docs.ruby-lang.org/en/master/Net/HTTP.html)
- [Git Hub](https://github.com/ruby/net-http)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RubyGems.org Registry API v1

Public REST API for the rubygems.org package registry. Endpoints cover gems, versions, downloads, owners, profiles, web hooks, activity, API keys, and OIDC/trusted-publishing token exchange. Authentication is via an API key in the Authorization header with optional OTP header for MFA. Responses available as JSON or YAML.

- **Human URL:** [https://guides.rubygems.org/rubygems-org-api/](https://guides.rubygems.org/rubygems-org-api/)
- **Base URL:** `https://rubygems.org/api/v1`

#### Tags

- Package Registry
- REST
- Public API

#### Properties

- [Documentation](https://guides.rubygems.org/rubygems-org-api/)
- [API Reference](https://guides.rubygems.org/rubygems-org-api/)
- [Authentication](https://guides.rubygems.org/api-key-scopes/)
- [Git Hub](https://github.com/rubygems/rubygems.org)
- [SDK](https://github.com/rubygems/gems)
- [OpenAPI](openapi/rubygems-registry-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/rubygems-registry-gem-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/rubygems-registry-version-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/rubygems-registry-owner-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/rubygems-registry-webhook-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/rubygems-registry-gem-structure.json)
- [JSON Structure](json-structure/rubygems-registry-version-structure.json)
- [Example](examples/rubygems-registry-get-gem-example.json)
- [Example](examples/rubygems-registry-list-versions-example.json)
- [Example](examples/rubygems-registry-list-owners-example.json)
- [Example](examples/rubygems-registry-search-example.json)
- [Example](examples/rubygems-registry-create-webhook-example.json)

### RubyGems.org Registry API v2

Version 2 of the rubygems.org registry API. Adds gem version detail endpoints with optional platform query parameter, returning richer metadata than v1.

- **Human URL:** [https://guides.rubygems.org/rubygems-org-api-v2/](https://guides.rubygems.org/rubygems-org-api-v2/)
- **Base URL:** `https://rubygems.org/api/v2`

#### Tags

- Package Registry
- REST
- Public API

#### Properties

- [Documentation](https://guides.rubygems.org/rubygems-org-api-v2/)
- [API Reference](https://guides.rubygems.org/rubygems-org-api-v2/)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bundler

Dependency manager for Ruby. Reads a Gemfile, resolves and installs gems from rubygems.org or alternate sources, and writes Gemfile.lock for reproducible installs across environments. Ships as part of modern Ruby distributions.

- **Human URL:** [https://bundler.io/](https://bundler.io/)

#### Tags

- Dependency Management
- CLI
- Package Manager

#### Properties

- [Documentation](https://bundler.io/docs.html)
- [Git Hub](https://github.com/rubygems/rubygems)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RBS (Ruby Type Signatures)

A language for describing the structure of Ruby programs. Lets developers declare classes, modules, method signatures, instance variables and inheritance in separate .rbs files so type checkers and IDE tooling can verify code against an explicit contract.

- **Human URL:** [https://github.com/ruby/rbs](https://github.com/ruby/rbs)

#### Tags

- Type System
- Schema
- Contracts

#### Properties

- [Git Hub](https://github.com/ruby/rbs)
- [Documentation](https://github.com/ruby/rbs#readme)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Faraday

Simple but flexible HTTP client library with a common interface over many adapters (Net::HTTP, Typhoeus, Patron, Excon, HTTPClient, and others) and Rack-style middleware for request/response processing.

- **Human URL:** [https://lostisland.github.io/faraday/](https://lostisland.github.io/faraday/)

#### Tags

- HTTP Client
- Middleware

#### Properties

- [Documentation](https://lostisland.github.io/faraday/)
- [Git Hub](https://github.com/lostisland/faraday)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HTTParty

HTTP client gem that "makes consuming RESTful web services dead easy" via a class-level DSL. Wraps Net::HTTP with parsing, query handling, and authentication helpers.

- **Human URL:** [https://github.com/jnunemaker/httparty](https://github.com/jnunemaker/httparty)

#### Tags

- HTTP Client
- REST

#### Properties

- [Git Hub](https://github.com/jnunemaker/httparty)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### http.rb

Fast Ruby HTTP client built on the llhttp parser with a chainable request-building API, streaming bodies, persistent connections, and fine-grained timeout control.

- **Human URL:** [https://github.com/httprb/http](https://github.com/httprb/http)

#### Tags

- HTTP Client
- Streaming

#### Properties

- [Git Hub](https://github.com/httprb/http)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Excon

EXtended HTTP(S) CONnections library focused on performance, persistent connections, and predictable behavior. Used as an adapter under Faraday and inside Fog/cloud SDKs.

- **Human URL:** [https://github.com/excon/excon](https://github.com/excon/excon)

#### Tags

- HTTP Client

#### Properties

- [Git Hub](https://github.com/excon/excon)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Typhoeus

Libcurl-based HTTP client built for running HTTP requests in parallel. Pairs well with Hydra for fan-out integrations against many APIs at once.

- **Human URL:** [https://github.com/typhoeus/typhoeus](https://github.com/typhoeus/typhoeus)

#### Tags

- HTTP Client
- Parallel

#### Properties

- [Git Hub](https://github.com/typhoeus/typhoeus)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### REST Client

Simple HTTP and REST client for Ruby inspired by Sinatra's microframework style. Provides class-level GET/POST/PUT/DELETE helpers.

- **Human URL:** [https://github.com/rest-client/rest-client](https://github.com/rest-client/rest-client)

#### Tags

- HTTP Client
- REST

#### Properties

- [Git Hub](https://github.com/rest-client/rest-client)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HTTPClient

Long-standing Ruby HTTP client providing "the functionality of libwww-perl (LWP) in Ruby". Supports keep-alive, cookies, proxies, and SSL.

- **Human URL:** [https://github.com/nahi/httpclient](https://github.com/nahi/httpclient)

#### Tags

- HTTP Client

#### Properties

- [Git Hub](https://github.com/nahi/httpclient)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ruby on Rails (API Mode)

Rails generated with the --api flag boots a slimmer middleware stack and an ApplicationController inheriting from ActionController::API (rather than ActionController::Base), making Rails a first-class JSON API framework while keeping Active Record, routing, and generators.

- **Human URL:** [https://guides.rubyonrails.org/api_app.html](https://guides.rubyonrails.org/api_app.html)

#### Tags

- Web Framework
- REST
- JSON API

#### Properties

- [Documentation](https://guides.rubyonrails.org/api_app.html)
- [Git Hub](https://github.com/rails/rails)
- [Website](https://rubyonrails.org/)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sinatra

"DSL for quickly creating web applications in Ruby with minimal effort." Widely used to stand up small HTTP APIs and microservices without the ceremony of a full-stack framework.

- **Human URL:** [https://sinatrarb.com/](https://sinatrarb.com/)

#### Tags

- Web Framework
- Microframework
- DSL

#### Properties

- [Documentation](https://sinatrarb.com/documentation.html)
- [Git Hub](https://github.com/sinatra/sinatra)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Grape

"Opinionated framework for creating REST-like APIs in Ruby." Provides a routing DSL with parameter validation, versioning, and content-negotiation helpers; runs standalone or mounted in Rails.

- **Human URL:** [https://github.com/ruby-grape/grape](https://github.com/ruby-grape/grape)

#### Tags

- Web Framework
- REST
- DSL

#### Properties

- [Git Hub](https://github.com/ruby-grape/grape)
- [Documentation](https://github.com/ruby-grape/grape#readme)
- [Postman Collection](collections/rubygems-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rubygems-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Spectral Rules](rules/rubygems-registry-rules.yml)
- [Vocabulary](vocabulary/ruby-vocabulary.yml)
- [J S O N- L D](json-ld/ruby-context.jsonld)
- [Website](https://www.ruby-lang.org/)
- [Documentation](https://docs.ruby-lang.org/en/)
- [Getting Started](https://www.ruby-lang.org/en/documentation/quickstart/)
- [Downloads](https://www.ruby-lang.org/en/downloads/)
- [Release Notes](https://www.ruby-lang.org/en/news/)
- [Security](https://www.ruby-lang.org/en/security/)
- [Community](https://www.ruby-lang.org/en/community/)
- [Blog](https://www.ruby-lang.org/en/news/)
- [GitHub Organization](https://github.com/ruby)
- [GitHub Organization](https://github.com/rubygems)
- [GitHub Organization](https://github.com/rails)
- [Source Code](https://github.com/ruby/ruby)
- [Registry](https://rubygems.org/)
- [Status Page](https://status.rubygems.org/)
- [Blog](https://blog.rubygems.org/)
- [License](https://www.ruby-lang.org/en/about/license.txt)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
