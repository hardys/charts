🚨 This is a RELEASE CANDIDATE. Use it only for testing purposes. If you find any bugs, file an [issue](https://github.com/rancher/turtles/issues/new).
<details>
<summary>More details about the release</summary>

:warning: **RELEASE CANDIDATE NOTES** :warning:
## Highlights

* REPLACE ME

## Deprecation Warning

REPLACE ME: A couple sentences describing the deprecation, including links to docs.

* [GitHub issue #REPLACE ME](REPLACE ME)

## Changes since v0.23.0
## :chart_with_upwards_trend: Overview
- 31 new commits merged
- 1 breaking change :warning:

## :warning: Breaking Changes
- Dependency: Bump Core and Infra Providers to newer versions (#1669)

## :seedling: Others
- Testing: Verify that workload cluster remains operational post-upgrade (#1638)

## :question: Sort these by hand
- Build-and-release: Build separate Prime/Community versions (#1644)
- Build-and-release: Chore(deps): Bump actions/setup-go from 5.5.0 to 6.0.0 (#1688)
- Build-and-release: Chore(deps): Bump actions/setup-python from 5 to 6 (#1689)
- Build-and-release: Chore(deps): Bump aquasecurity/trivy-action from 0.32.0 to 0.33.1 (#1687)
- Chart: Add upper bound for rancher-version annotation (#1670)
- CI: Clarify SOURCE_REPO and GITHUB_HEAD_REF on short e2e tests (#1661)
- CI: Fix late checkout in dependabot workflow (#1666)
- CI: Fix nightly chart build (#1671)
- CI: Fix release notes generation (#1662)
- CI: Rename config.yaml to config-default.yaml (#1682)
- CI: Update test dependencies (#1667)
- CI: Use go.mod to setup go version in workflows (#1653)
- Dependency: Bump Rancher to latest v2.12.1 patch version (#1665)
- Dependency: Bump Rancher to v2.12.1-alpha1 (#1589)
- Dependency: Chore(deps): Bump github.com/go-viper/mapstructure/v2 from 2.3.0 to 2.4.0 (#1639)
- Dependency: Chore(deps): Bump github.com/onsi/ginkgo/v2 from 2.25.2 to 2.25.3 in /exp/day2 in the testing-dependencies group (#1695)
- Dependency: Chore(deps): Bump github.com/rancher/cluster-api-provider-rke2 from 0.19.0 to 0.20.1 in /exp/day2 in the provider-dependencies group (#1696)
- Dependency: Chore(deps): Bump github.com/spf13/pflag from 1.0.7 to 1.0.10 in /examples in the other-dependencies group (#1698)
- Dependency: Chore(deps): Bump github.com/spf13/pflag from 1.0.7 to 1.0.10 in /exp/day2 in the other-dependencies group (#1697)
- Dependency: Chore(deps): Bump sigs.k8s.io/cluster-api-operator from 0.22.0 to 0.23.0 in the other-dependencies group (#1648)
- Dependency: Chore(deps): Bump the testing-dependencies group in /exp/clusterclass with 2 updates (#1651)
- Dependency: Chore(deps): Bump the testing-dependencies group in /exp/clusterclass with 2 updates (#1694)
- Dependency: Chore(deps): Bump the testing-dependencies group in /test with 2 updates (#1647)
- Dependency: Chore(deps): Bump the testing-dependencies group with 2 updates (#1646)
- Installation: ADR 0016: CAPI version pinning strategy (#1652)
- Installation: Providers helm chart improvements (#1680)
- MULTIPLE_AREAS[Installation/Ux]: Add provider helm chart migration script (#1681)
- Operator: Feat: let wrangler manage certs (#1570)
- Testing: Cleanup test framework (#1676)

## Dependencies

### Added
_Nothing has changed._

### Changed
- github.com/Masterminds/semver/v3: [v3.3.0 → v3.4.0](https://github.com/Masterminds/semver/compare/v3.3.0...v3.4.0)
- github.com/coredns/corefile-migration: [v1.0.26 → v1.0.27](https://github.com/coredns/corefile-migration/compare/v1.0.26...v1.0.27)
- github.com/go-viper/mapstructure/v2: [v2.3.0 → v2.4.0](https://github.com/go-viper/mapstructure/compare/v2.3.0...v2.4.0)
- github.com/google/pprof: [27863c8 → f64d9cf](https://github.com/google/pprof/compare/27863c8...f64d9cf)
- github.com/ianlancetaylor/demangle: [bd984b5 → f615e6b](https://github.com/ianlancetaylor/demangle/compare/bd984b5...f615e6b)
- github.com/onsi/ginkgo/v2: [v2.23.4 → v2.25.2](https://github.com/onsi/ginkgo/compare/v2.23.4...v2.25.2)
- github.com/onsi/gomega: [v1.38.0 → v1.38.2](https://github.com/onsi/gomega/compare/v1.38.0...v1.38.2)
- go.yaml.in/yaml/v3: v3.0.3 → v3.0.4
- golang.org/x/crypto: v0.40.0 → v0.41.0
- golang.org/x/mod: v0.26.0 → v0.27.0
- golang.org/x/net: v0.42.0 → v0.43.0
- golang.org/x/sys: v0.34.0 → v0.35.0
- golang.org/x/telemetry: 8d8967a → 1a19826
- golang.org/x/term: v0.33.0 → v0.34.0
- golang.org/x/tools: v0.35.0 → v0.36.0
- google.golang.org/protobuf: v1.36.6 → v1.36.7
- k8s.io/api: v0.32.6 → v0.32.7
- k8s.io/apiextensions-apiserver: v0.32.6 → v0.32.7
- k8s.io/apimachinery: v0.32.6 → v0.32.7
- k8s.io/apiserver: v0.32.6 → v0.32.7
- k8s.io/client-go: v0.32.6 → v0.32.7
- k8s.io/code-generator: v0.32.6 → v0.32.7
- k8s.io/component-base: v0.32.6 → v0.32.7
- k8s.io/kms: v0.32.6 → v0.32.7
- sigs.k8s.io/cluster-api-operator: v0.22.0 → v0.23.0
- sigs.k8s.io/cluster-api: v1.10.3 → v1.10.5

### Removed
_Nothing has changed._

</details>
<br/>
_Thanks to all our contributors!_ 😊
