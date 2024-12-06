This package enables Shopware to write to an Azure Storage Account via Flysystem. It acts as a wrapper around https://github.com/thephpleague/flysystem-azure-blob-storage. To install:

1. Run `composer require torqit/shopware-flysystem-azure-bundle`
2. Register the bundle by adding it to your project's `bundles.php` file:
    ```php
   <?php
   return [
      ...
      TorqIT\FlysystemAzureBundle\FlysystemAzureBundle::class => ['all' => true]
   ];
3. Add the contents of the file `shopware_example.yaml` to your project's `shopware.yaml` file (typically located at `config/packages/shopware.yaml`), adjusting the environment variables as necessary.
