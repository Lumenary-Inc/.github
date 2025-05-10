

# Solar - Build real software exceedingly fast

> Build apps with many AI agents on a canvas.

## TL;DR;

In Solar, you build full-stack apps alongside many LLMs on a spatial canvas, where you can freely remix features and try design variants. Bring your own backend, or Solar can generate full Python & Postgres stacks with builtin auth, in minutes.

## Demo // explore the canvas yourself

https://github.com/Lumenary-Inc/solar-assets/blob/develop/guides.fixBugs.gif?raw=true

### More demos

3D Rubik's cube solver
- Explore the canvas

X-ray medical classifier using vision transformers
- Deployed
- Explore the canvas


## Problem

You can only send one message at a time using Lovable / Bolt / v0 / Replit. If the LLM does a bad job, you have to “revert” the change and start over. Most of your time is spent waiting and hoping.

Eventually, your app starts to come together, but you lack a clear picture of what exactly is happening. Where are my tables? What are my API endpoints? How is the authentication done, and is it secure? Wait, does this app even work?

## Solution

Solar combines the best parts of Figma, Retool, and AI app builders.

Solar’s AI agents generate apps directly on a multiplayer spatial canvas, with database tables, Python business logic, and frontend pages all in one place. You can generate dozens of variants, work on different features concurrently, and simply discard failed attempts.

Our code generation is powered in part by our proprietary build system. This system ingests LLM-generated business logic and deterministically generates the necessary database schemas, servers, SDK clients, and infrastructure. The result is a far more reliable and secure experience.

### Features

Backend
- Make FastAPI backends with access to Python’s rich package ecosystem (we’ve zero-shotted ML backends with Pytorch)
- We provide authentication, database (Postgres), and object storage in every project at no additional cost. Single-click deploy.
- Import your existing databases, lakehouses, and authentication.

Frontend
- Generate 3x different design variations from just a single prompt
- Easily clone and compare versions, like in Figma
- Make the backend in Solar, or connect to any backend that uses OpenAPI. We’ll generate the client SDK.

## Ask

We ask you to try building your most ambitious idea on Solar. It could be a side project, an internal tool, or a new prototype for your company.

If your friends are using Lovable / Bolt / v0 and aren’t impressed, shoot them https://try.solar. We want to help people ship software that actually works.

Finally, we love seeing user creations, so send us apps you’re proud of.