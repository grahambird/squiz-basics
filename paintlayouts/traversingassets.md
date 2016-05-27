# Traversing assets

Let's say we have two assets on a website about road bikes.

* Asset #123 is an article about new bikes.
* Asset #456 is an asset that represents the Cannondale brand.

## Accessing another asset via a metadata field value

To access the properties of an asset that has been linked to via a related asset metadata field...

```
The current asset is %asset_assetid%
This asset's name is %asset_attribute_name%
The value of the brand field is %asset_metadata_brand%
The name of the related asset is %asset_metadata_brand^as_asset:asset_attribute_name%

```

prints:

```
The current asset is 123
This asset's name is New road bikes revealed
The value of the brand field is 456
The name of the related asset is Cannondale
```
