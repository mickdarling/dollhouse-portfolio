{
  "id": "templates_session-context-transfer_2025-08-10T23-09-54-955Z",
  "type": "templates",
  "version": "1.0.0",
  "metadata": {
    "name": "session-context-transfer",
    "description": "templates submitted from local portfolio",
    "author": "mickdarling",
    "version": "1.0.0",
    "created": "2025-08-10T23:09:54.720Z",
    "modified": "2025-08-10T23:09:54.720Z",
    "tags": []
  },
  "content": "---\ncategory: general\ndescription: Handlebars template for generating context transfer files between sessions\nexamples: []\nincludes: []\nname: session-context-transfer\noutput_format: markdown\ntags: []\nusage_count: 0\nvariables: []\nversion: 1.0.0\n\n---\n\n# Session Context Transfer - {{main_topic}} - {{end_date}}\n\n## Session Metadata\n- **Original Session ID**: {{session_id}}\n- **Date Range**: {{start_date}} - {{end_date}}\n- **Duration**: {{duration}}\n- **Main Topic**: {{main_topic}}\n\n## Essential Context\n{{essential_background}}\n\n## Key Decisions Made\n{{#each decisions}}\n- **{{title}}**: {{rationale}} *({{timestamp}})*\n{{/each}}\n\n## Technical Specifications\n{{#if architecture}}\n**Architecture**: {{architecture}}\n{{/if}}\n{{#if implementation}}\n**Implementation Details**: {{implementation}}\n{{/if}}\n{{#if security}}\n**Security Considerations**: {{security}}\n{{/if}}\n\n## Elements Created/Modified\n{{#each elements}}\n- **{{type}}**: {{name}} - {{description}}\n{{/each}}\n\n## Current State\n- **Progress**: {{current_progress}}\n- **Next Priority**: {{next_priority}}\n- **Blockers**: {{blockers}}\n\n## For New Session\nTo continue this work, you need to know:\n{{continuation_context}}\n\n**Immediate next steps:**\n{{#each next_steps}}\n1. {{this}}\n{{/each}}\n\n## Conversation Summary\n{{conversation_flow}}\n\n## Hook System Implementation (If Applicable)\n{{#if hooks_discussed}}\n- **Hook Elements Created**: {{hook_elements}}\n- **Monitoring Patterns**: {{monitoring_patterns}}\n- **Reaction Strategies**: {{reaction_strategies}}\n- **Integration Points**: {{integration_points}}\n{{/if}}\n\n---\n*Generated as artifact by Session Notes Agent at {{generation_timestamp}}*"
}