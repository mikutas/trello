# Trello CLI

## Installation

Download binary
https://github.com/mikutas/trello/releases

## Setup

1. Get your API key
https://trello.com/app-key
1. Then generate your token
1. Create `~/.trello.yaml`

```yaml
key: YOUR_API_KEY
token: YOUR_TOKEN
memberid: YOUR_MEMBER_ID # Also called 'user name'
board: BOARD_NAME # Default board
```

## Usage

`Description` is optional.

```
# Specify the board by using -b or --board and the list by using -l or --list.
trello add 'Card Name' 'Description' -b 'Board Name' -l 'List Name'

# List can be specified by using -i or --index option (zero-based, from the left).
trello add 'Card Name' -b 'Board Name' -i 1

# If you want to use default board and list(index=0, left end),
# just input the card name (and optional description).
trello add 'Card Name'
```

It is recommended that you define aliases for frequently used board and list.
Or you can define default board in your config file.
