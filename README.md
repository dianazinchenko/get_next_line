# get_next_line
## Overview
The get_next_line project revolves around creating a function that retrieves a line from a file descriptor.
Through this project, I explored the utilization of static variables, enhancing my understanding of file manipulation and resource management in C programming.

## Features
- **Efficient Line-by-Line Reading:** The get_next_line() function allows for efficient reading of text files or standard input, retrieving one line at a time.
- **Error Handling:** Returns NULL in case of errors or when there's nothing else to read.
- **Buffer Size Flexibility:** You can specify the buffer size using the -D BUFFER_SIZE=[SIZE] flag during compilation, providing flexibility and optimization options.
- **Compatibility with Different Buffer Sizes:** The function is designed to work effectively with various buffer sizes, ensuring functionality even with extreme values such as 1, 9999, or 10000000.

## Usage
1. Clone the repository
   ```
   git clone git@github.com:dianazinchenko/get_next_line.git
   ```
2. Go inside the project folder
   ```bash
   cd get_next_line
   ```
3. Compile the mandatory or bonus files
   ```bash
   [Mandatory] cc -Wall -Wextra -Werror main.c get_next_line.c get_next_line_utils.c
   [Bonus] cc -Wall -Wextra -Werror main.c get_next_line_bonus.c get_next_line_utils_bonus.c
   ```
4. Specify the BUFFER_SIZE to overwrite the default BUFFER_SIZE
> get_next_line should be able to compile with and without the -D BUFFER_SIZE=[SIZE] flag.</br>
   ```bash
   [Mandatory] cc -Wall -Wextra -Werror -D BUFFER_SIZE=[SIZE] main.c get_next_line.c get_next_line_utils.c
   [Bonus] cc -Wall -Wextra -Werror -D BUFFER_SIZE=[SIZE] main.c get_next_line_bonus.c get_next_line_utils_bonus.c
   ```
5. Execute with one or multiple file descriptor(s)
```bash
./a.out [text.txt]
./a.out [text1.txt] [text2.txt]
```
