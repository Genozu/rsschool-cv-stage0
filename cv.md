# **Nikita Pankov**

## ***MY CONTACTS***
    -addres: 141, Barykina Street, Gomel, Repablic of Belarus
    -phone: +375 29 370 24 19
    -email: genozu@yandex.by

## ***SKILLS***
    - programming language: python
    - version control system: Git
    - development tools: Visual Studio Code

### _Code example_
```
def table_verification(connection, name_table, data_column):
    
    name = f"'{name_table}'"
    query = "SELECT name FROM sqlite_master WHERE type='table';"
    result = execute_read_query(connection, query)
    print(result)
    
    if (name_table,) in result:
        print(f'Таблица {name_table} присутсвует!')
    else:
        print(f'Таблица {name_table} отсутсвует!')
               
        create = create_table(name, data_column)
        execute_query(connection, create)
```

## ***EDUCATION***
    + Creative shool (school 19, Gomel, Repablic of Belarus)
    + Civil engeneer (Belarusian State University of Transport 2011-2021)
    + Python basics (courses hexlet october-december 2022)
    + HTML and CSS basic (courses HTML Academy 2021)

## ***LANGUAGES***
    * English - elementary (A1)
    * Russian - native