### Hi, I'm Fabrizio 👋

Backend engineer working on **APIs, document pipelines and RAG systems**.
MSc in Computer Science and Engineering at Politecnico di Milano, thesis on multi-facet retrieval for RAG.

**At Efebia (Dec 2024 – Mar 2026)**
- **Document AI / RAG backend**: Fastify + PostgreSQL/pgvector APIs with resource-level authorization, permission-aware retrieval, LangChain/OpenAI answers streamed over SSE with incremental source citations.
- **Async ingestion**: S3 → SQS → parsing/indexing workers (Docling, OCR, batch embeddings), DLQs, concurrency limits, AI usage/cost tracking, generated DOCX reports and TTS overviews.
- **Multimodal image service**: refactored a FastAPI service with typed provider clients (Gemini, Bedrock, Ximilar), fallbacks, asyncio concurrency control.
- **Typed backend tooling**: shared Fastify + Zod v4 library with inferred request/response types, compile-time reply constraints and validated SSE streams.
- **Infra**: AWS CDK (SQS, S3, SES, CloudFront, ECS/Fargate, IAM), Docker, GitHub Actions.

**Research**: [MultiFacetBench](https://github.com/fabriziopagnozzi/thesis-code) is a deterministic benchmark showing that a relevant retrieval set can still be incomplete. It compares top-k, MMR and Facility-Location over 4 embedding models and 656 experimental cells, with facet-aware metrics and a held-out test split.

**Stack I use daily**
`TypeScript` `Node.js` `Fastify` `Zod` `Python` `FastAPI` `Pydantic` `PostgreSQL` `pgvector` `Drizzle` `LangChain` `OpenAI` `AWS` `Docker` `Polars` `DuckDB` `Sentence Transformers`

📫 [LinkedIn](https://www.linkedin.com/in/fabrizio-pagnozzi-a68396335) · fabriziopagnozzi00@gmail.com · Milan, Italy
