*Path*

| Key         | Name         | Type    |
|-------------|--------------|---------|
| Foreign Key | owner        | int     |
| Primary Key | path_id      | int     |

*User*

| Key         | Name      | Type   |
|-------------|-----------|--------|
| Foreign Key | owns_path | int    |
| Primary Key | user_id   | int    |
| N/A         | username  | varchar |
| N/A         | password  | varchar |

*File*

| Key         | Name         | Type    |
|-------------|--------------|---------|
| Foreign Key | owned_by     | int     |
| Primary Key | file_id      | int     |
| N/A         | file_location | varchar |
| N/A         | file_size    | int     |


