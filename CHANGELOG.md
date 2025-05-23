## v1.7.0 (December 3, 2024)

FEATURES:

ENHANCEMENTS:

* Bump RKE to v1.7.0 by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/488

BUG FIXES:

## v1.6.1 (December 3, 2024)

FEATURES:

ENHANCEMENTS:

* Bump RKE to v1.6.4 by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/486

BUG FIXES:

## v1.6.0 (November 4, 2024)

FEATURES:

ENHANCEMENTS:

* Migrate to Github Actions by @HarrisonWAffel in https://github.com/rancher/terraform-provider-rke/pull/458
* Replace 3rd party action with native CLI by @rancher-security-bot in https://github.com/rancher/terraform-provider-rke/pull/408
* [v1.6] Bump Go to 1.22 and RKE to 1.6.2 by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/462

BUG FIXES:

* [1.6] fix CI by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/464
* [1.6] fix env var in the GHA by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/466
* [1.6] fix errors around signing the shasum file by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/467
* [1.6] set the trust level non-interactively by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/468
* [1.6] use the full 40-character fingerprint by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/469
* use the first key by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/470
* find and use the secret subkey fingerprint   by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/471
* [1.6] fix CI error by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/472
* fix the decoding issue in ci by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/473
* update secret names used in CI  by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/474
* [1.6] bump rke to v1.6.3 by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/478

## v1.5.2 (December 3, 2024)

FEATURES:

ENHANCEMENTS:

* Bump RKE to v1.5.15 by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/487

BUG FIXES:

## v1.5.1 (November 4, 2024)

FEATURES:

ENHANCEMENTS:

* [1.5] bump RKE to 1.5.13, update README by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/463
* [1.5] bump RKE to v1.5.14 by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/477
* Migrate to Github Actions by @HarrisonWAffel in https://github.com/rancher/terraform-provider-rke/pull/458

BUG FIXES:

* [1.5] fix CI  by @jiaqiluo in https://github.com/rancher/terraform-provider-rke/pull/465

## 1.5.0 (April 8, 2024)

FEATURES:

ENHANCEMENTS:

* bump Go to 1.20 and RKE to v1.5.7 to support k8s 1.28. See [#447](https://github.com/rancher/terraform-provider-rke/issues/447)

BUG FIXES:

* Fix the issue that importing a cluster fails because `enable_cri_dockerd` is always set to the default value false. See [#432](https://github.com/rancher/terraform-provider-rke/issues/432)


## 1.4.4 (March 14, 2024)

FEATURES:

ENHANCEMENTS:

* Update RKE to [v1.4.16](https://github.com/rancher/rke/releases/tag/v1.4.16)

BUG FIXES:


## 1.4.3 (November 20, 2023)

FEATURES:

* Update libs and add Pod Security Admission Configuration Template (PSACT) support for `pod_security_configuration` and bind mount options. See [#416](https://github.com/rancher/terraform-provider-rke/pull/416)

ENHANCEMENTS:

* Add PR Template. See [#411](https://github.com/rancher/terraform-provider-rke/pull/411)
* Update gitignore. See [#412](https://github.com/rancher/terraform-provider-rke/pull/412)
* Use dl.k8s.io url for getting kubectl. See [#420](https://github.com/rancher/terraform-provider-rke/pull/420)
* Update RKE to [v1.4.11](https://github.com/rancher/rke/releases/tag/v1.4.11). See [#430](https://github.com/rancher/terraform-provider-rke/pull/430)
* Document and add validation on `enable_cri_dockerd` option. See [#415](https://github.com/rancher/terraform-provider-rke/pull/415)

BUG FIXES:



## 1.4.2 (July 12, 2023)

FEATURES:



ENHANCEMENTS:

* Update docs with branching and release process info. See [#391](https://github.com/rancher/terraform-provider-rke/pull/391)
* Update sdk to v2 for IDE debug capabilities. See [#347](https://github.com/rancher/terraform-provider-rke/pull/347)
* Update RKE to [v1.4.6](https://github.com/rancher/rke/releases/tag/v1.4.6) for new 1.24-1.25 Rancher images and 1.26 cluster support, and update sdk v2 to [2.27.0](https://github.com/hashicorp/terraform-plugin-sdk/releases/tag/v2.27.0) to improve schema and logging performance. See [#406](https://github.com/rancher/terraform-provider-rke/pull/406)
* Bump github.com/opencontainers/runc to 1.1.5. See [#393](https://github.com/rancher/terraform-provider-rke/pull/393)
* Bump github.com/containerd/containerd to 1.5.18. See [#394](https://github.com/rancher/terraform-provider-rke/pull/394)

BUG FIXES:



## 1.4.1 (March 23, 2023)

FEATURES:



ENHANCEMENTS:

* Update RKE to [v1.4.3](https://github.com/rancher/rke/releases/tag/v1.4.3) for new 1.23-24 Rancher images, high CPU usage fix for v1.24 clusters, and AWS hostname-override fixes. See [#386](https://github.com/rancher/terraform-provider-rke/pull/386)

BUG FIXES:



## 1.4.0 (February 24, 2023)

FEATURES:



ENHANCEMENTS:

* Update RKE to [v1.4.2](https://github.com/rancher/rke/releases/tag/v1.4.2) for new Rancher images with calico and canal and workarounds for known kubelet and kube-proxy issues. See [#377](https://github.com/rancher/terraform-provider-rke/pull/377)
* Bump golang.org/x/text to 0.3.8. See [#376](https://github.com/rancher/terraform-provider-rke/pull/376)
* Bump github.com/containerd/containerd to 1.5.18. See [#374](https://github.com/rancher/terraform-provider-rke/pull/374)
* Bump github.com/hashicorp/go-getter to 1.7.0. See [#375](https://github.com/rancher/terraform-provider-rke/pull/375)

BUG FIXES:



## 1.3.4 (October 27, 2022)

FEATURES:



ENHANCEMENTS:

* Update RKE to v1.3.15. See [#363](https://github.com/rancher/terraform-provider-rke/pull/363)

BUG FIXES:



## 1.3.3 (August 30, 2022)

FEATURES:



ENHANCEMENTS:

* Add release checklist to README. See [#356](https://github.com/rancher/terraform-provider-rke/pull/356)
* Update RKE to [v1.3.13](https://github.com/rancher/rke/releases/tag/v1.3.13) which supports kubernetes 1.24. See [#357](https://github.com/rancher/terraform-provider-rke/pull/357)

BUG FIXES:



## 1.3.2 (June 22, 2022)

FEATURES:



ENHANCEMENTS:

* Update RKE to [v1.3.11](https://github.com/rancher/rke/releases/tag/v1.3.11). See [#340](https://github.com/rancher/terraform-provider-rke/pull/340)
* Add `enable_cri_dockerd` parameter. See [#337](https://github.com/rancher/terraform-provider-rke/pull/337)

BUG FIXES:



## 1.3.1 (May 25, 2022)

BUG FIXES:

* Patch & re-assign `rke_cluster_yaml` post create. See [#327](https://github.com/rancher/terraform-provider-rke/pull/327)

## 1.3.0 (Dec 20, 2021)

FEATURES:

* **New Argument:** `rke_cluster.bastion_host.ignore_proxy_env_vars` - (Optional) Ignore proxy env vars at Bastion Host? Default: `false` (bool)

ENHANCEMENTS:

* Updated RKE to v1.3.3
* Updated `rke_cluster.services.kube_api.secrets_encryption_config.custom_config` go struct to proper marshal/unmarshal at RKE v1.3.3

BUG FIXES:



## 1.2.5 (Dec 10, 2021)

FEATURES:

* **New Argument:** `rke_cluster.ingress.http_port` - (Optional) Ingress controller http port (int)
* **New Argument:** `rke_cluster.ingress.https_port` - (Optional) Ingress controller https port (int)
* **New Argument:** `rke_cluster.ingress.network_mode` - (Optional) Networt mode for the ingress controller. `hostNetwork`, `hostPort` and `none` are supported (string)


ENHANCEMENTS:

* Updated RKE to v1.2.14

BUG FIXES:



## 1.2.4 (Oct 12, 2021)

FEATURES:



ENHANCEMENTS:

* Updated RKE to v1.2.13
* Added release binary for darwin arm64

BUG FIXES:

* Fix provider crash if `getClusterState` returns err 

## 1.2.3 (Jun 24, 2021)

FEATURES:



ENHANCEMENTS:

* Updated RKE to v1.2.9
* Updated golang to v1.16.5

BUG FIXES:



## 1.2.2 (May 7, 2021)

FEATURES:



ENHANCEMENTS:

* Updated RKE to v1.2.8

BUG FIXES:



## 1.2.1 (March 3, 2021)

FEATURES:



ENHANCEMENTS:



BUG FIXES:

* Fix `rke_cluster.services.etcd.backup_config.timeout` argument at tf schema

## 1.2.0 (March 3, 2021)

FEATURES:

* **New Argument:** `rke_cluster.services.etcd.backup_config.timeout` - (Optional/Computed) Set timeout in seconds for etcd backup. For RKE v1.2.6 and above

ENHANCEMENTS:

* Updated RKE to v1.2.6

BUG FIXES:

* Fixed example link to default system image tags for RKE

## 1.1.7 (January 7, 2021)

FEATURES:



ENHANCEMENTS:

* Updated RKE to v1.2.4

BUG FIXES:



## 1.1.6 (December 9, 2020)

FEATURES:



ENHANCEMENTS:

* Updated RKE to v1.2.3

BUG FIXES:

* Fix upgrade crash if upgrade_strategy.drain is set

## 1.1.5 (November 5, 2020)

FEATURES:



ENHANCEMENTS:

* Updated RKE to v1.2.2

BUG FIXES:



## 1.1.4 (November 5, 2020)

FEATURES:



ENHANCEMENTS:

* Updated RKE to v1.2.1 including k8s CVE:
  * [CVE-2020-8563](https://github.com/kubernetes/kubernetes/issues/95621) - Secret leaks in kube-controller-manager when using vSphere provider
  * [CVE-2020-8564](https://github.com/kubernetes/kubernetes/issues/95622) - Docker config secrets leaked when file is malformed and log level >= 4
  * [CVE-2020-8566](https://github.com/kubernetes/kubernetes/issues/95624) - Mask Ceph RBD adminSecrets in logs when logLevel >= 4

BUG FIXES:



## 1.1.3 (October 6, 2020)

FEATURES:



ENHANCEMENTS:

* Updated RKE to v1.2.0
* Updated Golang to 1.14.9, removing vendor folder
* Updated install/update section on README.md file

BUG FIXES:



## 1.1.2 (September 18, 2020)

FEATURES:



ENHANCEMENTS:

* Updated RKE to v1.1.7

BUG FIXES:

* Ordering `rancher2_cluster.certificates` to avoid output diff on tf 0.13
* Fix provider crash if `rke_state` and `rke_cluster_yaml` are not consistent about nodes count

## 1.1.1 (August 28, 2020)

FEATURES:



ENHANCEMENTS:

* Updated RKE to v1.1.6

BUG FIXES:



## 1.1.0 (August 24, 2020)

FEATURES:

* **New Feature:** Added restore feature on `rke_cluster` resource
* **Updated Arguments:** `addon_job_timeout`, `authentication`, `authorization`, `cluster_name`, `dns`, `ignore_docker_version`, `ingress`, `monitoring`, `network`, `private_registries`, `services`, `ssh_cert_path`, `ssh_key_path`, `upgrade_strategy` arguments has been defined as `computed: false`

ENHANCEMENTS:

* Updated RKE to v1.1.4
* Added support to `rke_cluster.services.kube_api.event_rate_limit.configuration`
* Added support to `rke_cluster.services.kube_api.secrets_encryption_config.custom_config`
* Updated provider docs to new registry format
* Added doc guide `Upgrade to terraform 0.13`

BUG FIXES:

* Fixed missing `nodelocal` system image custom registration
* Updated `expandRKECluster` function to fix `rke_cluster` import when audit log policy is defined
* Fixed provider crash if `rke_cluster.dind` is not defined
* Fixed `nodes` argument at `rke_cluster` resource to properly get updated
* Fixed `rke_cluster` import. Updated `rke_cluster` arguments 

## 1.0.1 (June 30, 2020)

FEATURES:



ENHANCEMENTS:

* Updated go to 1.13
* Updated RKE to v1.1.3
* Adapt provider release to met terraform registry requirements

BUG FIXES:

* Updated `cloud_provider` and `bastion_host` arguments on `rke_cluster` resource to fix false diff 
* Updated `ignore_docker_version` argument on `rke_cluster` resource to fix provider crash 

## 1.0.0 (May 7, 2020)

FEATURES:



ENHANCEMENTS:

* Set arguments as computed to avoid false diff:
  * `upgrade_strategy` on `rke_cluster` resource 
  * `ssh_key_path` on `bastion_host` argument 
  * `audit_log` on `services.kube_api` argument
* Add `external` as allowed value on `cloud_provider` argument
* Add `nodelocal` argument to `dns` argument on `rke_cluster` resource
* Updated RKE to v1.1.1

BUG FIXES:



## 1.0.0-rc5 (April 3, 2020)

FEATURES:

* **Deprecated Argument:** `nodes_conf` - Use `cluster_yaml` instead
* **Deprecated Argument:** `internal_kube_config_yaml` - Use `kube_config_yaml` instead
* **New Argument:** `cluster_yaml` - RKE cluster config yaml
* **New Import:** `rke_cluster` - RKE cluster import is supported

ENHANCEMENTS:

* Updated `hashicorp/terraform-plugin-sdk` go modules and vendor files to v1.8.0
* Updated go modules and vendor files to support [RKE v1.1.0](https://github.com/rancher/rke/releases/tag/v1.1.0)
* Added `upgrade_strategy` argument to `rke_cluster` resource
* Updated `kubernetes_version` argument to get default and available k8s versions from rke metadata

BUG FIXES:

* Fixed computed fields to avoid inconsistent plan
* Disabled `debug` config option until next rke release (Breaking logs)
* Fixed segmentation fault with deprecated fields
* Fixed `vsphere_cloud_provider` argument to avoid false diff
* Fixed segmentation fault with deprecated fields

## 1.0.0-rc4 (March 13, 2020)

FEATURES:



ENHANCEMENTS:

* Updated `log_file` to sync logs


BUG FIXES:

* Fixed computed fields to avoid inconsistent plan

## 1.0.0-rc3 (February 28, 2020)

FEATURES:



ENHANCEMENTS:

* Added `cert_dir`, `custom_certs` and `update_only` arguments to rke cluster configuration
* Refactored `rke_cluster` resource: 
  * Added uuid as tfstate id
  * Added `CustomizeDiff` to control changes
  * Saving state on any execution
* Added `kube_api.audit_log.Configuration.policy` argument to `services` argument
* Added `dind` support
* Added acceptance tests
* Added `debug` and `log_file` provider configuration


BUG FIXES:

* Fixed k8s version upgrade on `rke_cluster` resource


## 1.0.0-rc2 (February 6, 2020)

FEATURES:



ENHANCEMENTS:

* Updated go modules and vendor files to support RKE v1.0.4
* Added `mtu` argument to network configuration
* Save `rke_cluster` resource data in tfstate even if `clusterUp` fails, to be able to retry

BUG FIXES:

* Fix `nodes.port` argument definition on `rke_cluster` resource
* Fix false diffs setting: 
  * set `extra_*` and `image` arguments as computed on all `services` nested arguments
  * set `bastion_host` and `cloud_provider` arguments as non computed
  * set `hostname_override` and `internal_address` arguments as computed on `nodes` argument

## 1.0.0-rc1 (January 21, 2020)

FEATURES:

* **Deprecated Datasource:** `rke_node_parameter` - Use `rke_cluster` resource + dynamic instead
* **New Argument:** `services`
* **New Argument:** `services.etcd`  
* **Deprecated Argument:** `services_etcd` - Use `services.etcd` instead
* **New Argument:** `services.kube_api` 
* **Deprecated Argument:** `services_kube_api` - Use `services.kube_api` instead
* **New Argument:** `services.kube_controller` 
* **Deprecated Argument:** `services_kube_controller` - Use `services.kube_controller` instead
* **New Argument:** `services.kubelet` 
* **Deprecated Argument:** `services_kubelet` - Use `services.kubelet` instead
* **New Argument:** `services.kubeproxy` 
* **Deprecated Argument:** `services_kubeproxy` - Use `services.kubeproxy` instead
* **New Argument:** `services.scheduler` 
* **Deprecated Argument:** `services_scheduler` - Use `services.scheduler` instead
* **New Argument:** `cloud_provider.aws_cloud_provider`
* **Deprecated Argument:** `cloud_provider.aws_cloud_config` - Use `cloud_provider.aws_cloud_provider` instead
* **New Argument:** `cloud_provider.azure_cloud_provider`
* **Deprecated Argument:** `cloud_provider.azure_cloud_config` - Use `cloud_provider.azure_cloud_provider` instead
* **New Argument:** `cloud_provider.custom_cloud_provider`
**Deprecated Argument:** `cloud_provider.custom_cloud_config` - Use `cloud_provider.custom_cloud_provider` instead
* **New Argument:** `cloud_provider.openstack_cloud_provider`
* **Deprecated Argument:** `cloud_provider.openstack_cloud_config` - Use `cloud_provider.openstack_cloud_provider` instead
* **New Argument:** `cloud_provider.vsphere_cloud_provider`
* **Deprecated Argument:** `cloud_provider.vsphere_cloud_config` - Use `cloud_provider.vsphere_cloud_provider` instead


ENHANCEMENTS:

* Compatible with RKE v1.0.0

BUG FIXES:



**Important** There are some breaking changes from previous provider version. Some provider arguments has been deprecated, please take a look to [Documentation](website/docs)
