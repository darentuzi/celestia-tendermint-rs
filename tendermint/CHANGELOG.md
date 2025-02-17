# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.32.1](https://github.com/eigerco/celestia-tendermint-rs/compare/celestia-tendermint-v0.32.0...celestia-tendermint-v0.32.1) - 2024-01-15

### Other
- fully specify homepage url in metadata ([#27](https://github.com/eigerco/celestia-tendermint-rs/pull/27))
- align authors, repository and homepage keys ([#25](https://github.com/eigerco/celestia-tendermint-rs/pull/25))

## [0.32.0](https://github.com/eigerco/celestia-tendermint-rs/releases/tag/celestia-tendermint-v0.32.0) - 2024-01-12

This is the first release of the celestia-tendermint-rs, fork of tendermint-rs.

### Added
- allow deserialization of an empty hash ([#7](https://github.com/eigerco/celestia-tendermint-rs/pull/7))
- use protobuffers from celestia-core ([#1](https://github.com/eigerco/celestia-tendermint-rs/pull/1))

### Fixed
- Use `instant` only in wasm32 and with wasm-bindgen feature
- fix doc generation ([#2](https://github.com/eigerco/celestia-tendermint-rs/pull/2))

### Fixed - inherited
- fix deserialize power field in validator_update ([#451](https://github.com/informalsystems/tendermint-rs/pull/451))
- fix master again ([#159](https://github.com/informalsystems/tendermint-rs/pull/159))
- fix build on master 🔧💚 ([#157](https://github.com/informalsystems/tendermint-rs/pull/157))

### Other
- pre-release cleanups ([#16](https://github.com/eigerco/celestia-tendermint-rs/pull/16))
- Use instant to get time for wasm32 target ([#13](https://github.com/eigerco/celestia-tendermint-rs/pull/13))
- Revert "Use instant to get time for wasm32 target"
- Use instant to get time for wasm32 target
- update prost to 0.12.0
- remove unneded clones in proto encoding
- Remove unneeded allocations in serializers ([#6](https://github.com/eigerco/celestia-tendermint-rs/pull/6))
- Use Hash instead of Option<Hash> ([#4](https://github.com/eigerco/celestia-tendermint-rs/pull/4))

### Other - inherited
- Prepare release for v0.32.0 ([#1314](https://github.com/informalsystems/tendermint-rs/pull/1314))
- Loosen bounds on merkle hash arguments ([#1311](https://github.com/informalsystems/tendermint-rs/pull/1311))
- Attack detector and evidence reporting ([#1292](https://github.com/informalsystems/tendermint-rs/pull/1292))
- Prepare release v0.31.1 ([#1298](https://github.com/informalsystems/tendermint-rs/pull/1298))
- Expose the `TypedEvent` conversion trait ([#1296](https://github.com/informalsystems/tendermint-rs/pull/1296))
- Prepare v0.31.0 release ([#1295](https://github.com/informalsystems/tendermint-rs/pull/1295))
- Add a `TypedEvent` conversion trait for ABCI events. ([#1288](https://github.com/informalsystems/tendermint-rs/pull/1288))
- Bump `ed25519` to v2, `k256` to v0.13, `signature` to v2 ([#1285](https://github.com/informalsystems/tendermint-rs/pull/1285))
- Fix new Clippy warnings introduced in Rust 1.68 ([#1284](https://github.com/informalsystems/tendermint-rs/pull/1284))
- Release 0.30.0 ([#1282](https://github.com/informalsystems/tendermint-rs/pull/1282))
- Derive `Hash` on `tendermint::Time` again ([#1278](https://github.com/informalsystems/tendermint-rs/pull/1278))
- Fix typos ([#1266](https://github.com/informalsystems/tendermint-rs/pull/1266))
- Side-by-side support for Tendermint 0.34 and 0.37 ([#1193](https://github.com/informalsystems/tendermint-rs/pull/1193))
- Prepare `0.29.1` release of `tendermint` ([#1273](https://github.com/informalsystems/tendermint-rs/pull/1273))
- improve Debug impl for Ed25519 VerificationKeys ([#1272](https://github.com/informalsystems/tendermint-rs/pull/1272))
- `v0.29.0` ([#1267](https://github.com/informalsystems/tendermint-rs/pull/1267))
- Make crypto implementations replaceable ([#1238](https://github.com/informalsystems/tendermint-rs/pull/1238))
- Update all crates to Rust edition 2021 and fix clippy warnings introduced in Rust 1.67 ([#1261](https://github.com/informalsystems/tendermint-rs/pull/1261))
- Use ed25519-consensus instead of ed25519-dalek ([#1067](https://github.com/informalsystems/tendermint-rs/pull/1067)) ([#1245](https://github.com/informalsystems/tendermint-rs/pull/1245))
- fix minimal-versions correctness for `bytes` ([#1257](https://github.com/informalsystems/tendermint-rs/pull/1257))
- Fix lints that trigger clippy 0.1.66 ([#1253](https://github.com/informalsystems/tendermint-rs/pull/1253))
- Merge pull request from GHSA-xqqc-c5gw-c5r5
- Release v0.27.0 ([#1240](https://github.com/informalsystems/tendermint-rs/pull/1240))
- Remove async-trait from dependencies ([#1237](https://github.com/informalsystems/tendermint-rs/pull/1237))
- Decouple tendermint-rpc from tendermint-proto ([#1234](https://github.com/informalsystems/tendermint-rs/pull/1234))
- Change hashes' type from `Bytes` to `tendermint::Hash` or `tendermint::AppHash` ([#1232](https://github.com/informalsystems/tendermint-rs/pull/1232))
- Added `unix_timestamp` and `unix_timestamp_nanos` method in Time struct. ([#1176](https://github.com/informalsystems/tendermint-rs/pull/1176))
- Fix clippy lints for Rust 1.65 ([#1223](https://github.com/informalsystems/tendermint-rs/pull/1223))
- Replace RPC ABCI types with ABCI domain types ([#1204](https://github.com/informalsystems/tendermint-rs/pull/1204))
- Release v0.26.0 ([#1218](https://github.com/informalsystems/tendermint-rs/pull/1218))
- allow to be initialized with value 1 ([#1209](https://github.com/informalsystems/tendermint-rs/pull/1209))
- Fix unclosed HTML tags errors ([#1212](https://github.com/informalsystems/tendermint-rs/pull/1212))
- Rebase ABCI domain types onto main ([#1203](https://github.com/informalsystems/tendermint-rs/pull/1203))
- Release v0.25.0 ([#1202](https://github.com/informalsystems/tendermint-rs/pull/1202))
- Remove `ansi_term` dependency ([#1200](https://github.com/informalsystems/tendermint-rs/pull/1200))
- Unpin time dependency ([#1199](https://github.com/informalsystems/tendermint-rs/pull/1199))
- Fix deserialization of `DuplicateVoteEvidence` in `/block_results` response ([#1195](https://github.com/informalsystems/tendermint-rs/pull/1195))
- Update `master` references to `main` ([#1190](https://github.com/informalsystems/tendermint-rs/pull/1190))
- Derive Eq to appease clippy ([#1191](https://github.com/informalsystems/tendermint-rs/pull/1191))
- Initialize the `main` branch ([#1172](https://github.com/informalsystems/tendermint-rs/pull/1172))
- Release v0.23.8 ([#1162](https://github.com/informalsystems/tendermint-rs/pull/1162))
- Update `k256` to v0.11 (fixes [#1153](https://github.com/informalsystems/tendermint-rs/pull/1153)) on v0.23.x ([#1154](https://github.com/informalsystems/tendermint-rs/pull/1154))
- Release v0.23.8-pre.1 ([#1151](https://github.com/informalsystems/tendermint-rs/pull/1151))
- Release v0.23.7 ([#1122](https://github.com/informalsystems/tendermint-rs/pull/1122))
- Fix clippy warning ([#1123](https://github.com/informalsystems/tendermint-rs/pull/1123))
- [v0.23.x] Update `prost` to v0.10 ([#1114](https://github.com/informalsystems/tendermint-rs/pull/1114))
- Release v0.23.6 ([#1111](https://github.com/informalsystems/tendermint-rs/pull/1111))
- Generic `AppState` for `genesis()` ([#1107](https://github.com/informalsystems/tendermint-rs/pull/1107))
- Fix clippy warnings from Rust v1.59.0 ([#1097](https://github.com/informalsystems/tendermint-rs/pull/1097)) ([#1103](https://github.com/informalsystems/tendermint-rs/pull/1103))
- Release v0.23.5 ([#1079](https://github.com/informalsystems/tendermint-rs/pull/1079))
- Split out verifier parts of tendermint-light-client to tendermint-light-client-verifier (Backported to v0.23) ([#1072](https://github.com/informalsystems/tendermint-rs/pull/1072))
- Release v0.23.4 ([#1073](https://github.com/informalsystems/tendermint-rs/pull/1073))
- Release v0.23.3 ([#1066](https://github.com/informalsystems/tendermint-rs/pull/1066))
- Add temporary fix and tests for `block_results` serialization ([#1061](https://github.com/informalsystems/tendermint-rs/pull/1061))
- Bump `k256` to v0.10 ([#1059](https://github.com/informalsystems/tendermint-rs/pull/1059)) ([#1060](https://github.com/informalsystems/tendermint-rs/pull/1060))
- Derive `Hash` on `tendermint::Time` ([#1054](https://github.com/informalsystems/tendermint-rs/pull/1054)) ([#1055](https://github.com/informalsystems/tendermint-rs/pull/1055))
- Remove unnecessary cdylib artifacts from the build ([#1052](https://github.com/informalsystems/tendermint-rs/pull/1052)) ([#1056](https://github.com/informalsystems/tendermint-rs/pull/1056))
- Release v0.23.2 ([#1043](https://github.com/informalsystems/tendermint-rs/pull/1043))
- Expunge more uses of time >0.3.2 API ([#1050](https://github.com/informalsystems/tendermint-rs/pull/1050))
- Roll back time-rs dependency and remove methods that require version 0.3.5 ([#1048](https://github.com/informalsystems/tendermint-rs/pull/1048))
- Replace chrono with time 0.3 (backport to 0.23.x) ([#1036](https://github.com/informalsystems/tendermint-rs/pull/1036))
- Fix clippy 0.1.57 lints (backport to 0.23.x) ([#1042](https://github.com/informalsystems/tendermint-rs/pull/1042))
- Update to deprecations in ed25519 1.3 (backport to 0.23.x) ([#1031](https://github.com/informalsystems/tendermint-rs/pull/1031))
- Release v0.23.1 ([#1019](https://github.com/informalsystems/tendermint-rs/pull/1019))
- lowercase hex node ID ([#1016](https://github.com/informalsystems/tendermint-rs/pull/1016))
- Release v0.23.0 ([#1013](https://github.com/informalsystems/tendermint-rs/pull/1013))
- Use `core` and `alloc` crates for `no_std` compatibility (Take 2) ([#993](https://github.com/informalsystems/tendermint-rs/pull/993))
- Update to official Prost v0.9 ([#1011](https://github.com/informalsystems/tendermint-rs/pull/1011))
- Bump version to 0.23.0-internal ([#1009](https://github.com/informalsystems/tendermint-rs/pull/1009))
- Move out `tendermint::config` to `tendermint-config` crate ([#986](https://github.com/informalsystems/tendermint-rs/pull/986))
- Adopt forked prost crates ([#1005](https://github.com/informalsystems/tendermint-rs/pull/1005))
- Use chrono::DateTime instead of std::time::SystemTime ([#994](https://github.com/informalsystems/tendermint-rs/pull/994))
- Release v0.22.0 ([#987](https://github.com/informalsystems/tendermint-rs/pull/987))
- Refactor Light Client verification predicates interface for use from IBC ([#960](https://github.com/informalsystems/tendermint-rs/pull/960))
- Derive `PartialEq` and `Eq` on more types ([#970](https://github.com/informalsystems/tendermint-rs/pull/970))
- Add support for Secp256k1 signatures ([#962](https://github.com/informalsystems/tendermint-rs/pull/962))
- Change `hash` parameter of `/tx` RPC endpoint encoding to base64 ([#948](https://github.com/informalsystems/tendermint-rs/pull/948))
- Use flex-error for tendermint-rs errors ([#923](https://github.com/informalsystems/tendermint-rs/pull/923))
- Fix recent clippy errors on `master` ([#941](https://github.com/informalsystems/tendermint-rs/pull/941))
- Release v0.21.0 ([#935](https://github.com/informalsystems/tendermint-rs/pull/935))
- Ensure correct `TrustThresholdFraction` construction ([#934](https://github.com/informalsystems/tendermint-rs/pull/934))
- Specify default value for `tendermint::block::Size` ([#931](https://github.com/informalsystems/tendermint-rs/pull/931))
- Temporarily revert [#926](https://github.com/informalsystems/tendermint-rs/pull/926) ([#928](https://github.com/informalsystems/tendermint-rs/pull/928))
- Deduplicate RPC domain types ([#922](https://github.com/informalsystems/tendermint-rs/pull/922))
- Update `prost` and `prost-types` to version 0.8 ([#926](https://github.com/informalsystems/tendermint-rs/pull/926))
- update Tendermint genesis ([#917](https://github.com/informalsystems/tendermint-rs/pull/917))
- Release v0.20.0 ([#912](https://github.com/informalsystems/tendermint-rs/pull/912))
- Fix latest clippy assertion failures ([#910](https://github.com/informalsystems/tendermint-rs/pull/910))
- Tendermint config handle optional values + fix `net::Address` Display ([#908](https://github.com/informalsystems/tendermint-rs/pull/908))
- Add TryFrom for node::Id from PublicKey ([#903](https://github.com/informalsystems/tendermint-rs/pull/903))
- use k256::ecdsa::VerifyingKey as Secp256k1 key ([#900](https://github.com/informalsystems/tendermint-rs/pull/900))
- update tendermint config ([#897](https://github.com/informalsystems/tendermint-rs/pull/897))
- Bump `k256` crate dependency to v0.9; MSRV 1.51+ ([#894](https://github.com/informalsystems/tendermint-rs/pull/894))
- Update [#877](https://github.com/informalsystems/tendermint-rs/pull/877) with latest changes from master ([#882](https://github.com/informalsystems/tendermint-rs/pull/882))
- Bump `k256` crate dependency to v0.8 ([#872](https://github.com/informalsystems/tendermint-rs/pull/872))
- Release v0.19.0 ([#854](https://github.com/informalsystems/tendermint-rs/pull/854))
- Add IPv6 support for net::Address ([#827](https://github.com/informalsystems/tendermint-rs/pull/827))
- Fix clippy errors/warnings when upgrading to Rust 1.51 ([#839](https://github.com/informalsystems/tendermint-rs/pull/839))
- Move time proptest generators into their own crate ([#829](https://github.com/informalsystems/tendermint-rs/pull/829))
- Add tendermint-light-client-js crate ([#812](https://github.com/informalsystems/tendermint-rs/pull/812))
- Property based tests of Time ([#815](https://github.com/informalsystems/tendermint-rs/pull/815))
- Temporarily patch funty dependency to fix build ([#817](https://github.com/informalsystems/tendermint-rs/pull/817))
- Release v0.18.1 ([#808](https://github.com/informalsystems/tendermint-rs/pull/808))
- Fix rendering of documentation on docs.rs ([#807](https://github.com/informalsystems/tendermint-rs/pull/807))
- Upgrade jsonrpc to upgrade hyper ([#804](https://github.com/informalsystems/tendermint-rs/pull/804))
- Release v0.18.0 ([#796](https://github.com/informalsystems/tendermint-rs/pull/796))
- Update Tokio to 1.0, Hyper to 0.14, Prost to 0.7 and Bytes to 1.0 ([#783](https://github.com/informalsystems/tendermint-rs/pull/783))
- Release v0.17.1 ([#778](https://github.com/informalsystems/tendermint-rs/pull/778))
- Fix formatting of tendermint::Time ([#775](https://github.com/informalsystems/tendermint-rs/pull/775))
- Fix new Clippy warnings as of Rust 1.49 ([#766](https://github.com/informalsystems/tendermint-rs/pull/766))
- rpc-probe fixes and kvstore-fixtures and tests ([#758](https://github.com/informalsystems/tendermint-rs/pull/758))
- kvstore test with cargo-make invoking docker ([#748](https://github.com/informalsystems/tendermint-rs/pull/748))
- Release v0.17.0 ([#751](https://github.com/informalsystems/tendermint-rs/pull/751))
- Bump `k256` crate dependency to v0.7 ([#752](https://github.com/informalsystems/tendermint-rs/pull/752))
- Add support for consensus_state endpoint ([#719](https://github.com/informalsystems/tendermint-rs/pull/719))
- Remove `total_voting_power` parameter from `validator::Set::new` ([#740](https://github.com/informalsystems/tendermint-rs/pull/740))
- Final protobuf for 0.17.0 / Go 0.34.0 ([#737](https://github.com/informalsystems/tendermint-rs/pull/737))
- Specify proposer when constructing validator set in light client ([#706](https://github.com/informalsystems/tendermint-rs/pull/706))
- Bump `k256` crate dependency to v0.6 ([#724](https://github.com/informalsystems/tendermint-rs/pull/724))
- Automatically de/serialize ABCI event attributes from/to base64 ([#718](https://github.com/informalsystems/tendermint-rs/pull/718))
- Add tx_search endpoint for RPC client ([#701](https://github.com/informalsystems/tendermint-rs/pull/701))
- Bech32 compatibility fix ([#704](https://github.com/informalsystems/tendermint-rs/pull/704))
- Upgrade WebSocketClient to support full client functionality ([#646](https://github.com/informalsystems/tendermint-rs/pull/646))
- Downgrade back to Tokio 0.2 ([#700](https://github.com/informalsystems/tendermint-rs/pull/700))
- Upgrade Tokio to version 0.3.0 ([#681](https://github.com/informalsystems/tendermint-rs/pull/681))
- Release v0.17.0-rc3 ([#684](https://github.com/informalsystems/tendermint-rs/pull/684))
- :State deserialization fixes ([#680](https://github.com/informalsystems/tendermint-rs/pull/680))
- Rename DomainType trait to Protobuf ([#672](https://github.com/informalsystems/tendermint-rs/pull/672))
- State struct JSON serialization ([#676](https://github.com/informalsystems/tendermint-rs/pull/676))
- :Data serialization fix ([#670](https://github.com/informalsystems/tendermint-rs/pull/670))
- Release v0.17.0-rc2 ([#668](https://github.com/informalsystems/tendermint-rs/pull/668))
- CanonicalVote and CanonicalProposal now correctly encode/decode BlockId ([#664](https://github.com/informalsystems/tendermint-rs/pull/664))
- rfc3339 direct ser/deser fix for protobuf Timestamp ([#666](https://github.com/informalsystems/tendermint-rs/pull/666))
- Re-built tendermint-proto with serialization annotations ([#639](https://github.com/informalsystems/tendermint-rs/pull/639))
- Renaming "parts" to "part_set_header" ([#648](https://github.com/informalsystems/tendermint-rs/pull/648))
- Release v0.17.0 ([#624](https://github.com/informalsystems/tendermint-rs/pull/624))
- Added empty option to signature ([#635](https://github.com/informalsystems/tendermint-rs/pull/635))
- Enable RPC integration tests in a new job on CI ([#607](https://github.com/informalsystems/tendermint-rs/pull/607))
- Refactor WebSocketClient interface to expose driver ([#617](https://github.com/informalsystems/tendermint-rs/pull/617))
- Round struct From trait ([#630](https://github.com/informalsystems/tendermint-rs/pull/630))
- Height conversion support for u32,u16,u8 ([#629](https://github.com/informalsystems/tendermint-rs/pull/629))
- Removed amino folder ([#592](https://github.com/informalsystems/tendermint-rs/pull/592))
- Use u64 default instead of providing an explicit default ([#623](https://github.com/informalsystems/tendermint-rs/pull/623))
- Supply default value for app version if field is missing in JSON ([#622](https://github.com/informalsystems/tendermint-rs/pull/622))
- Add structured querying for event subscriptions ([#584](https://github.com/informalsystems/tendermint-rs/pull/584))
- improve fmt::UpperHex impl on Transaction ([#613](https://github.com/informalsystems/tendermint-rs/pull/613))
- Add integration test showing management of concurrent subscriptions ([#614](https://github.com/informalsystems/tendermint-rs/pull/614))
- impl fmt::UpperHex for abci::Transaction ([#610](https://github.com/informalsystems/tendermint-rs/pull/610))
- remove `tai64` crate ([#603](https://github.com/informalsystems/tendermint-rs/pull/603))
- Remove public key field from DuplicateVoteEvidence ([#589](https://github.com/informalsystems/tendermint-rs/pull/589))
- Add integration test for catching empty merkle root bug ([#588](https://github.com/informalsystems/tendermint-rs/pull/588))
- Fix validator sorting according to v.0.34 requirements ([#580](https://github.com/informalsystems/tendermint-rs/pull/580))
- Bump `k256` crate to v0.5 ([#578](https://github.com/informalsystems/tendermint-rs/pull/578))
- Fix and test WebSocket Tx event subscription ([#572](https://github.com/informalsystems/tendermint-rs/pull/572))
- Blanket implementation for DomainType ([#571](https://github.com/informalsystems/tendermint-rs/pull/571))
- Simplify client interface ([#569](https://github.com/informalsystems/tendermint-rs/pull/569))
- Rename WebSocketSubscriptionClient ([#566](https://github.com/informalsystems/tendermint-rs/pull/566))
- event subscription management for RPC client ([#516](https://github.com/informalsystems/tendermint-rs/pull/516))
- order validators by voting power ([#565](https://github.com/informalsystems/tendermint-rs/pull/565))
- Tendermint JSON test case fixes ([#563](https://github.com/informalsystems/tendermint-rs/pull/563))
- Replace amino with protobuf types ([#527](https://github.com/informalsystems/tendermint-rs/pull/527))
- Compile the `tendermint` and `light-client` crates to WASM ([#553](https://github.com/informalsystems/tendermint-rs/pull/553))
- Empty Merkle tree hash fix ([#557](https://github.com/informalsystems/tendermint-rs/pull/557))
- Run Clippy on all targets (standard, tests, examples and benchmarks) ([#554](https://github.com/informalsystems/tendermint-rs/pull/554))
- CHANGELOG for v0.16, lib version updates ([#543](https://github.com/informalsystems/tendermint-rs/pull/543))
- Add higher resolution images (thanks Jelena) ([#513](https://github.com/informalsystems/tendermint-rs/pull/513))
- Bump `ed25519-dalek` dependency to v1.0 release ([#532](https://github.com/informalsystems/tendermint-rs/pull/532))
- Revert empty Merkle tree hashing for v0.15 release ([#541](https://github.com/informalsystems/tendermint-rs/pull/541))
- Replace `signatory` with `ed25519-dalek` and `k256` crates ([#522](https://github.com/informalsystems/tendermint-rs/pull/522))
- return rfc6962 hash for empty merkle tree ([#514](https://github.com/informalsystems/tendermint-rs/pull/514))
- Consolidate and delete old implementation of the light client ([#500](https://github.com/informalsystems/tendermint-rs/pull/500))
- replace broken links ([#495](https://github.com/informalsystems/tendermint-rs/pull/495))
- Adds more verification tests ([#475](https://github.com/informalsystems/tendermint-rs/pull/475))
- Generator of Tendermint types for unit, integration, and model-based testing ([#468](https://github.com/informalsystems/tendermint-rs/pull/468))
- Cleanup and standardize the READMEs ([#482](https://github.com/informalsystems/tendermint-rs/pull/482))
- Prep release v0.15.0 ([#454](https://github.com/informalsystems/tendermint-rs/pull/454))
- add new fancy logo :tada: ([#447](https://github.com/informalsystems/tendermint-rs/pull/447))
- make dependency secp256k1 optional, fix [#391](https://github.com/informalsystems/tendermint-rs/pull/391) ([#441](https://github.com/informalsystems/tendermint-rs/pull/441))
- Fix header.hash for height 1 ([#438](https://github.com/informalsystems/tendermint-rs/pull/438))
- Fix rpc response deserialization ([#432](https://github.com/informalsystems/tendermint-rs/pull/432))
- Multi-peer conformance tests ([#371](https://github.com/informalsystems/tendermint-rs/pull/371))
- close [#409](https://github.com/informalsystems/tendermint-rs/pull/409): sort validators by address on deserialization ([#410](https://github.com/informalsystems/tendermint-rs/pull/410))
- Add unit tests for voting power calculator ([#383](https://github.com/informalsystems/tendermint-rs/pull/383))
- Conformance test fixes ([#366](https://github.com/informalsystems/tendermint-rs/pull/366))
- tendermint v0.14.1 ([#368](https://github.com/informalsystems/tendermint-rs/pull/368))
- Update `prost-amino`/`prost-amino-derive` to v0.6 ([#367](https://github.com/informalsystems/tendermint-rs/pull/367))
- do not explicitly version dev-dependency ([#353](https://github.com/informalsystems/tendermint-rs/pull/353))
- Light Client: Evidence reporting ([#336](https://github.com/informalsystems/tendermint-rs/pull/336))
- Prep v0.14.0 release ([#347](https://github.com/informalsystems/tendermint-rs/pull/347))
- Fix `VotingPowerCalculator::voting_power_in` ([#306](https://github.com/informalsystems/tendermint-rs/pull/306))
- add `cryptography::cryptocurrencies` category ([#345](https://github.com/informalsystems/tendermint-rs/pull/345))
- guard client with feature flag ([#343](https://github.com/informalsystems/tendermint-rs/pull/343))
- move `net2` dependency out of tendermint crate ([#338](https://github.com/informalsystems/tendermint-rs/pull/338))
- Update signatory to v0.20 ([#322](https://github.com/informalsystems/tendermint-rs/pull/322))
- [light-client] Supervisor ([#302](https://github.com/informalsystems/tendermint-rs/pull/302))
- Add integration test pinned to tendermint-go v0.33.5 ([#324](https://github.com/informalsystems/tendermint-rs/pull/324))
- add Clone to EventSubscription ([#315](https://github.com/informalsystems/tendermint-rs/pull/315))
- make fields in event subscription accessible publicly ([#312](https://github.com/informalsystems/tendermint-rs/pull/312))
- Light Client: Follow-up ([#284](https://github.com/informalsystems/tendermint-rs/pull/284))
- Add tests for jsonrpc id ([#298](https://github.com/informalsystems/tendermint-rs/pull/298))
- Fix null data in TxResult deserialization ([#299](https://github.com/informalsystems/tendermint-rs/pull/299))
- Move proof.rs to merkle module ([#297](https://github.com/informalsystems/tendermint-rs/pull/297))
- light tests: remove assertions about number of bisections ([#295](https://github.com/informalsystems/tendermint-rs/pull/295))
- 0.33 compat followup ([#296](https://github.com/informalsystems/tendermint-rs/pull/296))
- Make serialization of CommitSig, TrustedState symmetric ([#288](https://github.com/informalsystems/tendermint-rs/pull/288))
- Fix block_id of nil vote ([#236](https://github.com/informalsystems/tendermint-rs/pull/236))
- Light Client refactoring ([#237](https://github.com/informalsystems/tendermint-rs/pull/237))
- Symmetric assertions to unit tests ([#283](https://github.com/informalsystems/tendermint-rs/pull/283))
- CommitSig refactor ([#277](https://github.com/informalsystems/tendermint-rs/pull/277))
- Simplify event subscription ([#279](https://github.com/informalsystems/tendermint-rs/pull/279))
- Add subscriptions support ([#225](https://github.com/informalsystems/tendermint-rs/pull/225))
- Full JSON test structure changes ([#273](https://github.com/informalsystems/tendermint-rs/pull/273))
- Locked down serialization library to local crate only ([#274](https://github.com/informalsystems/tendermint-rs/pull/274))
- Broke up serializers.rs into its own folder ([#272](https://github.com/informalsystems/tendermint-rs/pull/272))
- Serialization refactor step 2 ([#269](https://github.com/informalsystems/tendermint-rs/pull/269))
- Serialization refactor step 1 ([#255](https://github.com/informalsystems/tendermint-rs/pull/255))
- Update abci_info test to 0.17.0 ([#256](https://github.com/informalsystems/tendermint-rs/pull/256))
- bump abci version in integration tests ([#238](https://github.com/informalsystems/tendermint-rs/pull/238))
- Fix [#241](https://github.com/informalsystems/tendermint-rs/pull/241) evidence JSON format ([#242](https://github.com/informalsystems/tendermint-rs/pull/242))
- Fix CI badges, update minimum Rust version, update logo in docs ([#234](https://github.com/informalsystems/tendermint-rs/pull/234))
- Tendermint/v0.33 ([#196](https://github.com/informalsystems/tendermint-rs/pull/196))
- Release/v0.13.0 ([#228](https://github.com/informalsystems/tendermint-rs/pull/228))
- Update `signatory` requirement to v0.19 ([#227](https://github.com/informalsystems/tendermint-rs/pull/227))
- Update secp address hash ([#213](https://github.com/informalsystems/tendermint-rs/pull/213))
- Updated versions to 0.13.0-dev and CHANGELOG
- Bump version ([#222](https://github.com/informalsystems/tendermint-rs/pull/222))
- JSON ID specification compatible ([#202](https://github.com/informalsystems/tendermint-rs/pull/202))
- make tests sync instead of async where no async function is used ([#195](https://github.com/informalsystems/tendermint-rs/pull/195))
- Require that light client datatypes be serializable ([#191](https://github.com/informalsystems/tendermint-rs/pull/191))
- Add matching serializer for `app_hash` field of `block::Header` struct ([#188](https://github.com/informalsystems/tendermint-rs/pull/188))
- Enable integration tests + GitHub Actions Service for Tendermint node ([#183](https://github.com/informalsystems/tendermint-rs/pull/183))
- Abscissify light node ([#125](https://github.com/informalsystems/tendermint-rs/pull/125))
- Make TrustedState::new take ownership of its arguments ([#178](https://github.com/informalsystems/tendermint-rs/pull/178))
- Export publicly more functions from lite::verifier ([#176](https://github.com/informalsystems/tendermint-rs/pull/176))
- Update integration tests to async tokio::test ([#173](https://github.com/informalsystems/tendermint-rs/pull/173))
- Turn `lite::types::Requester` into an async trait ([#171](https://github.com/informalsystems/tendermint-rs/pull/171))
- Turn `rpc::Client::new` into a sync fn by not performing the health check on creation ([#169](https://github.com/informalsystems/tendermint-rs/pull/169))
- Shivani/detect faulty vals ([#163](https://github.com/informalsystems/tendermint-rs/pull/163))
- remove usage of deprecated method ([#166](https://github.com/informalsystems/tendermint-rs/pull/166))
- Make TrustedState serializable, Fix [#161](https://github.com/informalsystems/tendermint-rs/pull/161) ([#164](https://github.com/informalsystems/tendermint-rs/pull/164))
- Follow up on 142 ([#162](https://github.com/informalsystems/tendermint-rs/pull/162))
- Valid TrustThresholdFraction and further simplify tests code ([#142](https://github.com/informalsystems/tendermint-rs/pull/142))
- Refactor errors  ([#158](https://github.com/informalsystems/tendermint-rs/pull/158))
- Followup on 149 and 151 ([#155](https://github.com/informalsystems/tendermint-rs/pull/155))
- JSON bisection tests ([#146](https://github.com/informalsystems/tendermint-rs/pull/146))
- Light errors: Remove `InvalidSignature` and `InvalidCommitSignatures`  ([#151](https://github.com/informalsystems/tendermint-rs/pull/151))
- more data in errors ([#149](https://github.com/informalsystems/tendermint-rs/pull/149))
- adr-002 lite client ([#54](https://github.com/informalsystems/tendermint-rs/pull/54))
- Added single-step-skipping JSON tests ([#143](https://github.com/informalsystems/tendermint-rs/pull/143))
- 132 followup ([#141](https://github.com/informalsystems/tendermint-rs/pull/141))
- Simplify some light client types and testing ([#132](https://github.com/informalsystems/tendermint-rs/pull/132))
- Move Amino type prefixes over from KMS ([#131](https://github.com/informalsystems/tendermint-rs/pull/131))
- Release/v0.12.0-rc0 ([#130](https://github.com/informalsystems/tendermint-rs/pull/130))
- Update to `signatory` v0.18 ([#129](https://github.com/informalsystems/tendermint-rs/pull/129))
- Remove `extern crate` directives ([#128](https://github.com/informalsystems/tendermint-rs/pull/128))
- remove unused extern crates ([#127](https://github.com/informalsystems/tendermint-rs/pull/127))
- Update to bytes 0.5 and amino_rs 0.5 ([#126](https://github.com/informalsystems/tendermint-rs/pull/126))
- block id in vote could be empty ([#103](https://github.com/informalsystems/tendermint-rs/pull/103))
- Refactor lite impls into their own module within tendermint  ([#124](https://github.com/informalsystems/tendermint-rs/pull/124))
- impl Requester, Store, and a basic syncing daemon ([#116](https://github.com/informalsystems/tendermint-rs/pull/116))
- Setup rustfmt config ([#121](https://github.com/informalsystems/tendermint-rs/pull/121))
- New public API for the light client ([#114](https://github.com/informalsystems/tendermint-rs/pull/114))
- Light client: bisection, store, requester ([#100](https://github.com/informalsystems/tendermint-rs/pull/100))
- Light client: further trait impls, improvements, and tests ([#84](https://github.com/informalsystems/tendermint-rs/pull/84))
- fix README path ([#94](https://github.com/informalsystems/tendermint-rs/pull/94))
- Release/v0.11.0 ([#92](https://github.com/informalsystems/tendermint-rs/pull/92))
- Upgrade to `uuid` v0.8 ([#91](https://github.com/informalsystems/tendermint-rs/pull/91))
- Replace `rand_os` with `getrandom` ([#90](https://github.com/informalsystems/tendermint-rs/pull/90))
- *(deps)* update subtle-encoding requirement from 0.3 to 0.5 ([#47](https://github.com/informalsystems/tendermint-rs/pull/47))
- Upgrade to `signatory` v0.17 ([#89](https://github.com/informalsystems/tendermint-rs/pull/89))
- Upgrade to hyper v0.13; use async/await ([#85](https://github.com/informalsystems/tendermint-rs/pull/85))
- Change type of ``max_gas`` to i64, and remove two clones. ([#61](https://github.com/informalsystems/tendermint-rs/pull/61))
- Fix master: ed25519-dalek dep, adapt to renaming (simple_merkle hickup), and fmt: ([#83](https://github.com/informalsystems/tendermint-rs/pull/83))
- Light client: trait impls ([#36](https://github.com/informalsystems/tendermint-rs/pull/36))
- Made Height field public
- Simplify conversion into Path
- Implement TryFrom<i64> for Height
- Use base64 serializer/deserializer for abci_query response key and value
- Added serializers for base64 bytes and optional base64 bytes
- Use subtle-encoding instead of hex crate
- Made RPC integration test target a local throwaway network node
- Allow block heights of 0
- Added integration test for RPC abci_query
- Optionized 'key' and 'value' fields in abci_query RPC response
- Use hex string serializer/deserializer for data field in abci_query RPC request
- Added hex string (de)serializer
- Upgrade to `zeroize` v1.0 ([#74](https://github.com/informalsystems/tendermint-rs/pull/74))
- Parse validators field in genesis api ([#65](https://github.com/informalsystems/tendermint-rs/pull/65))
- Fix clippy errors on master ([#81](https://github.com/informalsystems/tendermint-rs/pull/81))
- MVP Generic Sequential & Skipping Lite Client Verifiers ([#31](https://github.com/informalsystems/tendermint-rs/pull/31))
- Merge pull request [#64](https://github.com/informalsystems/tendermint-rs/pull/64) from yihuang/implement-default-traits
- implement utility traits for tendermint data types
- *(deps)* update tai64 requirement from 2 to 3 ([#22](https://github.com/informalsystems/tendermint-rs/pull/22))
- Address clippy warnings ([#55](https://github.com/informalsystems/tendermint-rs/pull/55))
- SignedHeader should contain commit ([#42](https://github.com/informalsystems/tendermint-rs/pull/42))
- Update Readme, add LICENSE, add clippy and fix lints ([#40](https://github.com/informalsystems/tendermint-rs/pull/40))
- Allow lower case for abci::data ([#17](https://github.com/informalsystems/tendermint-rs/pull/17))
- cargo workspace with tendermint crate ([#30](https://github.com/informalsystems/tendermint-rs/pull/30))
