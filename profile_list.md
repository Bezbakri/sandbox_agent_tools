filesystem_read_access: Can look at file paths, can read files, cannot write files
filesystem_write_access: Can look at file paths, cannot read files, can write files
filesystem_full_access: Can look at file paths, can read files, can write files
api_tool_access: Can access the api key for a tool, can make requests to only the URL for the tool
http_access: Can make requests to fixed list of URLs, cannot make requests to URLs outside that list.
http_and_filesystem_read_access: Can make requests to fixed list of URLs, cannot make requests to URLs outside that list, can look at file paths, can read files, cannot write files
http_and_filesystem_write_access: Can make requests to fixed list of URLs, cannot make requests to URLs outside that list, can look at file paths, cannot read files, can write files
http_and_filesystem_full_access: Can make requests to fixed list of URLs, cannot make requests to URLs outside that list, can look at file paths, can read files, can write files
database_read_access: Read access to fixed set of database files, cannot write to database files
database_read_write_access: Read access to fixed set of database files, can write to database files, cannot create or delete database files
database_full_access: Read access to fixed set of database files, can write to database files, can create and delete database files