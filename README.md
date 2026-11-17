# Vadym Maniuk

I build automation for data collection, research, and review. I use Python, SQL, REST APIs, and MCP to connect systems, and I use LLMs in workflows where a person reviews the result before it is published.

## Selected projects

| Project | What I built and verified |
| --- | --- |
| **[Tallinn Jobs](https://github.com/VadymManiuk/tallinn-jobs)** | A Python and SQLite catalog that refreshes listings from six sources. It groups duplicates, keeps links to the original postings, and retains existing records when a source returns incomplete results. |
| **Momentum Desk** | An LLM research workflow that gathers sources, flags drafts with weak evidence, and queues drafts for human review. I ran it on a Linux VPS and checked that collection resumed after a restart. |
| **[Telegram Research Connector](https://github.com/VadymManiuk/telegram-research-connector)** | A read-only Python MCP connector with bounded requests. I verified the MCP handshake and retrieval of a live post. |
| **ArcInvoice** | An invoice approval and reconciliation prototype. In a simulated payment flow, I verified that the wrong amount was rejected and concurrent retries recorded one receipt. |

## Public code

- [ArcTask](https://github.com/VadymManiuk/ArcTask) documents how an AI worker processes jobs, stores its state, and prepares deliverables for review.
- [Whale-Flow](https://github.com/VadymManiuk/Whale-Flow) shows how a monitoring service collects events, persists them, and produces alerts.
