# dOrg November + December Services

| Funds Requested | Time Period | Actual Effort |
|-|-|-|
| $31,150 + ... `W3API` | Nov 1 - Dec 31, 2020 | 713.6 hrs |

## Summary

dOrg will provide the following services:
- Tech
    - pre-alpha
    - documentation
    - developer onboarding
    - partner tech syncs
    - weekly recorded tech syncs
- DAO Ops
    - [Token holder bookkeeping](../token-allocations/)
    - Launch partner outreach
    - Fundraising efforts
    - Onboarding new members of the DAO
    - Moderating DAO chat channels and github issues
    - Refining and creating new external-facing content

## Deliverables

NOTE: We'll be updating this deliverable log before each month's payout proposal.

### November

### Tech - 1 FTEs (154 hrs)
1. [Web3API JS Client Browser Support](https://github.com/Web3-API/prototype/issues/28)  
    * [Ongoing - ~90% Complete](https://github.com/Web3-API/prototype/commits/issue-28?since=2020-11-01&until=2020-12-01)
      * MsgPack Nullable Value Support
      * Schema Binding Support Custom Types
      * CLI Codegen Integration Started
      * Implement _w3_call flow
      * Client rewrite almost done, including new marshaling standard
2. [Web3API Manifest's Schema Tooling (Complete)](https://github.com/Web3-API/prototype/pull/50)  
    * [Reviews completed -> PR merged](https://github.com/Web3-API/prototype/pull/50).
3. [JavaScript Web3API (Complete)](https://github.com/Web3-API/prototype/issues/59)  
    * The concent of "Web3API Client Plugins" has been defined and implemented. These plugins are written in the client's host language (ex: Javascript), and can be exposed by redirecting Uri requests to the plugin's instance.
4. [Make WASM Interface Assemblyscript Agnostic (Complete)](https://github.com/Web3-API/prototype/issues/2)  
    * The schema parsing, composing, and binding pipeline has been built in such a way that Assemblyscript is just one of many supported WASM languages. In order to add support for a new WASM language, simply create new string templates for the generated code in the schema binding package.
5. [Sanitize GraphQL => WASM Function Signature Mappings (Complete)](https://github.com/Web3-API/prototype/issues/16)  
    * The generated code has been implemented in such a way that, if a function signature does not match, the Web3API will not compile. This takes care of GraphQL => WASM function signature sanitization for us.
6. [Cross Module Dependencies (~90% Complete)](https://github.com/Web3-API/prototype/issues/41)  
    * Schema Composer package supports the importing of external and local schema files.
    * Schema Binding package generates code to make calling into these external Web3APIs as easy as one function call.
    * Web3API's WASM interface has been updated to support querying external modules.
7. [Schema Imports (Complete)](https://github.com/Web3-API/prototype/issues/55)  
    * Schema Composer package supports the importing of external and local schema files.
8. [Two Way Data Type Marshalling Between Client & WASM (~90% Complete)](https://github.com/Web3-API/prototype/issues/27)  
    * Schema Parser Breakout
    * TypeInfo, W/ Visitor + Transforms
    * __w3_query & _w3_call standards set and partially implemented
9. [Web3API Schema Sanitization (~20% Complete)](https://github.com/Web3-API/prototype/issues/61)  
    * Initial sanitization happening through schema-parser & schema-composer.
    * A project for defining new sanitization rules still needs to be created.

### DAO Ops - 0.75 FTEs (112.6 hrs)

1. Bookkeeping ([done](https://github.com/Web3-API/dao/tree/master/token-allocations))
2. Launch partners ([Fleek, Abridged, Mantra DAO, Rockside, Torus, Pocket Network, Gnosis, dxDAO, Squad Games](https://web3api.dev/))
3. Fundraising ([$366K Raised](https://github.com/Web3-API/dao/blob/master/token-allocations/seed-funders.csv))
4. Improved DAO onboarding funnel (done)
    * mailer created
    * tracking of who's onboarded and who's not
6. Established and managed new comms channels:
    - Telegram Public Announcements Channel ([done](https://t.me/Web3API))
    - Telegram DAO Chat (done)
    - Keybase Builders Chat ([done](https://keybase.io/team/web3api))
    - Substack Newsletter ([done](https://web3api.substack.com/))
    - Twitter ([post 1](https://twitter.com/Web3API/status/1323709966096752647), [post 2](https://twitter.com/Web3API/status/1324148919849439233), [post 3](https://twitter.com/Web3API/status/1328173560565788676), [post 4](https://twitter.com/Web3API/status/1329444081102180353), [post 5](https://twitter.com/Web3API/status/1329462384130469889), [post 6](https://twitter.com/Web3API/status/1333011768365506569), [post 7](https://twitter.com/Web3API/status/1333498243347517442), [post 8](https://twitter.com/Web3API/status/1334329732633128960), [post 9](https://twitter.com/Web3API/status/1334493482031984643), [post 10](https://twitter.com/Web3API/status/1334528479057022977), [post 11](https://twitter.com/Web3API/status/1334926240466219008), [post 12](https://twitter.com/Web3API/status/1335969624190496771))
7. Standardized call schedule
    - Weekly DAO Ops call (done)
    - Weekly tech call (done)
    - Biweekly individual partner calls (awaiting pre-alpha)
8. Established deliverable tracking project board ([created](https://github.com/Web3-API/dao/projects/1))
9. Publish Introduction Article ([posted](https://web3api.substack.com/p/introducing-web3api-the-universal))
10. Publish Development Updates Article ([posted](https://web3api.substack.com/p/web3api-development-updates-december))
11. Published Web3API Problem / Solution Article (finished, posting soon)
12. Landing page changes ([partners + blurbs added](https://web3api.substack.com), more sections being specified now)

### December 

### Tech - 1.70 FTEs (167.25 hrs)

#### Pre-Alpha Release
1. [Ongoing - ~95% Complete](https://github.com/Web3-API/prototype/commits/prealpha-dev?since=2020-12-01&until=2020-12-31)  
    * [Web3API JS Client Browser Support (~95% Complete)](https://github.com/Web3-API/prototype/issues/28)  
    * [Cross Module Dependencies (~95% Complete)](https://github.com/Web3-API/prototype/issues/41)  
    * [Two Way Data Type Marshalling Between Client & WASM (~95% Complete)](https://github.com/Web3-API/prototype/issues/27)  
    * [Web3API Schema Sanitization (~30% Complete)](https://github.com/Web3-API/prototype/issues/61)  
1. Weekly update call for the above deliverables

### DAO Ops - 1.50 FTEs (279.75 hrs)

1. Bookkeeping ([done](https://github.com/Web3-API/dao/tree/master/token-allocations))
1. Launch partners ([WalletConnect, Aleph](https://web3api.dev))
1. Fundraising ([$1M Raised](https://github.com/Web3-API/dao/blob/master/token-allocations/seed-funders.csv))
1. Improved DAO onboarding funnel (done)
  * Builder Squads
  * Proposal Payment Guidelines
  * DAO Calendar
1. Established and managed comms channels:
    - Telegram Public Announcements Channel ([done](https://t.me/Web3API))
    - Telegram DAO Chat (done)
    - Keybase Builders Chat ([done](https://keybase.io/team/web3api))
    - Substack Newsletter ([done](https://web3api.substack.com/))
    - Twitter ([post 1](https://twitter.com/Web3API/status/1334329732633128960), [post 2](https://twitter.com/Web3API/status/1334493482031984643), [post 3](https://twitter.com/Web3API/status/1334528479057022977), [post 4](https://twitter.com/Web3API/status/1334926240466219008), [post 5](https://twitter.com/Web3API/status/1335228105494048768), [post 6](https://twitter.com/Web3API/status/1335969624190496771), [post 7](https://twitter.com/Web3API/status/1336450609378160641), [post 8](https://twitter.com/Web3API/status/1337750411453767681), [post 9](https://twitter.com/Web3API/status/1338526995106304005), [post 10](https://twitter.com/Web3API/status/1338551006771040257), [post 11](https://twitter.com/Web3API/status/1338855809049112577), [post 12](https://twitter.com/Web3API/status/1339193358162464769), [post 13](https://twitter.com/Web3API/status/1340354581600083969), [post 14](https://twitter.com/Web3API/status/1341413349444231172), [post 15](https://twitter.com/Web3API/status/1342477872053678081), [post 16](https://twitter.com/Web3API/status/1340279203183423488))
1. Standardized call schedule
    - Weekly DAO Ops call
    - Biweekly individual partner calls (awaiting pre-alpha)
1. Published Web3API Problem / Solution Article ([done](https://hackernoon.com/top-5-headaches-for-web3-developers-br1334u4))
1. Landing page changes ([done](http://web3api.dev/))

## Fund Distribution
All stable coins will be sent to the dOrg DAO @ 0x15344ecdc2c4edfcb092e284d93c20f0529fd8a6.

All `W3API` will be sent to individual builders:

**November:**
| Name | W3API | Address |
|-|-|-|
| [Jordan](https://github.com/dOrgJelli) | 33.00 | 0xB1B7586656116D546033e3bAFF69BFcD6592225E |  
| [Nestor](https://github.com/namesty) | 0.05 | 0x2e7f4dd3acd226ddae10246a45337f815cf6b3ff |  
| [Cesar](https://github.com/cbrzn) | 5.00 | 0x61ffe691821291d02e9ba5d33098adcee71a3a17 |  
| [Ori](https://github.com/orishim) | 4.38 | 0x639749b7b08aee65039c21d8a411103c6cebebf0 |  
| [Ingamar](https://twitter.com/Ingalandia) | 11.50 | 0x58b753f0c417494226af608b63e80028255cbc64 |  
| [Roberto](https://github.com/rihp) | 8.00 | 0x37341cbb14c5f128a70b149726ad8b2ce6f4c793 |  
| Bernie | 0.25 | 0xf6bd8c23142533661d67dc2c724e12c6f43f5b1c |  
| [Phil](https://github.com/PhilH) | 1.75 | 0xaa01dec5307cf17f20881a3286dcaa062578cea7 |  
| Alex | 2.28 | 0xa13Ee4362f171B5c62be230E5EB2fEe8C375b875 |  

**December:**
| Name | W3API | Address |
|-|-|-|
| ... | ... | ... |  

## About You
dOrg is a full stack Web3 development collective. It's been building in the Web3 space for almost 2 years now, working with some of Web3's top protocols: https://dorg.tech  

Jordan Ellis will be the point of contact for this roadmap:
- https://github.com/dOrgJelli  
- jelli@dorg.tech
- @dOrgJelli (Keybase, Telegram)