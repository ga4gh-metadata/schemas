
## _id

the database-internal object id

#### Example

`ObjectId("558e5c56ad9a82d958392bd6")
`

## biosample_id

The identifier ("biosample.id") of the biosample this variant was reported from. This is a shortcut to using the variant -> callset -> biosample chaining.

#### Example

`pgx-bs-987647
`

## description

A free text description of the callset.

#### Example

`SNP6 array of cancer sample BRCA-0893
`

## geo_provenance

This geo_class attribute ideally describes the geographic location of where this callset was analysed.


#### Example

```
[
  {
    'longitude' => '21.23',
    'country' => 'Romania',
    'city' => 'Timisoara',
    'label' => 'Str Marasesti 5, 300077 Timisoara, Romania',
    'latitude' => '45.75'
  }
]

```

## id

The local-unique identifier of this callset (referenced as "callset_id").

#### Example

`GSM264198
`

## updated

time of the last edit of this record, in ISO8601

#### Example

`2017-10-25T07:06:03Z
`
