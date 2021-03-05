# UPGRADE FROM `v1.0.8` TO `v1.1.0`

* **BC BREAK**: Rename composer vendor name from
  `prometee\sylius-vies-client-plugin` to `flux-se\sylius-eu-vat-plugin`
* **BC BREAK**: Rename the namespace vendor name from
  `Prometee\SyliusVIESClientPlugin` to `FluxSE\SyliusEUVatPlugin`
* **BC BREAK**: Rename classes from
  `PrometeeSyliusVIESClientPlugin` to `FluxSESyliusEUVatPlugin`
  `PrometeeSyliusVIESClientExtension` to `FluxSESyliusEUVatExtension`
* **BC BREAK**: Rename the service names from
  `flux_se.sylius_vies_client_plugin.*` to `flux_se.sylius_eu_vat.*`
* **BC BREAK**: Rename translations name from
  `flux_se_sylius_vies_client.*` to `flux_se.sylius_eu_vat`

# UPGRADE FROM `v1.0.0` TO `v1.0.1`

* **BC BREAK**: `Prometee\SyliusVIESClientPlugin\Entity\Channel` have to be defined into your `src/Entity/Channel` directory 
* **BC BREAK**: `Prometee\SyliusVIESClientPlugin\Entity\ChannelInterface` have to be defined into your `src/Entity/Channel` directory 
* **BC BREAK**: `Prometee\SyliusVIESClientPlugin\Entity\Address` have to be defined into your `src/Entity/Addressing` directory
* **BC BREAK**: `Prometee\SyliusVIESClientPlugin\Entity\AddressInterface` have to be defined into your `src/Entity/Addressing` directory