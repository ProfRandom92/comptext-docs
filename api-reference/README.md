# CompText API Reference

## REST API

Base URL: `http://localhost:8000`

### Endpoints

#### Search Commands
```
GET /api/search?query=docker
```

#### List Modules
```
GET /api/modules
```

#### Get Command
```
GET /api/command/{id}
```

Full API docs: [MCP Server API](https://github.com/ProfRandom92/comptext-mcp-server/blob/main/docs/API.md)

## MCP Protocol

### Tools

- `list_modules` - List all modules
- `list_commands` - List commands in module
- `search` - Search commands
- `get_command` - Get specific command

Full MCP docs: [MCP Integration](../mcp-integration/README.md)
