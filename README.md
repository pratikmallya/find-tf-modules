# find-tf-modules

Find all terraform modules in a target directory

### Example

Find all tf modules in [terraform-google-kubernetes-engine]:

```
./find-tf-modules /Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine

/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/autogen/main
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/acm-terraform-blog-part1/terraform
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/acm-terraform-blog-part2/terraform
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/acm-terraform-blog-part3/terraform
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/deploy_service
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/disable_client_cert
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/node_pool
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/node_pool_update_variant
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/node_pool_update_variant_beta
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/node_pool_update_variant_public_beta
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/private_zonal_with_networking
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/regional_private_node_pool_oauth_scopes
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/safer_cluster
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/safer_cluster_iap_bastion
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/shared_vpc
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_autopilot_private
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_autopilot_public
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_regional
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_regional_beta
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_regional_private
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_regional_private_beta
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_regional_with_kubeconfig
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_regional_with_networking
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_zonal_private
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_zonal_with_acm
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_zonal_with_asm
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_zonal_with_hub
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/simple_zonal_with_hub_kubeconfig
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/stub_domains
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/stub_domains_private
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/stub_domains_upstream_nameservers
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/upstream_nameservers
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/workload_identity
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/examples/workload_metadata_config
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/acm
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/asm
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/auth
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/beta-autopilot-private-cluster
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/beta-autopilot-public-cluster
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/beta-private-cluster
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/beta-private-cluster-update-variant
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/beta-public-cluster
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/beta-public-cluster-update-variant
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/binary-authorization
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/config-sync
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/hub
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/k8s-operator-crd-support
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/private-cluster
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/private-cluster-update-variant
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/safer-cluster
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/safer-cluster-update-variant
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/services
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/modules/workload-identity
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/all_examples
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/beta_cluster
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/deploy_service
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/disable_client_cert
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/node_pool
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/node_pool_update_variant
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/private_zonal_with_networking
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/safer_cluster
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/safer_cluster_iap_bastion
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/sandbox_enabled
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/shared
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/shared_vpc
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/simple_autopilot_private
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/simple_autopilot_public
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/simple_regional
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/simple_regional_private
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/simple_regional_with_kubeconfig
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/simple_regional_with_networking
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/simple_zonal
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/simple_zonal_private
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/simple_zonal_with_asm
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/stub_domains
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/stub_domains_private
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/stub_domains_upstream_nameservers
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/upstream_nameservers
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/workload_identity
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/fixtures/workload_metadata_config
/Users/pratikmallya/code/terraform-google-modules/terraform-google-kubernetes-engine/test/setup
```

[terraform-google-kubernetes-engine]: https://github.com/terraform-google-modules/terraform-google-kubernetes-engine
