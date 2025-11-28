Mini Quarto Project with Mermaid-ELK diagram
I am a very beginner user, looking for help with the  ELK layout for Mermaid. When rendering this mini-project, the Mermaid diagram does appear in index.html. However, the diagram does not use the ELK layout; specifically, the mergeEdges setting is not shown. 
The Mermaid diagram is defined in mermaid-elk-sample.qmd, and it is injected into index.qmd using an 'include' directive.
When I look at the rendered index.html using VSC live server, the mermaid diagram does not have ELK layout. When inspecting index.html with devtools console mermaid.mermaidAPI.getConfig(), I see some ELK settings, but I don't know or understand enough to figure out whether they are correct.
