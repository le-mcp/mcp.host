### MCP HOST Demo

simple mcp host demo

### Configuring LLM providers to use

#### OpenAI

To use the OpenAI API, you need to set your `OPENAI_API_KEY` key in the `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key
MODEL="gpt-4.1"
```

#### GitHub Models

To use the GitHub models, you need to set your `GITHUB_TOKEN` in the `.env` file:

```env
GITHUB_TOKEN=your_github_token
MODEL="openai/gpt-4.1"
```

### Running

```bash
npm install
npm start
```
