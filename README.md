### Samarateja Reddy Gutta

Backend and applied-AI engineer. M.S. Computer Science, George Washington University.
Washington, D.C. · open to remote.

I like the parts of a system where the interesting decision is not *how* to build
something but *which failure you are willing to accept*. Most of what's here is
built around one of those.

---

**[Distributed Object Storage Platform](https://github.com/Samarateja0118/distributed-object-storage)** · Java 21 · Spring Boot · gRPC · PostgreSQL

An S3-inspired object store across seven services. Objects are split into
content-addressed chunks on a data plane while their metadata lives in a separate
relational control plane — so no transaction spans an object's two halves, and
every write has to choose which inconsistency it leaves behind. Twelve architecture
decision records argue those choices out, costs included.

**[Access AI Gateway](https://github.com/Samarateja0118/access-ai-gateway)** · TypeScript · PostgreSQL · LLM security

An LLM gateway built around indirect prompt injection: the payload isn't typed into
the chat, it's stored in a door's name by someone with permission to name doors, and
reaches the model weeks later through a tool result. Input filtering never sees it.
Tenant scope resolves before the query, tool output is scanned as untrusted input,
and an adversarial suite proves it holds — including base64, homoglyphs, and
instructions split across two rows.

**[TradeWatch](https://tradewatch-hazel.vercel.app)** · Python · FastAPI · React · [live](https://tradewatch-hazel.vercel.app)

A daily briefing agent for India–US trade policy, and a dashboard over it. A
deterministic prefilter drops routine notices at zero marginal cost so model calls
are spent only where they earn their keep. The design problem is that a language
model is an unreliable component inside a pipeline that has to be dependable, so
every stage degrades instead of failing.

**[Movie Catalog Service](https://github.com/Samarateja0118/movie-mcp-server)** · Python · MCP · FastAPI · [live](https://movie-finder-demo.vercel.app)

One domain layer behind two independent transports — an MCP server for assistants
and an HTTP API for the web demo — so caching, retries and failure behaviour are
identical whichever door a caller comes through.

---

Things I care about, visible in the code rather than claimed here: tests that assert
a decision rather than a line, comments that explain why instead of restating what,
and a written record of the reasoning behind anything non-obvious.

[Portfolio](https://portfolio-ten-psi-ml0tn08w0t.vercel.app) · [LinkedIn](https://www.linkedin.com/in/samaratejareddygutta/) · samarateja18@gmail.com
