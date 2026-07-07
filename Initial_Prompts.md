Hello DocuMakerAI,

I am attaching a set of process discovery artefacts for an automation candidate. These artefacts may include screenshots, process notes, existing documentation, sample files, and other supporting material.

Please analyse all the information provided and generate a .docx Process Design Document using the approved PDD template available in your knowledge base.


These instructions define DocuMakerAI’s required behaviour. Follow them as the primary operating rules for the agent.

Use the PDD template in the Knowledge section as the source of truth for the final document structure.

Do not treat the PDD template as process knowledge. The template defines structure only. Process-specific content must come from the user, uploaded artefacts, or confirmed conversation context.

Hello DocuMakerAI,

I am attaching a set of process discovery artefacts for an automation candidate. These artefacts may include screenshots, process notes, existing documentation, sample files, and other supporting material.

Please analyse all the information provided and generate a document-ready Process Design Document using the approved PDD template available in your knowledge base.

The final output should be a Microsoft Word document where possible.

Please follow these rules:

1. Use the approved PDD template structure.
2. Populate all relevant PDD sections using the information provided.
3. Use the screenshots as evidence for the detailed process steps where relevant.
4. If possible, identify and crop the relevant screenshot regions for each step.
5. Generate a high-level process flow using Mermaid.
6. If possible, render the Mermaid diagram as an image and insert it into the PDD.
7. Do not invent missing information.
8. Mark missing or unclear information as “To be confirmed”.
9. After generating the draft, list the main open questions that need clarification.

Please create the best possible first draft of the PDD based on the artefacts attached.




I’ve been testing DocuMakerAI, my AI build that takes images, documents, and process artefacts, and uses them to populate a Word document template in a Process Design Document format.

I’ve run into a few issues that I’d like to brainstorm with you:

1. The agent is not populating the existing Word PDD template. It seems to be creating a new document with different formatting instead of using the approved template.
2. It is dumping the full PDD content into the chat, rather than focusing on generating the document output.
3. It is not generating the Mermaid process flow diagram.
4. It is not embedding the screenshots into the PDD. Instead, it only adds placeholders such as image filenames.

I suspect some of these may be platform/tooling limitations rather than prompt issues, so I’d really appreciate your input on the best way forward.

Would you be available for a short brainstorming call to discuss possible approaches?

Thanks,

