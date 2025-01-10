# Browserbase Context

How to Persist a Cookie: Use Browserbase's context persistence feature to persist across multiple sessions.

# Getting Started

1. Clone this repository
2. Install dependencies: `npm install`
3. Create a `.env` file and add your Browserbase Project ID and API Key (accessible here: https://www.browserbase.com/settings)
4. Run: `tsc -w`
5. Run: `node dist/index.js`

### Prerequisites

- A Browserbase account with API access
- Node.js (v14 or higher recommended)

# Brief Overview of Script

- Creates a Browserbase context
- Starts a first browserbase session with this context
- Sets and verifies a cookie
- Closes the first session
- Starts a second browserbase session with this same context
- Verifies that the cookies persists between sessions
