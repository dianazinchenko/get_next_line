# get_next_line
## Overview
The get_next_line project revolves around creating a function that retrieves a line from a file descriptor.
Through this project, I explored the utilization of static variables, enhancing my understanding of file manipulation and resource management in C programming.

## Usage
1. Clone the repository
   ```
   git clone git@github.com:dianazinchenko/get_next_line.git
   
2. Go inside the project folder and compile the library
   ```bash
   cd get_next_line
   
3. Compile the mandatory or bonus files
   ```bash
   [Mandatory] cc -Wall -Wextra -Werror main.c get_next_line.c get_next_line_utils.c
   [Bonus] cc -Wall -Wextra -Werror main.c get_next_line_bonus.c get_next_line_utils_bonus.c
   
4. Specify the BUFFER_SIZE to overwrite the default BUFFER_SIZE
> get_next_line should be able to compile with and without the -D BUFFER_SIZE=[SIZE] flag.</br>
   ```bash
   [Mandatory] cc -Wall -Wextra -Werror -D BUFFER_SIZE=[SIZE] main.c get_next_line.c get_next_line_utils.c
   [Bonus] cc -Wall -Wextra -Werror -D BUFFER_SIZE=[SIZE] main.c get_next_line_bonus.c get_next_line_utils_bonus.c

5.
