
   <h1>Blog Generator Agent</h1>

  <p>
        Blog Generator Agent is a planning-based agentic system designed to generate
        structured, high-quality technical blogs using large language models combined
        with real-time web research. The primary goal of the system is to produce
        coherent, well-structured content while minimizing hallucinations and ensuring
        factual grounding through external evidence.
    </p>
    <p>
        The system leverages LangGraph to implement hierarchical planning, intelligent
        routing, and dynamic fan-out worker execution. Each blog is generated through
        a multi-stage pipeline where high-level outlines are planned first, followed
        by section-level content generation and state-based merging into a single,
        consistent final document.
    </p>
    <p>
        To improve reliability and factual accuracy, the agent integrates live web
        research using the Firecrawl API. This enables hybrid knowledge synthesis by
        combining LLM reasoning with up-to-date web data, structured evidence extraction,
        and citation-aware content generation.
    </p>
    <p>
        Google Gemini is used as the core language model for hierarchical planning,
        content generation, and automated diagram creation. The generated blogs
        include formatted sections, code blocks, citations, and AI-generated visuals,
        making the output suitable for technical documentation and educational content.
    </p>
    <p>
        The frontend is built using React to provide an interactive user interface,
        while the backend is implemented in Flask (Python) to manage agent execution,
        orchestration logic, and API communication between components.
    </p>

</body>
