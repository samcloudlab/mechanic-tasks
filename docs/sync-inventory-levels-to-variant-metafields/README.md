# Sync inventory levels to variant metafields

Tags: Inventory, Metafields, Products, Sync, Variants

Use this task to easily make your inventory levels available in your online storefront theme. This task monitors for changes to inventory, and copies inventory availability figures to metafields on the related variant.

* View in the task library: [usemechanic.com/task/sync-inventory-levels-to-variant-metafields](https://usemechanic.com/task/sync-inventory-levels-to-variant-metafields)
* Task JSON, for direct import: [task.json](../../tasks/sync-inventory-levels-to-variant-metafields.json)
* Preview task code: [script.liquid](./script.liquid)

## Default options

```json
{
  "metafield_namespace__required": null,
  "location_ids_and_metafield_keys__keyval_required": null
}
```

[Learn about task options in Mechanic](https://docs.usemechanic.com/article/471-task-options)

## Subscriptions

```liquid
shopify/inventory_levels/connect
shopify/inventory_levels/update
mechanic/user/trigger
mechanic/shopify/bulk_operation
```

[Learn about event subscriptions in Mechanic](https://docs.usemechanic.com/article/408-subscriptions)

## Documentation

Use this task to easily make your inventory levels available in your online storefront theme. This task monitors for changes to inventory, and copies inventory availability figures to metafields on the related variant.

This task runs automatically, whenever an inventory level is adjusted or whenever a variant is stocked for the first time at a new location.

Run this task manually to backfill metafields for all variants that are stocked in the locations you've configured in this task.

Populate the left-hand side of the "Location IDs and metafield keys" option with your location IDs. [Learn how to find location IDs here.](https://learn.mechanic.dev/techniques/finding-a-resource-id)

## Installing this task

Find this task [in the library at usemechanic.com](https://usemechanic.com/task/sync-inventory-levels-to-variant-metafields), and use the "Try this task" button. Or, import [this task's JSON export](../../tasks/sync-inventory-levels-to-variant-metafields.json) – see [Importing and exporting tasks](https://docs.usemechanic.com/article/505-importing-and-exporting-tasks) to learn how imports work.

## Contributions

Found a bug? Got an improvement to add? Start here: [../../CONTRIBUTING.md](../../CONTRIBUTING.md).

## Task requests

Submit your [task requests](https://mechanic.canny.io/task-requests) for consideration by the Mechanic community, and they may be chosen for development and inclusion in the [task library](https://tasks.mechanic.dev/)!
