# Pitch Deck Setup Guide

This guide will help you set up the Slidev pitch deck and MCP server for Terpedia, LLC.

## Prerequisites

- Node.js (v18 or higher)
- npm or yarn

## Setup Steps

### 1. Install Slidev Dependencies

```bash
cd pitch-deck
npm install
```

### 2. Install MCP Server Dependencies

```bash
cd ../slidev-mcp
npm install
```

### 3. Configure MCP Server

The MCP server needs to be added to your MCP client configuration. The exact location depends on your MCP client:

**For Cursor:**
- Configuration is typically in your Cursor settings
- Add the server configuration pointing to the `slidev-mcp/src/index.js` file

**Example configuration:**
```json
{
  "mcpServers": {
    "slidev": {
      "command": "node",
      "args": [
        "/Users/danielmcshan/GitHub/TerpediaLLC/slidev-mcp/src/index.js"
      ]
    }
  }
}
```

**Note:** Update the path to match your actual project location.

### 4. Start Development

To work on your pitch deck:

```bash
cd pitch-deck
npm run dev
```

This will start the Slidev development server, typically at `http://localhost:3030`.

## Using the MCP Server

Once configured, you can use the MCP server to manage your presentation through your AI assistant. Available operations include:

- **List presentations** - See all available presentations
- **Read presentation** - View the full content of a presentation
- **Create presentation** - Create a new Slidev presentation
- **Add slide** - Add a new slide to an existing presentation
- **Update slide** - Modify an existing slide
- **Delete slide** - Remove a slide from a presentation
- **Get slide count** - Count the total number of slides

## Building the Presentation

To create a production build:

```bash
cd pitch-deck
npm run build
```

To export as PDF:

```bash
npm run export
```

## Project Structure

```
TerpediaLLC/
├── pitch-deck/          # Slidev presentation
│   ├── slides.md        # Main presentation file
│   ├── package.json     # Slidev dependencies
│   └── README.md        # Presentation documentation
└── slidev-mcp/          # MCP server for managing presentations
    ├── src/
    │   └── index.js     # MCP server implementation
    ├── package.json     # MCP server dependencies
    └── README.md        # MCP server documentation
```

## Next Steps

1. Customize the initial slides in `pitch-deck/slides.md`
2. Add your company content, mission, vision, and value proposition
3. Use the MCP server to iteratively build out your pitch deck
4. Export the final presentation when ready
