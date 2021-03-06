<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [Trove](./lib-base.trove.md) &gt; [adjust](./lib-base.trove.adjust.md)

## Trove.adjust() method

Calculate the result of an [adjustTrove()](./lib-base.transactableliquity.adjusttrove.md) transaction on this Trove.

<b>Signature:</b>

```typescript
adjust(params: TroveAdjustmentParams<Decimalish>, borrowingRate?: Decimalish): Trove;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  params | [TroveAdjustmentParams](./lib-base.troveadjustmentparams.md)<!-- -->&lt;[Decimalish](./decimal.decimalish.md)<!-- -->&gt; | Parameters of the transaction. |
|  borrowingRate | [Decimalish](./decimal.decimalish.md) | Borrowing rate to use when adding to the Trove's debt. |

<b>Returns:</b>

[Trove](./lib-base.trove.md)

