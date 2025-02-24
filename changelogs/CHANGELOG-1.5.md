# Changelog since v1.4.0

## v1.5.1

Date: 2022-5-2

### Changes

- Remove busybox reference from Dockerfiles ([#524](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/524), [@deepakkinni](https://github.com/deepakkinni))
- Use Photon 4.0 base image in Dockerfiles ([#528](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/528), [@deepakkinni](https://github.com/deepakkinni))
- Update consumed velero to 1.10.2 ([#529](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/529), [@deepakkinni](https://github.com/deepakkinni))

## Dependencies

### Added
_Nothing has changed._

### Changed
- github.com/vmware-tanzu/velero: [v1.10.1 → v1.10.2](https://github.com/vmware-tanzu/velero/compare/v1.10.1...v1.10.2)

### Removed
- github.com/armon/consul-api: [eb2c6b5](https://github.com/armon/consul-api/tree/eb2c6b5)
- github.com/blang/semver: [v3.5.0+incompatible](https://github.com/blang/semver/tree/v3.5.0)
- github.com/mattn/go-runewidth: [v0.0.2](https://github.com/mattn/go-runewidth/tree/v0.0.2)
- github.com/olekukonko/tablewriter: [a0225b3](https://github.com/olekukonko/tablewriter/tree/a0225b3)
- github.com/ugorji/go: [v1.1.4](https://github.com/ugorji/go/tree/v1.1.4)
- github.com/urfave/cli: [v1.20.0](https://github.com/urfave/cli/tree/v1.20.0)
- github.com/xordataexchange/crypt: [b2862e3](https://github.com/xordataexchange/crypt/tree/b2862e3)
- go.etcd.io/etcd: 17cef6e
- gopkg.in/cheggaaa/pb.v1: v1.0.25

## v1.5.0

Date: 2022-2-22

### Changes

- 1.24 support for backup-driver Deployment ([#508](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/508), [@deepakkinni](https://github.com/deepakkinni))
- Add notes for configurable block list. ([#511](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/511), [@xinyanw409](https://github.com/xinyanw409))
- Changes to support velero v1.10 ([#500](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/500), [@deepakkinni](https://github.com/deepakkinni))
- Make resources to block list configurable. ([#510](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/510), [@xinyanw409](https://github.com/xinyanw409))
- Update Astrolabe to 0.6.0 ([#515](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/515), [@deepakkinni](https://github.com/deepakkinni))
- Update go mod to resolve CVE-2022-28948, CVE-2022-41717, CVE-2022-41721, CVE-2022-43551, CVE-2022-43552,
  CVE-2022-1304, CVE-2022-42898, CVE-2022-40303, CVE-2022-40304, CVE-2022-3996, CVE-2022-4203,
  CVE-2022-4304, CVE-2022-4450, CVE-2023-0215, CVE-2023-0216, CVE-2023-0217, CVE-2023-0401,
  CVE-2022-46908 ([#514](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/514), [@deepakkinni](https://github.com/deepakkinni))
- Update supervisor deployment doc to indicate that velero-vsphere-plugin-config needs to be created. ([#509](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/509), [@deepakkinni](https://github.com/deepakkinni))
- Fix datamgr Dockerfile ([#518](https://github.com/vmware-tanzu/velero-plugin-for-vsphere/pull/518), [@deepakkinni](https://github.com/deepakkinni))

## Dependencies

### Added
- cloud.google.com/go/compute/metadata: v0.2.0
- cloud.google.com/go/compute: v1.5.0
- cloud.google.com/go/iam: v0.1.1
- github.com/Azure/azure-pipeline-go: [v0.2.3](https://github.com/Azure/azure-pipeline-go/tree/v0.2.3)
- github.com/Azure/azure-sdk-for-go/sdk/azcore: [v0.21.1](https://github.com/Azure/azure-sdk-for-go/sdk/azcore/tree/v0.21.1)
- github.com/Azure/azure-sdk-for-go/sdk/internal: [v0.8.3](https://github.com/Azure/azure-sdk-for-go/sdk/internal/tree/v0.8.3)
- github.com/Azure/azure-sdk-for-go/sdk/storage/azblob: [v0.3.0](https://github.com/Azure/azure-sdk-for-go/sdk/storage/azblob/tree/v0.3.0)
- github.com/Azure/azure-storage-blob-go: [v0.14.0](https://github.com/Azure/azure-storage-blob-go/tree/v0.14.0)
- github.com/GehirnInc/crypt: [bb7000b](https://github.com/GehirnInc/crypt/tree/bb7000b)
- github.com/alecthomas/kingpin: [b6657d9](https://github.com/alecthomas/kingpin/tree/b6657d9)
- github.com/alessio/shellescape: [v1.4.1](https://github.com/alessio/shellescape/tree/v1.4.1)
- github.com/antlr/antlr4/runtime/Go/antlr: [b48c857](https://github.com/antlr/antlr4/runtime/Go/antlr/tree/b48c857)
- github.com/armon/go-socks5: [e753329](https://github.com/armon/go-socks5/tree/e753329)
- github.com/blang/semver/v4: [v4.0.0](https://github.com/blang/semver/v4/tree/v4.0.0)
- github.com/bombsimon/logrusr/v3: [v3.0.0](https://github.com/bombsimon/logrusr/v3/tree/v3.0.0)
- github.com/buger/jsonparser: [v1.1.1](https://github.com/buger/jsonparser/tree/v1.1.1)
- github.com/chmduquesne/rollinghash: [v4.0.0+incompatible](https://github.com/chmduquesne/rollinghash/tree/v4.0.0)
- github.com/chromedp/cdproto: [7bc2623](https://github.com/chromedp/cdproto/tree/7bc2623)
- github.com/chromedp/chromedp: [v0.8.0](https://github.com/chromedp/chromedp/tree/v0.8.0)
- github.com/chromedp/sysutil: [v1.0.0](https://github.com/chromedp/sysutil/tree/v1.0.0)
- github.com/danieljoos/wincred: [v1.1.2](https://github.com/danieljoos/wincred/tree/v1.1.2)
- github.com/dgryski/go-sip13: [e10d5fe](https://github.com/dgryski/go-sip13/tree/e10d5fe)
- github.com/dnaeon/go-vcr: [v1.2.0](https://github.com/dnaeon/go-vcr/tree/v1.2.0)
- github.com/dustinkirkland/golang-petname: [8e5a1ed](https://github.com/dustinkirkland/golang-petname/tree/8e5a1ed)
- github.com/emicklei/go-restful/v3: [v3.8.0](https://github.com/emicklei/go-restful/v3/tree/v3.8.0)
- github.com/flowstack/go-jsonschema: [v0.1.1](https://github.com/flowstack/go-jsonschema/tree/v0.1.1)
- github.com/foomo/htpasswd: [e3a90e7](https://github.com/foomo/htpasswd/tree/e3a90e7)
- github.com/frankban/quicktest: [v1.13.1](https://github.com/frankban/quicktest/tree/v1.13.1)
- github.com/getkin/kin-openapi: [v0.76.0](https://github.com/getkin/kin-openapi/tree/v0.76.0)
- github.com/gobwas/httphead: [v0.1.0](https://github.com/gobwas/httphead/tree/v0.1.0)
- github.com/gobwas/pool: [v0.2.1](https://github.com/gobwas/pool/tree/v0.2.1)
- github.com/gobwas/ws: [v1.1.0](https://github.com/gobwas/ws/tree/v1.1.0)
- github.com/gofrs/flock: [v0.8.1](https://github.com/gofrs/flock/tree/v0.8.1)
- github.com/golang-jwt/jwt/v4: [v4.4.1](https://github.com/golang-jwt/jwt/v4/tree/v4.4.1)
- github.com/google/cel-go: [v0.10.1](https://github.com/google/cel-go/tree/v0.10.1)
- github.com/google/cel-spec: [v0.6.0](https://github.com/google/cel-spec/tree/v0.6.0)
- github.com/google/fswalker: [f0e929b](https://github.com/google/fswalker/tree/f0e929b)
- github.com/google/gnostic: [v0.6.9](https://github.com/google/gnostic/tree/v0.6.9)
- github.com/google/readahead: [eaceba1](https://github.com/google/readahead/tree/eaceba1)
- github.com/gorilla/mux: [v1.8.0](https://github.com/gorilla/mux/tree/v1.8.0)
- github.com/hanwen/go-fuse/v2: [f57e95b](https://github.com/hanwen/go-fuse/v2/tree/f57e95b)
- github.com/jhump/protoreflect: [v1.6.0](https://github.com/jhump/protoreflect/tree/v1.6.0)
- github.com/klauspost/cpuid/v2: [v2.0.12](https://github.com/klauspost/cpuid/v2/tree/v2.0.12)
- github.com/klauspost/cpuid: [v1.3.1](https://github.com/klauspost/cpuid/tree/v1.3.1)
- github.com/klauspost/pgzip: [v1.2.5](https://github.com/klauspost/pgzip/tree/v1.2.5)
- github.com/kopia/htmluibuild: [bbc499e](https://github.com/kopia/htmluibuild/tree/bbc499e)
- github.com/kopia/kopia: [v0.10.7](https://github.com/kopia/kopia/tree/v0.10.7)
- github.com/kylelemons/godebug: [v1.1.0](https://github.com/kylelemons/godebug/tree/v1.1.0)
- github.com/mattn/go-ieproxy: [v0.0.1](https://github.com/mattn/go-ieproxy/tree/v0.0.1)
- github.com/minio/md5-simd: [v1.1.2](https://github.com/minio/md5-simd/tree/v1.1.2)
- github.com/minio/minio-go/v7: [v7.0.23](https://github.com/minio/minio-go/v7/tree/v7.0.23)
- github.com/minio/sha256-simd: [v1.0.0](https://github.com/minio/sha256-simd/tree/v1.0.0)
- github.com/modocache/gover: [b58185e](https://github.com/modocache/gover/tree/b58185e)
- github.com/natefinch/atomic: [v1.0.1](https://github.com/natefinch/atomic/tree/v1.0.1)
- github.com/pierrec/lz4: [v2.6.1+incompatible](https://github.com/pierrec/lz4/tree/v2.6.1)
- github.com/pkg/diff: [20ebb0f](https://github.com/pkg/diff/tree/20ebb0f)
- github.com/pkg/profile: [v1.6.0](https://github.com/pkg/profile/tree/v1.6.0)
- github.com/pquerna/ffjson: [aa0246c](https://github.com/pquerna/ffjson/tree/aa0246c)
- github.com/prometheus/tsdb: [v0.7.1](https://github.com/prometheus/tsdb/tree/v0.7.1)
- github.com/rs/xid: [v1.3.0](https://github.com/rs/xid/tree/v1.3.0)
- github.com/rs/zerolog: [v1.21.0](https://github.com/rs/zerolog/tree/v1.21.0)
- github.com/sanity-io/litter: [v1.5.4](https://github.com/sanity-io/litter/tree/v1.5.4)
- github.com/skratchdot/open-golang: [eef8423](https://github.com/skratchdot/open-golang/tree/eef8423)
- github.com/studio-b12/gowebdav: [29e74ef](https://github.com/studio-b12/gowebdav/tree/29e74ef)
- github.com/tg123/go-htpasswd: [v1.2.0](https://github.com/tg123/go-htpasswd/tree/v1.2.0)
- github.com/xeipuuv/gojsonpointer: [4e3ac27](https://github.com/xeipuuv/gojsonpointer/tree/4e3ac27)
- github.com/xeipuuv/gojsonreference: [bd5ef7b](https://github.com/xeipuuv/gojsonreference/tree/bd5ef7b)
- github.com/xeipuuv/gojsonschema: [v1.2.0](https://github.com/xeipuuv/gojsonschema/tree/v1.2.0)
- github.com/zalando/go-keyring: [v0.2.1](https://github.com/zalando/go-keyring/tree/v0.2.1)
- github.com/zeebo/assert: [v1.1.0](https://github.com/zeebo/assert/tree/v1.1.0)
- github.com/zeebo/blake3: [v0.2.3](https://github.com/zeebo/blake3/tree/v0.2.3)
- github.com/zeebo/pcg: [v1.0.1](https://github.com/zeebo/pcg/tree/v1.0.1)
- gopkg.in/kothar/go-backblaze.v0: 35409b8
- sigs.k8s.io/json: 227cbc7

### Changed
- cloud.google.com/go/firestore: v1.6.0 → v1.1.0
- cloud.google.com/go/storage: v1.10.0 → v1.21.0
- cloud.google.com/go: v0.93.3 → v0.100.2
- dmitri.shuralyov.com/gpu/mtl: 666a987 → 28db891
- github.com/Azure/azure-sdk-for-go: [v55.0.0+incompatible → v61.4.0+incompatible](https://github.com/Azure/azure-sdk-for-go/compare/v55.0.0...v61.4.0)
- github.com/Azure/go-autorest/autorest/adal: [v0.9.14 → v0.9.16](https://github.com/Azure/go-autorest/autorest/adal/compare/v0.9.14...v0.9.16)
- github.com/alecthomas/units: [f65c72e → 59d0afb](https://github.com/alecthomas/units/compare/f65c72e...59d0afb)
- github.com/armon/go-radix: [v1.0.0 → 7fddfc3](https://github.com/armon/go-radix/compare/v1.0.0...7fddfc3)
- github.com/aws/aws-sdk-go: [v1.42.10 → v1.44.207](https://github.com/aws/aws-sdk-go/compare/v1.42.10...v1.44.207)
- github.com/blang/semver: [v3.5.1+incompatible → v3.5.0+incompatible](https://github.com/blang/semver/compare/v3.5.1...v3.5.0)
- github.com/cespare/xxhash/v2: [v2.1.1 → v2.1.2](https://github.com/cespare/xxhash/v2/compare/v2.1.1...v2.1.2)
- github.com/cncf/udpa/go: [5459f2c → 04548b0](https://github.com/cncf/udpa/go/compare/5459f2c...04548b0)
- github.com/cncf/xds/go: [fbca930 → cb28da3](https://github.com/cncf/xds/go/compare/fbca930...cb28da3)
- github.com/cpuguy83/go-md2man/v2: [v2.0.0 → v2.0.1](https://github.com/cpuguy83/go-md2man/v2/compare/v2.0.0...v2.0.1)
- github.com/envoyproxy/go-control-plane: [63b5d3c → cf90f65](https://github.com/envoyproxy/go-control-plane/compare/63b5d3c...cf90f65)
- github.com/evanphx/json-patch: [v4.11.0+incompatible → v5.6.0+incompatible](https://github.com/evanphx/json-patch/compare/v4.11.0...v5.6.0)
- github.com/fsnotify/fsnotify: [v1.5.1 → v1.5.4](https://github.com/fsnotify/fsnotify/compare/v1.5.1...v1.5.4)
- github.com/go-kit/kit: [v0.9.0 → v0.10.0](https://github.com/go-kit/kit/compare/v0.9.0...v0.10.0)
- github.com/go-kit/log: [v0.1.0 → v0.2.0](https://github.com/go-kit/log/compare/v0.1.0...v0.2.0)
- github.com/go-logfmt/logfmt: [v0.5.0 → v0.5.1](https://github.com/go-logfmt/logfmt/compare/v0.5.0...v0.5.1)
- github.com/go-logr/logr: [v0.4.0 → v1.2.3](https://github.com/go-logr/logr/compare/v0.4.0...v1.2.3)
- github.com/go-logr/zapr: [v0.4.0 → v1.2.0](https://github.com/go-logr/zapr/compare/v0.4.0...v1.2.0)
- github.com/go-openapi/jsonreference: [v0.19.6 → v0.20.0](https://github.com/go-openapi/jsonreference/compare/v0.19.6...v0.20.0)
- github.com/go-openapi/swag: [v0.19.15 → v0.21.1](https://github.com/go-openapi/swag/compare/v0.19.15...v0.21.1)
- github.com/gobuffalo/flect: [v0.2.3 → v0.1.3](https://github.com/gobuffalo/flect/compare/v0.2.3...v0.1.3)
- github.com/godbus/dbus/v5: [v5.0.4 → v5.0.6](https://github.com/godbus/dbus/v5/compare/v5.0.4...v5.0.6)
- github.com/golang/glog: [23def4e → v1.0.0](https://github.com/golang/glog/compare/23def4e...v1.0.0)
- github.com/google/go-cmp: [v0.5.6 → v0.5.8](https://github.com/google/go-cmp/compare/v0.5.6...v0.5.8)
- github.com/google/uuid: [v1.1.2 → v1.3.0](https://github.com/google/uuid/compare/v1.1.2...v1.3.0)
- github.com/googleapis/gax-go/v2: [v2.1.0 → v2.2.0](https://github.com/googleapis/gax-go/v2/compare/v2.1.0...v2.2.0)
- github.com/hashicorp/consul/api: [v1.10.1 → v1.1.0](https://github.com/hashicorp/consul/api/compare/v1.10.1...v1.1.0)
- github.com/hashicorp/consul/sdk: [v0.8.0 → v0.1.1](https://github.com/hashicorp/consul/sdk/compare/v0.8.0...v0.1.1)
- github.com/hashicorp/go-hclog: [v0.12.0 → v0.14.1](https://github.com/hashicorp/go-hclog/compare/v0.12.0...v0.14.1)
- github.com/hashicorp/go-multierror: [v1.1.0 → v1.0.0](https://github.com/hashicorp/go-multierror/compare/v1.1.0...v1.0.0)
- github.com/hashicorp/go-plugin: [a1bc615 → v1.4.3](https://github.com/hashicorp/go-plugin/compare/a1bc615...v1.4.3)
- github.com/hashicorp/go-rootcerts: [v1.0.2 → v1.0.0](https://github.com/hashicorp/go-rootcerts/compare/v1.0.2...v1.0.0)
- github.com/hashicorp/golang-lru: [v0.5.1 → v0.5.4](https://github.com/hashicorp/golang-lru/compare/v0.5.1...v0.5.4)
- github.com/hashicorp/mdns: [v1.0.1 → v1.0.0](https://github.com/hashicorp/mdns/compare/v1.0.1...v1.0.0)
- github.com/hashicorp/memberlist: [v0.2.2 → v0.1.3](https://github.com/hashicorp/memberlist/compare/v0.2.2...v0.1.3)
- github.com/hashicorp/serf: [v0.9.5 → v0.8.2](https://github.com/hashicorp/serf/compare/v0.9.5...v0.8.2)
- github.com/imdario/mergo: [v0.3.12 → v0.3.13](https://github.com/imdario/mergo/compare/v0.3.12...v0.3.13)
- github.com/json-iterator/go: [v1.1.11 → v1.1.12](https://github.com/json-iterator/go/compare/v1.1.11...v1.1.12)
- github.com/klauspost/compress: [v1.13.6 → v1.15.1](https://github.com/klauspost/compress/compare/v1.13.6...v1.15.1)
- github.com/kr/pretty: [v0.2.0 → v0.3.0](https://github.com/kr/pretty/compare/v0.2.0...v0.3.0)
- github.com/kubernetes-csi/external-snapshotter/client/v4: [v4.0.0 → v4.2.0](https://github.com/kubernetes-csi/external-snapshotter/client/v4/compare/v4.0.0...v4.2.0)
- github.com/mailru/easyjson: [v0.7.6 → v0.7.7](https://github.com/mailru/easyjson/compare/v0.7.6...v0.7.7)
- github.com/mattn/go-colorable: [v0.1.11 → v0.1.12](https://github.com/mattn/go-colorable/compare/v0.1.11...v0.1.12)
- github.com/mattn/go-runewidth: [v0.0.13 → v0.0.2](https://github.com/mattn/go-runewidth/compare/v0.0.13...v0.0.2)
- github.com/miekg/dns: [v1.1.26 → v1.0.14](https://github.com/miekg/dns/compare/v1.1.26...v1.0.14)
- github.com/mitchellh/cli: [v1.1.0 → v1.0.0](https://github.com/mitchellh/cli/compare/v1.1.0...v1.0.0)
- github.com/moby/term: [9d4ed18 → 3f7ff69](https://github.com/moby/term/compare/9d4ed18...3f7ff69)
- github.com/modern-go/reflect2: [v1.0.1 → v1.0.2](https://github.com/modern-go/reflect2/compare/v1.0.1...v1.0.2)
- github.com/olekukonko/tablewriter: [v0.0.4 → a0225b3](https://github.com/olekukonko/tablewriter/compare/v0.0.4...a0225b3)
- github.com/onsi/ginkgo: [v1.16.4 → v1.16.5](https://github.com/onsi/ginkgo/compare/v1.16.4...v1.16.5)
- github.com/onsi/gomega: [v1.16.0 → v1.18.1](https://github.com/onsi/gomega/compare/v1.16.0...v1.18.1)
- github.com/pelletier/go-toml: [v1.9.4 → v1.9.3](https://github.com/pelletier/go-toml/compare/v1.9.4...v1.9.3)
- github.com/pkg/sftp: [v1.10.1 → v1.13.4](https://github.com/pkg/sftp/compare/v1.10.1...v1.13.4)
- github.com/posener/complete: [v1.2.3 → v1.1.1](https://github.com/posener/complete/compare/v1.2.3...v1.1.1)
- github.com/prometheus/client_golang: [v1.11.1 → v1.12.2](https://github.com/prometheus/client_golang/compare/v1.11.1...v1.12.2)
- github.com/prometheus/common: [v0.26.0 → v0.34.0](https://github.com/prometheus/common/compare/v0.26.0...v0.34.0)
- github.com/prometheus/procfs: [v0.6.0 → v0.7.3](https://github.com/prometheus/procfs/compare/v0.6.0...v0.7.3)
- github.com/rogpeppe/go-internal: [v1.3.0 → v1.9.0](https://github.com/rogpeppe/go-internal/compare/v1.3.0...v1.9.0)
- github.com/russross/blackfriday/v2: [v2.0.1 → v2.1.0](https://github.com/russross/blackfriday/v2/compare/v2.0.1...v2.1.0)
- github.com/spf13/cast: [v1.4.1 → v1.3.1](https://github.com/spf13/cast/compare/v1.4.1...v1.3.1)
- github.com/spf13/cobra: [v1.2.1 → v1.4.0](https://github.com/spf13/cobra/compare/v1.2.1...v1.4.0)
- github.com/spf13/viper: [v1.9.0 → v1.8.1](https://github.com/spf13/viper/compare/v1.9.0...v1.8.1)
- github.com/stretchr/testify: [v1.7.0 → v1.7.1](https://github.com/stretchr/testify/compare/v1.7.0...v1.7.1)
- github.com/vmware-tanzu/astrolabe: [b206312 → v0.6.0](https://github.com/vmware-tanzu/astrolabe/compare/b206312...v0.6.0)
- github.com/vmware-tanzu/velero: [v1.7.1 → v1.10.1](https://github.com/vmware-tanzu/velero/compare/v1.7.1...v1.10.1)
- go.etcd.io/etcd/api/v3: v3.5.0 → v3.5.1
- go.etcd.io/etcd/client/pkg/v3: v3.5.0 → v3.5.1
- go.etcd.io/etcd/client/v3: v3.5.0 → v3.5.1
- go.uber.org/atomic: v1.7.0 → v1.9.0
- go.uber.org/goleak: v1.1.10 → v1.1.12
- go.uber.org/multierr: v1.6.0 → v1.8.0
- go.uber.org/zap: v1.19.0 → v1.21.0
- golang.org/x/crypto: 1baeb1c → v0.6.0
- golang.org/x/exp: 6cc2880 → 5cb4fee
- golang.org/x/mobile: d2bd2a2 → e6ae53a
- golang.org/x/net: f3363e0 → v0.7.0
- golang.org/x/oauth2: 2bc19b1 → v0.5.0
- golang.org/x/sys: 3c1f352 → v0.5.0
- golang.org/x/term: 03fcf44 → v0.5.0
- golang.org/x/text: v0.3.8 → v0.7.0
- golang.org/x/time: 1f47c86 → v0.3.0
- google.golang.org/api: v0.56.0 → v0.74.0
- google.golang.org/genproto: 66f60bf → acbaeb5
- google.golang.org/grpc: v1.40.0 → v1.45.0
- google.golang.org/protobuf: v1.27.1 → v1.28.0
- gopkg.in/check.v1: 8fa4692 → 10cb982
- gopkg.in/ini.v1: v1.63.2 → v1.66.2
- gopkg.in/yaml.v3: 496545a → v3.0.1
- honnef.co/go/tools: v0.0.1-2020.1.4 → v0.1.3
- k8s.io/api: v0.22.4 → v0.24.2
- k8s.io/apiextensions-apiserver: v0.22.4 → v0.24.2
- k8s.io/apimachinery: v0.22.4 → v0.24.2
- k8s.io/apiserver: v0.22.4 → v0.24.2
- k8s.io/cli-runtime: v0.22.2 → v0.24.0
- k8s.io/client-go: v0.22.4 → v0.24.2
- k8s.io/code-generator: v0.22.4 → v0.24.2
- k8s.io/component-base: v0.22.4 → v0.24.2
- k8s.io/gengo: b6c5ce2 → c02415c
- k8s.io/klog/v2: v2.9.0 → v2.60.1
- k8s.io/kube-openapi: 2043435 → 1062c7a
- k8s.io/utils: cb0fa31 → 3a6ce19
- sigs.k8s.io/apiserver-network-proxy/konnectivity-client: v0.0.22 → v0.0.30
- sigs.k8s.io/controller-runtime: v0.10.2 → v0.12.2
- sigs.k8s.io/kustomize/api: v0.8.11 → v0.11.4
- sigs.k8s.io/kustomize/kyaml: v0.11.0 → v0.13.6
- sigs.k8s.io/structured-merge-diff/v4: v4.1.2 → v4.2.1

### Removed
- github.com/MakeNowJust/heredoc: [v1.0.0](https://github.com/MakeNowJust/heredoc/tree/v1.0.0)
- github.com/chai2010/gettext-go: [c6fed77](https://github.com/chai2010/gettext-go/tree/c6fed77)
- github.com/coredns/caddy: [v1.1.0](https://github.com/coredns/caddy/tree/v1.1.0)
- github.com/coredns/corefile-migration: [v1.0.13](https://github.com/coredns/corefile-migration/tree/v1.0.13)
- github.com/daviddengcn/go-colortext: [511bcaf](https://github.com/daviddengcn/go-colortext/tree/511bcaf)
- github.com/docker/distribution: [v2.7.1+incompatible](https://github.com/docker/distribution/tree/v2.7.1)
- github.com/drone/envsubst/v2: [7bf45db](https://github.com/drone/envsubst/v2/tree/7bf45db)
- github.com/exponent-io/jsonpath: [d6023ce](https://github.com/exponent-io/jsonpath/tree/d6023ce)
- github.com/fatih/camelcase: [v1.0.0](https://github.com/fatih/camelcase/tree/v1.0.0)
- github.com/flynn/go-shlex: [3f9db97](https://github.com/flynn/go-shlex/tree/3f9db97)
- github.com/fvbommel/sortorder: [v1.0.1](https://github.com/fvbommel/sortorder/tree/v1.0.1)
- github.com/go-task/slim-sprig: [348f09d](https://github.com/go-task/slim-sprig/tree/348f09d)
- github.com/gofrs/uuid: [v4.0.0+incompatible](https://github.com/gofrs/uuid/tree/v4.0.0)
- github.com/golangplus/testing: [af21d9c](https://github.com/golangplus/testing/tree/af21d9c)
- github.com/google/go-github/v33: [v33.0.0](https://github.com/google/go-github/v33/tree/v33.0.0)
- github.com/google/go-querystring: [v1.0.0](https://github.com/google/go-querystring/tree/v1.0.0)
- github.com/gosuri/uitable: [v0.0.4](https://github.com/gosuri/uitable/tree/v0.0.4)
- github.com/lithammer/dedent: [v1.1.0](https://github.com/lithammer/dedent/tree/v1.1.0)
- github.com/mitchellh/go-wordwrap: [v1.0.0](https://github.com/mitchellh/go-wordwrap/tree/v1.0.0)
- github.com/opencontainers/go-digest: [v1.0.0](https://github.com/opencontainers/go-digest/tree/v1.0.0)
- github.com/rivo/uniseg: [v0.2.0](https://github.com/rivo/uniseg/tree/v0.2.0)
- github.com/russross/blackfriday: [v1.5.2](https://github.com/russross/blackfriday/tree/v1.5.2)
- github.com/sagikazarmark/crypt: [v0.1.0](https://github.com/sagikazarmark/crypt/tree/v0.1.0)
- k8s.io/cluster-bootstrap: v0.22.2
- k8s.io/component-helpers: v0.22.2
- k8s.io/kubectl: v0.22.2
- k8s.io/metrics: v0.22.2
- sigs.k8s.io/cluster-api: v1.0.0
- sigs.k8s.io/kustomize/cmd/config: v0.9.13
- sigs.k8s.io/kustomize/kustomize/v4: v4.2.0