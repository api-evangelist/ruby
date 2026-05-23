# Ruby Programming Language and Popular API Gems (ruby)

A profile of the Ruby programming language ecosystem from an API perspective:
the language and its standard library HTTP surface (Net::HTTP), the
rubygems.org package registry and its public v1/v2 REST API, Bundler,
RBS type signatures, popular HTTP/REST client gems (Faraday, http.rb,
HTTParty, Excon, Typhoeus, REST Client, HTTPClient), and the major
Ruby frameworks used to build APIs (Rails API mode, Sinatra, Grape).

**URL:** [Visit APIs.yml URL](https://raw.githubusercontent.com/api-evangelist/ruby/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Programming Language, Ruby, HTTP, REST, API Clients, Frameworks, Libraries, Package Registry

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Net::HTTP (Ruby Standard Library)

The HTTP client class shipped with the Ruby standard library. Provides class and instance methods for GET, POST, PUT, DELETE, HEAD, PATCH, OPTIONS, TRACE plus WebDAV methods (COPY, LOCK, MKCOL, MOVE, PROPFIND, PROPPATCH, UNLOCK), TLS, proxy support, and configurable timeouts. Backs many higher-level gems such as Faraday's default adapter.

**Human URL:** [https://docs.ruby-lang.org/en/master/Net/HTTP.html](https://docs.ruby-lang.org/en/master/Net/HTTP.html)

#### Tags

- HTTP Client, Standard Library, Built-In

#### Properties

- [Documentation](https://docs.ruby-lang.org/en/master/Net/HTTP.html)
- [GitHub](https://github.com/ruby/net-http)

### RubyGems.org Registry API v1

Public REST API for the rubygems.org package registry. Endpoints cover gems, versions, downloads, owners, profiles, web hooks, activity, API keys, and OIDC/trusted-publishing token exchange. Authentication is via an API key in the Authorization header with optional OTP header for MFA. Responses available as JSON or YAML.

**Human URL:** [https://guides.rubygems.org/rubygems-org-api/](https://guides.rubygems.org/rubygems-org-api/)

**Base URL:** `https://rubygems.org/api/v1`

#### Tags

- Package Registry, REST, Public API

#### Properties

- [Documentation](https://guides.rubygems.org/rubygems-org-api/)
- [APIReference](https://guides.rubygems.org/rubygems-org-api/)
- [Authentication](https://guides.rubygems.org/api-key-scopes/)
- [GitHub](https://github.com/rubygems/rubygems.org)
- [SDK](https://github.com/rubygems/gems)
- [OpenAPI](openapi/rubygems-registry-openapi.yml)
- [JSONSchema — Gem](json-schema/rubygems-registry-gem-schema.json)
- [JSONSchema — Version](json-schema/rubygems-registry-version-schema.json)
- [JSONSchema — Owner](json-schema/rubygems-registry-owner-schema.json)
- [JSONSchema — WebHook](json-schema/rubygems-registry-webhook-schema.json)
- [JSONStructure — Gem](json-structure/rubygems-registry-gem-structure.json)
- [JSONStructure — Version](json-structure/rubygems-registry-version-structure.json)
- [Example — Get Gem](examples/rubygems-registry-get-gem-example.json)
- [Example — List Versions](examples/rubygems-registry-list-versions-example.json)
- [Example — List Owners](examples/rubygems-registry-list-owners-example.json)
- [Example — Search](examples/rubygems-registry-search-example.json)
- [Example — Create Webhook](examples/rubygems-registry-create-webhook-example.json)

#### Naftiko Capabilities

- [Gems](capabilities/rubygems-registry-gems.yaml)
- [Versions](capabilities/rubygems-registry-versions.yaml)
- [Downloads](capabilities/rubygems-registry-downloads.yaml)
- [Owners](capabilities/rubygems-registry-owners.yaml)
- [Profiles](capabilities/rubygems-registry-profiles.yaml)
- [Webhooks](capabilities/rubygems-registry-webhooks.yaml)
- [Activity](capabilities/rubygems-registry-activity.yaml)
- [API Keys](capabilities/rubygems-registry-api-keys.yaml)
- [OIDC / Trusted Publishing](capabilities/rubygems-registry-oidc.yaml)

### RubyGems.org Registry API v2

Version 2 of the rubygems.org registry API. Adds gem version detail endpoints with optional platform query parameter, returning richer metadata than v1.

**Human URL:** [https://guides.rubygems.org/rubygems-org-api-v2/](https://guides.rubygems.org/rubygems-org-api-v2/)

**Base URL:** `https://rubygems.org/api/v2`

#### Tags

- Package Registry, REST, Public API

#### Properties

- [Documentation](https://guides.rubygems.org/rubygems-org-api-v2/)
- [APIReference](https://guides.rubygems.org/rubygems-org-api-v2/)

### Bundler

Dependency manager for Ruby. Reads a Gemfile, resolves and installs gems from rubygems.org or alternate sources, and writes Gemfile.lock for reproducible installs across environments. Ships as part of modern Ruby distributions.

**Human URL:** [https://bundler.io/](https://bundler.io/)

#### Tags

- Dependency Management, CLI, Package Manager

#### Properties

- [Documentation](https://bundler.io/docs.html)
- [GitHub](https://github.com/rubygems/rubygems)

### RBS (Ruby Type Signatures)

A language for describing the structure of Ruby programs. Lets developers declare classes, modules, method signatures, instance variables and inheritance in separate .rbs files so type checkers and IDE tooling can verify code against an explicit contract.

**Human URL:** [https://github.com/ruby/rbs](https://github.com/ruby/rbs)

#### Tags

- Type System, Schema, Contracts

#### Properties

- [GitHub](https://github.com/ruby/rbs)
- [Documentation](https://github.com/ruby/rbs#readme)

### Faraday

Simple but flexible HTTP client library with a common interface over many adapters (Net::HTTP, Typhoeus, Patron, Excon, HTTPClient, and others) and Rack-style middleware for request/response processing.

**Human URL:** [https://lostisland.github.io/faraday/](https://lostisland.github.io/faraday/)

#### Tags

- HTTP Client, Middleware

#### Properties

- [Documentation](https://lostisland.github.io/faraday/)
- [GitHub](https://github.com/lostisland/faraday)

### HTTParty

HTTP client gem that "makes consuming RESTful web services dead easy" via a class-level DSL. Wraps Net::HTTP with parsing, query handling, and authentication helpers.

**Human URL:** [https://github.com/jnunemaker/httparty](https://github.com/jnunemaker/httparty)

#### Tags

- HTTP Client, REST

#### Properties

- [GitHub](https://github.com/jnunemaker/httparty)

### http.rb

Fast Ruby HTTP client built on the llhttp parser with a chainable request-building API, streaming bodies, persistent connections, and fine-grained timeout control.

**Human URL:** [https://github.com/httprb/http](https://github.com/httprb/http)

#### Tags

- HTTP Client, Streaming

#### Properties

- [GitHub](https://github.com/httprb/http)

### Excon

EXtended HTTP(S) CONnections library focused on performance, persistent connections, and predictable behavior. Used as an adapter under Faraday and inside Fog/cloud SDKs.

**Human URL:** [https://github.com/excon/excon](https://github.com/excon/excon)

#### Tags

- HTTP Client

#### Properties

- [GitHub](https://github.com/excon/excon)

### Typhoeus

Libcurl-based HTTP client built for running HTTP requests in parallel. Pairs well with Hydra for fan-out integrations against many APIs at once.

**Human URL:** [https://github.com/typhoeus/typhoeus](https://github.com/typhoeus/typhoeus)

#### Tags

- HTTP Client, Parallel

#### Properties

- [GitHub](https://github.com/typhoeus/typhoeus)

### REST Client

Simple HTTP and REST client for Ruby inspired by Sinatra's microframework style. Provides class-level GET/POST/PUT/DELETE helpers.

**Human URL:** [https://github.com/rest-client/rest-client](https://github.com/rest-client/rest-client)

#### Tags

- HTTP Client, REST

#### Properties

- [GitHub](https://github.com/rest-client/rest-client)

### HTTPClient

Long-standing Ruby HTTP client providing "the functionality of libwww-perl (LWP) in Ruby". Supports keep-alive, cookies, proxies, and SSL.

**Human URL:** [https://github.com/nahi/httpclient](https://github.com/nahi/httpclient)

#### Tags

- HTTP Client

#### Properties

- [GitHub](https://github.com/nahi/httpclient)

### Ruby on Rails (API Mode)

Rails generated with the `--api` flag boots a slimmer middleware stack and an ApplicationController inheriting from `ActionController::API` (rather than `ActionController::Base`), making Rails a first-class JSON API framework while keeping Active Record, routing, and generators.

**Human URL:** [https://guides.rubyonrails.org/api_app.html](https://guides.rubyonrails.org/api_app.html)

#### Tags

- Web Framework, REST, JSON API

#### Properties

- [Documentation](https://guides.rubyonrails.org/api_app.html)
- [GitHub](https://github.com/rails/rails)
- [Website](https://rubyonrails.org/)

### Sinatra

"DSL for quickly creating web applications in Ruby with minimal effort." Widely used to stand up small HTTP APIs and microservices without the ceremony of a full-stack framework.

**Human URL:** [https://sinatrarb.com/](https://sinatrarb.com/)

#### Tags

- Web Framework, Microframework, DSL

#### Properties

- [Documentation](https://sinatrarb.com/documentation.html)
- [GitHub](https://github.com/sinatra/sinatra)

### Grape

"Opinionated framework for creating REST-like APIs in Ruby." Provides a routing DSL with parameter validation, versioning, and content-negotiation helpers; runs standalone or mounted in Rails.

**Human URL:** [https://github.com/ruby-grape/grape](https://github.com/ruby-grape/grape)

#### Tags

- Web Framework, REST, DSL

#### Properties

- [GitHub](https://github.com/ruby-grape/grape)
- [Documentation](https://github.com/ruby-grape/grape#readme)

## Common Properties

- [SpectralRules](rules/rubygems-registry-rules.yml)
- [Vocabulary](vocabulary/ruby-vocabulary.yml)
- [JSON-LD](json-ld/ruby-context.jsonld)
- [Website](https://www.ruby-lang.org/)
- [Documentation](https://docs.ruby-lang.org/en/)
- [GettingStarted](https://www.ruby-lang.org/en/documentation/quickstart/)
- [Downloads](https://www.ruby-lang.org/en/downloads/)
- [ReleaseNotes](https://www.ruby-lang.org/en/news/)
- [Security](https://www.ruby-lang.org/en/security/)
- [Community](https://www.ruby-lang.org/en/community/)
- [Blog](https://www.ruby-lang.org/en/news/)
- [GitHubOrganization — ruby](https://github.com/ruby)
- [GitHubOrganization — rubygems](https://github.com/rubygems)
- [GitHubOrganization — rails](https://github.com/rails)
- [SourceCode](https://github.com/ruby/ruby)
- [Registry](https://rubygems.org/)
- [StatusPage](https://status.rubygems.org/)
- [Blog — RubyGems](https://blog.rubygems.org/)
- [License](https://www.ruby-lang.org/en/about/license.txt)

## Features

| Name | Description |
|------|-------------|
| Dynamic, Object-Oriented Language | Ruby is a dynamic, open-source programming language with a focus on simplicity and productivity, with everything-is-an-object semantics. |
| Standard Library HTTP Client | Net::HTTP ships in the standard library and covers GET/POST/PUT/DELETE/HEAD/PATCH/OPTIONS/TRACE plus WebDAV verbs and TLS. |
| Public Package Registry API | rubygems.org exposes versioned v1 and v2 REST APIs over HTTPS for discovering, publishing, and managing gems with JSON or YAML responses. |
| Trusted Publishing via OIDC | `/api/v1/oidc/` endpoints let CI providers exchange OIDC tokens for short-lived RubyGems API keys instead of long-lived secrets. |
| Type Signatures with RBS | RBS provides a separate-file type signature language so Ruby code can carry an explicit, machine-checkable contract for IDEs and type checkers. |
| API-First Rails | `rails new --api` generates a Rails app with a JSON-oriented middleware stack and `ActionController::API` as the base class. |

## Use Cases

| Name | Description |
|------|-------------|
| Consuming Third-Party HTTP APIs | Calling external REST APIs from Ruby scripts, jobs, and services using Net::HTTP, Faraday, http.rb, HTTParty, or Excon. |
| Building JSON APIs | Standing up REST/JSON APIs with Rails in `--api` mode, Sinatra, or Grape, optionally documented with OpenAPI tooling. |
| Publishing and Managing Gems | Releasing libraries to rubygems.org via the v1 publish endpoints and the gem and bundler CLIs, including trusted-publishing flows. |
| Mirroring or Caching a Private Gem Server | Running gemstash as a rubygems.org cache and private gem server inside an enterprise. |
| Static Analysis and IDE Support | Writing `.rbs` signatures so type checkers and IDEs can validate method shapes against the implementation. |

## Integrations

| Name | Description |
|------|-------------|
| rubygems.org Registry | The default gem source for bundler and the gem CLI, accessible over HTTPS at `https://rubygems.org` and `https://rubygems.org/api/v1`. |
| GitHub Actions (setup-ruby) | `ruby/setup-ruby` installs prebuilt Ruby versions in CI for building, testing, and publishing gems. |
| OIDC Trusted Publishing | `/api/v1/oidc/` exchanges short-lived CI OIDC tokens for scoped rubygems.org API keys, eliminating long-lived secrets. |
| Fastly CDN | rubygems.org serves gem downloads and the API surface through Fastly edge caching, tracked on status.rubygems.org. |
| HackerOne Vulnerability Disclosure | Ruby core security issues are reported through the official HackerOne program and the `security@ruby-lang.org` mailing list. |

## Solutions

| Name | Description |
|------|-------------|
| Self-Hosted RubyGems with Gemstash | A caching proxy and private gem server for organizations that need air-gapped or controlled gem distribution. |
| Rails-Powered API Backends | Production JSON API backends built on Rails `--api` mode with Active Record, Active Job, and Action Cable as needed. |
| Sinatra Microservices | Lightweight HTTP services and API gateways built on Sinatra's minimal DSL. |

## Artifacts

- **OpenAPI specs (1):** `openapi/rubygems-registry-openapi.yml`
- **JSON Schemas (4):** Gem, Version, Owner, WebHook
- **JSON Structures (2):** Gem, Version
- **JSON-LD contexts (1):** `json-ld/ruby-context.jsonld`
- **Example payloads (5):** Get Gem, List Versions, List Owners, Search, Create Webhook
- **Spectral rulesets (1):** `rules/rubygems-registry-rules.yml`
- **Naftiko capabilities (9):** Gems, Versions, Downloads, Owners, Profiles, Webhooks, Activity, API Keys, OIDC
- **Vocabulary (1):** `vocabulary/ruby-vocabulary.yml`

## Maintainers

- Kin Lane — <kin@apievangelist.com>
