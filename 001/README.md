Complete ontologies structure
ontologies/
├── 01_base/
│   ├── 01_attributes_definition.ttl
│   ├── 02_assets_definition_and_taxonomy.ttl
│   └── 03_relationships_definition.ttl
│
├── 02_specialized/
│   ├── 01_assets_attributes.ttl
│   └── 02_assets_relationships.ttl
│
└── simple_assets_example.ttl

Imports hierarchy
simple_assets_example.ttl
├── 01_assets_attributes.ttl
│   ├── 01_attributes_definition.ttl
│   ├── 02_assets_definition_and_taxonomy.ttl
│   └── 03_relationships_definition.ttl
└── 02_assets_relationships.ttl
    ├── 01_attributes_definition.ttl
    ├── 02_assets_definition_and_taxonomy.ttl
    └── 03_relationships_definition.ttl
