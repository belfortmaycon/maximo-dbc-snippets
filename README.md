# maximo-dbc-snippets README

This extension includes the most commonly used IBM Maximo DBC elements by developers in their daily activities.

It does not contain all the elements and attributes found in the [DBC XML Format Technical Reference](https://bportaluri.com/wp-content/downloads/docs/DBC_XML_Format_Reference.pdf), but feel free to contribute with the project.

## Features

This code-snippets extension helps you write DBC files faster!

|                     Prefix | Action                                                                        |
| -------------------------: | ----------------------------------------------------------------------------- |
|        `create_dbc_file →` | Creates DBC file **Template**                                                 |
|           `define_table →` | Creates a database table.                                                     |
|                `attrdef →` | Adds an attribute. Used with **add_attributes/define_table**.                 |
|            `attr_sameas →` | Adds an attribute using **SAMEAS**. Used with **add_attributes/define_table**.|
|        `drop_attributes →` | Drops an attribute according with its name.                                   |
|       `modify_attribute →` | Modifies an attribute from an existing object/table.                          |
|         `add_attributes →` | Adds new attributes to an existing object/table.                              |
|    `create_relationship →` | Creates a Maximo relationship.                                                |
|             `aln_domain →` | Adds/Modifies an **ALN** domain.                                              |
|           `alnvalueinfo →` | Adds an **ALN** domain value.                                                 |
|           `table_domain →` | Adds/Modifies a **TABLE** domain.                                             |
|         `synonym_domain →` | Adds/Modifies a **SYNONYM** domain.                                           |
|           `synonymvalue →` | Adds a **SYNONYM** domain value.                                              |
|           `cross_domain →` | Adds/Modifies a **CROSSOVER** domain.                                         |
|     `crossovervalueinfo →` | Adds a **CROSSOVER** domain value.                                            |
|              `free_form →` | Adds session for SQL statements.                                              |
|          `sql_free_form →` | Adds sql element to **free_form**.                                            |
|          `add_sigoption →` | Creates sigoption.                                                            |
|         `drop_sigoption →` | Drops sigoption.                                                              |
|              `add_index →` | Adds/Modifies an index.                                                       |
|           `set_property →` | Set a value to an existent property.                                          |
|           `add_property →` | Add a system property to be configured through the UI.                        |
|             `create_app →` | Creates an Maximo application.                                                |


## Requirements

To enable the snippets, change the `Language Mode` to `XML`.

## Contribution

Contributions are what make the open source community an incredible place to learn, inspire, and create. Any contribution you make will be **greatly appreciated**.

1. Fork the project
2. Create a Branch for your Feature (`git checkout -b feature/AmazingFeature`)
3. Add your changes (`git add .`)
4. Commit your changes (`git commit -m 'Adding an awesome Feature!`)
5. Push the Branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

## Release Notes

### 1.0.0

Initial release of `maximo-dbc-snippets`.
