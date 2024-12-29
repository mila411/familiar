# Familiar

`Familiar` is a simple key-value store implemented in Rust. It can be operated from the command line, and supports data types such as strings, integers, booleans, maps, lists, and sets.

## Installation

Clone this project and build it using Cargo.

```sh
git clone https://github.com/mila411/familiar.git
cd familiar
cargo build
```

## Usage

Run Familiar using the following command.

`cargo run`

After running, enter the following commands from the command line to operate.

### List of Commands

- `set <key> <value>`: Sets a value for a key.
- `get <key>`: Gets the value of the specified key.
- `delete <key>`: Deletes the specified key.
- `update <key> <new_value>`: Updates the value of an existing key.
- `list`: Lists all the keys currently in the store.
- `history`: Displays a history of commands executed.
- `help`: Displays available commands and their descriptions.
- `exit`: Exits the program.

### Examples

```sh
Enter command:
set name “Alice”
Set key ‘name’ with value ‘String(”Alice“)’

Enter command:
get name
Value for key ‘name’: ‘String(”Alice")’

Enter command:
list
Keys: name

Enter command:
history
Command History:
1: set name “Alice”
2: get name
3: list

Enter command:
exit
Exiting...
```

## Testing

Run the tests using the following command.

`cargo test`

## License

This project is released under the MIT license. Please refer to the LICENSE file for details.
