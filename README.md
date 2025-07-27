# minishell 

## 📚 Project Description

This project consists of creating a minimalistic shell that can:

- Parse and execute user commands
- Handle redirections (`<`, `>`, `>>`)
- Handle pipes (`|`)
- Support environment variable expansion (`$`)
- Manage built-in commands
- Implement basic signal handling (`ctrl + C`, `ctrl + \`, `ctrl + D`)
- Execute commands with correct file descriptor handling and child processes


## 📦 Dependencies

- Language: C
- Compilation: `cc` with flags `-Wall -Wextra -Werror -lreadline`


## 📁 Project Structure

```
ft_minishell/
│
├── minishell.c        # Main file
├── execution
├── includes
│   └── parsing
├── libft
│   └── ft_fprintf
├── parsing
│   ├── __media
│   ├── ast
│   ├── env
│   ├── expansion
│   │   └── wildcards
│   ├── pre_ast
│   ├── syntx_check
│   └── tokenize
├── Makefile
└── README.md
```

## ⚙️ How to Use

### 1. Clone the repository

```bash
git clone https://github.com/LawKmu/shell-imzine.git
cd ft_minishell
```

### 2. Compile

```bash
make
```

### 3. Run

```bash
./minishell
```
You'll see a prompt where you can start typing commands



## 🧠 Concepts Learned
- Process creation with `fork`, `execve`, and `wait`


