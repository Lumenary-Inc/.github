# Launch BF: Solar — Build real software exceedingly fast

> Ship in minutes with “Figma + Cursor + Retool”


## TLDR

Build full-stack apps alongside many LLMs on a canvas, where you can freely remix features and try design variants. We provide infra (auth, DBs, storage, servers), or you can integrate with your own. Deploy in a click.

![xxxx-ezgif com-video-to-gif-converter (3)](https://github.com/user-attachments/assets/fdae4101-8c86-4dc5-b3f2-f3c547483b08)

![appGenerationComplete-lbf-3](https://github.com/user-attachments/assets/718b7634-5cd0-4628-b663-5b2d40da7183)

## Problem

We’re a team of four engineers who’ve used nearly every AI-powered app builder. Projects started off great, but we found ourselves in an endless loop of “revert, and try again.” Most of our time was spent waiting and hoping as the LLM made changes one-at-a-time.

Even when the app seemed to work, it was unclear what were real features versus frontend demoware. We lacked an understanding of the architecture, dataflow, and what vulnerabilities were left open. It felt like these platforms had prioritized making neat frontends and bolted on real functionality as an afterthought.


## Solution

We loved three things:
- Figma’s flexibility — work on many designs with many people
- Cursor’s power — write production code with LLMs
- Retool’s safety — ship apps that you know work

We combined those to make Solar.

Solar’s AI agents work alongside you on a multiplayer canvas. You can generate **dozens of variants** and work on different features **concurrently**.

Solar’s AI generates database tables, API endpoints, and frontend pages so you can visualize and understand your app’s **data flow**.

**Solar makes apps production-worthy** by combining LLM-generated code with deterministic code generation for databases, services, and authentication. This makes your apps maintainable and deployable past the MVP.

## Demo

We built a full-stack MP3 player in under an hour — [Explore the canvas yourself](https://solarapp.dev/fdd48e04-12c9-450e-9511-0da2d9ce5772/canvas)

https://youtu.be/d70ugaMXRxo

### Features

Backend
- Make Python / FastAPI backends with access to Python’s rich package ecosystem ([we’ve first-shotted ML backends with Pytorch](https://solarapp.dev/f5e264d5-8b9a-4faf-92c0-e39e979596f8/canvas))
- We provide authentication, database (Postgres), and object storage in every project at no additional cost. Single-click deploy.
- Import your existing databases, lakehouses, and authentication.

Frontend
- Generate 3x different design variations from just a single prompt
- Easily clone and compare versions, like in Figma
- Make the backend in Solar, or connect to any backend that uses OpenAPI. We’ll generate the client SDK.


## Ask

Sign up at [solarapp.dev](https://solarapp.dev) and try building an app. We have a very generous free tier for early sign ups – limited spots for now, but we are excited to share with YC.

Build your most ambitious idea on Solar. We’ve had folks build:
- Internal tools
- Customer-facing product
- Personal software
- Multiplayer games

If you build something awesome, send it to us! If it didn’t work as well, we’d love to know why. [Here’s our Discord](https://discord.com/channels/1362654659881205830/1362654660455960688).
