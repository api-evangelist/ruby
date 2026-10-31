# Ruby Programming Language and Popular API Gems

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

**Areas:** Programming Language · Ruby · HTTP · REST · API Client · Framework · Library · Package Registry

## Ruby Programming Language and Popular API Gems on APIs.io

Everything profiled for Ruby Programming Language and Popular API Gems is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ruby/](https://apis.io/providers/ruby/)** — or go straight to one of the APIs or properties below.

### APIs (23)

- [Net::HTTP (Ruby Standard Library)](https://apis.io/apis/ruby/net-http/) — The HTTP client class shipped with the Ruby standard library. Provides class and instance methods for GET, POST, PUT, DELETE, HEAD, PATCH, OPTIONS, TRACE…
- [RubyGems.org Registry API v2](https://apis.io/apis/ruby/rubygems-registry-api-v2/) — Version 2 of the rubygems.org registry API. Adds gem version detail endpoints with optional platform query parameter, returning richer metadata than v1.
- [Bundler](https://apis.io/apis/ruby/bundler/) — Dependency manager for Ruby. Reads a Gemfile, resolves and installs gems from rubygems.org or alternate sources, and writes Gemfile.lock for reproducible…
- [RBS (Ruby Type Signatures)](https://apis.io/apis/ruby/rbs/) — A language for describing the structure of Ruby programs. Lets developers declare classes, modules, method signatures, instance variables and inheritance in…
- [Faraday](https://apis.io/apis/ruby/faraday/) — Simple but flexible HTTP client library with a common interface over many adapters (Net::HTTP, Typhoeus, Patron, Excon, HTTPClient, and others) and…
- [HTTParty](https://apis.io/apis/ruby/httparty/) — HTTP client gem that "makes consuming RESTful web services dead easy" via a class-level DSL. Wraps Net::HTTP with parsing, query handling, and…
- [http.rb](https://apis.io/apis/ruby/http-rb/) — Fast Ruby HTTP client built on the llhttp parser with a chainable request-building API, streaming bodies, persistent connections, and fine-grained timeout…
- [Excon](https://apis.io/apis/ruby/excon/) — EXtended HTTP(S) CONnections library focused on performance, persistent connections, and predictable behavior. Used as an adapter under Faraday and inside…
- [Typhoeus](https://apis.io/apis/ruby/typhoeus/) — Libcurl-based HTTP client built for running HTTP requests in parallel. Pairs well with Hydra for fan-out integrations against many APIs at once.
- [REST Client](https://apis.io/apis/ruby/rest-client/) — Simple HTTP and REST client for Ruby inspired by Sinatra's microframework style. Provides class-level GET/POST/PUT/DELETE helpers.
- [HTTPClient](https://apis.io/apis/ruby/httpclient/) — Long-standing Ruby HTTP client providing "the functionality of libwww-perl (LWP) in Ruby". Supports keep-alive, cookies, proxies, and SSL.
- [Ruby on Rails (API Mode)](https://apis.io/apis/ruby/rails-api/) — Rails generated with the --api flag boots a slimmer middleware stack and an ApplicationController inheriting from ActionController::API (rather than…
- [Sinatra](https://apis.io/apis/ruby/sinatra/) — "DSL for quickly creating web applications in Ruby with minimal effort." Widely used to stand up small HTTP APIs and microservices without the ceremony of a…
- [Grape](https://apis.io/apis/ruby/grape/) — "Opinionated framework for creating REST-like APIs in Ruby." Provides a routing DSL with parameter validation, versioning, and content-negotiation helpers;…
- [Ruby Programming Language and Popular API Gems Activity API](https://apis.io/apis/ruby/ruby-activity-api/) — The Activity API from Ruby Programming Language and Popular API Gems — 2 operation(s) for activity.
- [Ruby Programming Language and Popular API Gems API Keys API](https://apis.io/apis/ruby/ruby-api-keys-api/) — The API Keys API from Ruby Programming Language and Popular API Gems — 1 operation(s) for api keys.
- [Ruby Programming Language and Popular API Gems Downloads API](https://apis.io/apis/ruby/ruby-downloads-api/) — The Downloads API from Ruby Programming Language and Popular API Gems — 2 operation(s) for downloads.
- [Ruby Programming Language and Popular API Gems API](https://apis.io/apis/ruby/ruby-gems-api/) — The Gems API from Ruby Programming Language and Popular API Gems — 4 operation(s) for gems.
- [Ruby Programming Language and Popular API Gems OIDC API](https://apis.io/apis/ruby/ruby-oidc-api/) — The OIDC API from Ruby Programming Language and Popular API Gems — 1 operation(s) for oidc.
- [Ruby Programming Language and Popular API Gems Owners API](https://apis.io/apis/ruby/ruby-owners-api/) — The Owners API from Ruby Programming Language and Popular API Gems — 1 operation(s) for owners.
- [Ruby Programming Language and Popular API Gems Profiles API](https://apis.io/apis/ruby/ruby-profiles-api/) — The Profiles API from Ruby Programming Language and Popular API Gems — 1 operation(s) for profiles.
- [Ruby Programming Language and Popular API Gems Versions API](https://apis.io/apis/ruby/ruby-versions-api/) — The Versions API from Ruby Programming Language and Popular API Gems — 3 operation(s) for versions.
- [Ruby Programming Language and Popular API Gems Webhooks API](https://apis.io/apis/ruby/ruby-webhooks-api/) — The Webhooks API from Ruby Programming Language and Popular API Gems — 4 operation(s) for webhooks.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ruby Agentic Access](https://apis.io/agentic-access/ruby/ruby-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Gem](https://apis.io/schemas/ruby/rubygems-registry-gem/)
- [Owner](https://apis.io/schemas/ruby/rubygems-registry-owner/)
- [Version](https://apis.io/schemas/ruby/rubygems-registry-version/)
- [WebHook](https://apis.io/schemas/ruby/rubygems-registry-webhook/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Rubygems Registry Gem Structure](https://apis.io/json-structure/ruby/rubygems-registry-gem-structure/)
- [Rubygems Registry Version Structure](https://apis.io/json-structure/ruby/rubygems-registry-version-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ruby Context](https://apis.io/jsonld/ruby/ruby-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Ruby Programming Language Vocabulary](https://apis.io/vocabularies/ruby/ruby-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Rubygems Registry Create Webhook Example](https://apis.io/examples/ruby/rubygems-registry-create-webhook-example/)
- [Rubygems Registry Get Gem Example](https://apis.io/examples/ruby/rubygems-registry-get-gem-example/)

#### Collections (10)

Postman and Open Collection request collections.

- [RubyGems.org Registry Activity API](https://apis.io/collections/ruby/open-ruby-activity-api/)
- [RubyGems.org Registry Activity API Keys API](https://apis.io/collections/ruby/open-ruby-api-keys-api/)
- [RubyGems.org Registry Activity Downloads API](https://apis.io/collections/ruby/open-ruby-downloads-api/)
- [RubyGems.org Registry Activity Gems API](https://apis.io/collections/ruby/open-ruby-gems-api/)
- [RubyGems.org Registry Activity OIDC API](https://apis.io/collections/ruby/open-ruby-oidc-api/)
- [RubyGems.org Registry Activity Owners API](https://apis.io/collections/ruby/open-ruby-owners-api/)
- [RubyGems.org Registry Activity Profiles API](https://apis.io/collections/ruby/open-ruby-profiles-api/)
- [RubyGems.org Registry Activity Versions API](https://apis.io/collections/ruby/open-ruby-versions-api/)
- [RubyGems.org Registry Activity Webhooks API](https://apis.io/collections/ruby/open-ruby-webhooks-api/)
- [RubyGems.org Registry API](https://apis.io/collections/ruby/open-rubygems-registry/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Ruby Programming Language and Popular API Gems — jsonschema rules](https://apis.io/rules/ruby/ruby-jsonschema-spectral-rules/)
- [Ruby Programming Language and Popular API Gems — rubygems registry rules](https://apis.io/rules/ruby/rubygems-registry-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ruby Authentication](https://apis.io/security/ruby/ruby-authentication/)
- [Ruby Domain Security](https://apis.io/security/ruby/ruby-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ruby-lang.org/)
- [Documentation](https://docs.ruby-lang.org/en/)
- [Getting started](https://www.ruby-lang.org/en/documentation/quickstart/)
- [Blog](https://www.ruby-lang.org/en/news/)
- [Security](https://www.ruby-lang.org/en/security/)
- [GitHub](https://github.com/ruby)
- [Status](https://status.rubygems.org/)

## API Evangelist rating

**Kin Score 40.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 66.2 |
| Contract governance | 27.3 |
| Operational transparency | 44.7 |
| Developer ergonomics | 52.4 |
| Access clarity | 0.0 |

**Agent readiness 19.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ruby/](https://apis.io/providers/ruby/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Ruby Programming Language and Popular API Gems: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ruby/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
