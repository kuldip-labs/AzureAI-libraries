## Microsoft offers a highly integrated ecosystem of Azure AI Libraries and SDKs managed primarily under the Microsoft Azure AI Foundry platform. These libraries are available across standard enterprise languages including Python, .NET (C#), JavaScript, and Java.

### Core Generative AI & Agent SDKs
 * azure-ai-projects (Microsoft Foundry SDK): The primary unified library used to create, manage, and scale AI Agents and orchestration workloads. It lets you connect to your AI project, deploy LLMs/SLMs, build hosted agents, and handle custom tooling.
 * azure-ai-agents: A specific client library focusing purely on developing autonomous agents leveraging the Azure AI Agents Service ecosystem.
 * azure-ai-inference: A unified API client allowing developers to call and compare various foundational models (such as Meta, Mistral, and Cohere) deployed via Foundry serverless API endpoints or GitHub Models.
 * azure-ai-evaluation: Built specifically for evaluating Generative AI systems, providing automated metrics to measure quality, performance, and safety.

 ### Azure AI vision Library
 * azure-cognitiveservices-vision-computervision: The azure-cognitiveservices-vision-computervision library is the legacy, deprecated Azure SDK for Python used to interact with the older Azure Computer Vision service (v3.x APIs)
 * azure-ai-vision-imageanalysis: Modern (latest lib) Instead of managing separate endpoints or methods for OCR (read), object detection, or tagging, a single client request can perform all analysis tasks at once

 ### Data, Search, & Grounding Libraries
 
 * azure-search-documents (Azure AI Search): Used to manage search indexes, upload datasets, and run vector, keyword, or hybrid search queries crucial for Retrieval-Augmented Generation (RAG).
 * azure-ai-contentunderstanding: Automatically processes and transforms unstructured multi-modal content (documents, audio, video, images) into AI-ready structured markdown.
 * azure-ai-documentintelligence: Specializes in extracting structured layouts, text, tables, and fields from formal documents like tax forms, receipts, and IDs.

 ### Specialized Ecosystem & Language Extensions
 * Azure OpenAI Client Library: Companion libraries that configure official OpenAI SDKs to safely point to enterprise Azure OpenAI Service endpoints.
 * Microsoft.Extensions.AI (.NET ecosystem): A standardized set of core C# abstractions (like IChatClient and IEmbeddingGenerator) allowing seamless switching between local and cloud model backends.
 * Teams AI Library: Used to seamlessly combine Azure AI Search capabilities with Microsoft Teams for building custom workspace co-pilots.