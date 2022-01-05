[How to generate scaffold with Infyom Laravel Generator](https://www.youtube.com/watch?v=g6Rp98_0inQ&list=PL0wCC44AhrC3JHzcB5qmjYkm70OaoKegg&index=4&t=81s)

author_id integer selectTable:users:name:name,id

otras opciones
:api \$MODEL_NAME$ --paginate=10  
:scaffold \$MODEL_NAME --datatables=true  
:scaffold \$MODEL_NAME --views=index,create,edit,show  
:scaffold \$MODEL_NAME --factory  
:scaffold \$MODEL_NAME --seeder    
:scaffold \$MODEL_NAME --fieldsFile=filename_from_model_schema_directory_OR_path_from_base_directory_OR_absolute_file_path
:scaffold \$MODEL_NAME --tableName=custom_table_name  
:scaffold \$MODEL_NAME --fromTable --tableName=$TABLE_NAME
:scaffold \$MODEL_NAME --fromTable --tableName=$TABLE_NAME --connection=connectionName  
:api_scaffold Post --skip=routes,migration,model  
:scaffold \$MODEL_NAME --primary=custom_name_id
:scaffold \$MODEL_NAME --plural=AuthorBooks
:scaffold \$MODEL_NAME --prefix=admin
:scaffold \$MODEL_NAME --ignoreFields=geo_location,last_login
:scaffold \$MODEL_NAME --forceMigrate
:api \$MODEL_NAME --resources=true