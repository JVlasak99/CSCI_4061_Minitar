# CSCI_4061_Minitar
- Implementation of a "mini" version of the tar archive utility
- Includes a Comamand Line Interface (CLI) for each operation
- To use the CLI, follow the following format: `./a.out <operation> -f <archive_name> <file_name_1> ... <file_name_n)`
- Operations                                                                                                                     
  - `-c`: Create a new archive file with the name `<archive_name>` containing `<file_name_i>` files
  - `-a`: Add more files `<file_name_i>` to `<archive_name>`
  - `-t`: Print names of the files contained in `<archive_name>`
  - `-u`: Update files `<file_name_i>` contained in `<archive_name>`
  - `-x`: Extract files in `<archive_name>` to the current working directory
