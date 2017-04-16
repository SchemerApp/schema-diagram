# schema-diagram
Core visual component for https://github.com/SchemerApp/schemer-desktop

This component can also be the basis for an interactive visual database documentation, provided you correctly use the `schema` variable

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="schema-diagram.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<schema-diagram
                schema='[{ "name": "Table_1", "columns": [{"name": "id", "type": "integer"}, {"name": "val", "type": "string"}], "relations": ["config_table.id"]},
            { "name": "config_table", "columns": [{"name": "id", "type": "integer"}, { "name": "value", "type": "string"}], "relations": []}]'></schema-diagram>
```

> More documentation coming soon


License

MIT
