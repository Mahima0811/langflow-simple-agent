# Workflow architecture

1. **Chat Input** receives a user's message.
2. **Agent** interprets the request and decides how to respond.
3. **Gemini language model** provides language-generation capability to the Agent.
4. **Web Search** can search for relevant information when the Agent chooses to use the tool.
5. **URL** can fetch page content when a URL is supplied and the tool is invoked.
6. **Chat Output** presents the final response.

## Implementation note
This document is based on the supplied screenshot. Exact component settings, tool behavior, model identifiers, credentials, and Langflow version must be verified in the actual Langflow project.
