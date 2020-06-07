# Trello CLI

## Installation

Download binary
https://github.com/tkms0106/trello/releases

## Setup

1. Get your API key
https://trello.com/app-key
1. Then generate your token
1. Create `~/.trello.yaml`

```yaml
key: YOUR_API_KEY
token: YOUR_TOKEN
memberid: YOUR_MEMBER_ID # Also called 'user name'
```

## Usage

```
trello add 'Card Name' 'Description' -b 'Board Name' -l 'List Name'
```

`Description` is optional.

It is recommended that you define aliases for frequently used board and list.
