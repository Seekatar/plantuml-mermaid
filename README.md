# PlantUML and Mermaid Diagrams

Diagrams as code can save you alot of time when creating diagram for communication. You can spend your time thinking about the problem, instead of trying to get the lines of the sequence diagram are crooked, or the boxes lined up just right.

When I first saw someone create a sequence diagram in five minutes with PlantUML after I'd been spending hours fighting VISIO, I was sold. Most diagrams you create are made to help you and your colleagues understand the the problem or a solution. They need to be clear, but do they need to be ready for an art gallery? I think not.

After using PlantUML for a while, I stumbled upon Mermaid diagrams, which are very similar.

## PlantUML

[PlantUML](https://plantuml.com/) has been around since 2009 and is written in Java. It uses its own DSL to describe various diagrams. Even though the name has UML in it, it can do more than just UML diagrams.

This is the first one I used and am most familiar with. It seems easier to learn and use, but has the downside not being supported in repo sites like GitHub, and Azure DevOps Wikis.

## Mermaid

[Mermaid](https://mermaid-js.github.io/mermaid/#/) is written in JavaScript and is newer than PlantUML (first README.md commit was in 2014). Its syntax is very similar to PlantUML, and uses more JavaScript-like syntax and CSS for styling.

## Basic Features

Both have very good documentation with many examples of each diagram type its supports.

| Feature      | PlantUML                                                                      | Mermaid                                                                                 |
| ------------ | ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| Platform     | Java                                                                          | JavaScript                                                                              |
| Extensions   | [VS Code](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml) | [VS Code](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid) |
| Rendering    | Java local, or a server, or extension                                         | Extensions or browser                                                                   |
| Markdown     | GitLab                                                                        | Azure DevOps, GitHub, GitLab                                                            |
| Image Export | Extension, CLI                                                                | Extension, CLI                                                                          |
| Styling      | Pretty easy, nested files                                                     | More JS-like in diagram                                                                 |
| Themes       | Many builtin, and on Internet                                                 | Few built-in. Uses CSS                                                                  |
| Sandbox      | [PlantUML Online Server](https://www.plantuml.com/plantuml/uml/)              | [Mermaid Live](https://mermaid.live/)                                                   |

## Diagrams

| Diagram                                          | PlantUML | Mermaid          |
| ------------------------------------------------ | -------- | ---------------- |
| Activity/FlowChart                               | Y        | Y                |
| Archimate                                        | Y        |                  |
| Class                                            | Y        | Y                |
| C4                                               | Y        | Y                |
| Component                                        | Y        |                  |
| Deployment                                       | Y        |                  |
| Ditaa                                            | Y        |                  |
| Entity Relationship (IE/ER)                      | Y        | Y (experimental) |
| Gantt                                            | Y        | Y                |
| Git                                              |          | Y                |
| JSON data                                        | Y        |                  |
| Mathematic with AsciiMath or JLaTeXMath notation | Y        |                  |
| MindMap                                          | Y        |                  |
| Network (nwdiag)                                 | Y        |                  |
| Object                                           | Y        |                  |
| Pie chart                                        | Y        |                  | Y |
| Requirement                                      |          | Y                |
| Salt (Wireframe)                                 | Y        |                  |
| Sequence                                         | Y        |                  |
| Specification and Description Language (SDL)     | Y        |                  |
| State                                            | Y        | Y                |
| Timing                                           | Y        |                  |
| Use Case                                         | Y        |                  |
| User Journey                                     |          | Y                |
| Work Breakdown Structure (WBS)                   | Y        |                  |
| YAML data                                        | Y        |                  |

### PlantUML Icon and Macro Libraries

| Name         | Descriptio                                                       |
| ------------ | ---------------------------------------------------------------- |
| archimate    | ArchiMate PlantUML macros                                        |
| aws          | Amazon AWS icons                                                 |
| azure        | Microsoft Azure icons                                            |
| c4           | Macros for C4 diagrams                                           |
| cloudinsight | Cloudinsight icons                                               |
| cloudogu     | Cloudogu services macros, etc.                                   |
| elastic      | Elastic icons                                                    |
| kubernetes   | Kubernetes icons                                                 |
| logos        | Gil Barbara’s logos                                              |
| material     | Material style icons from Google and other artists.              |
| office       | Monochrome icons                                                 |
| osa          | Open Security Architecture icons                                 |
| tupadr3      | Several libraries of icons (including Devicons and Font Awesome) |

## Links

- [PlantUML](https://plantuml.com/)
- [PlantUML Online Server](https://www.plantuml.com/plantuml/uml/SyfFKj2rKt3CoKnELR1Io4ZDoSa70000)
- [PlantUML Themes](https://the-lum.github.io/puml-themes-gallery/)
- [PlantUML on GitHub](https://github.com/plantuml/plantuml)
- [PlantUML and C4](https://github.com/plantuml-stdlib/C4-PlantUML)
- [Mermaid](https://mermaid-js.github.io/mermaid/#/)
- [Mermaid Live](https://mermaid.live/edit#pako:eNpVkM-KwkAMxl8l5OSCfYEeBG3Vi6Cgt46H0InOIPOHdMoibd99p5aF3ZyS7_t9IWTANmjGEp9C0cCtVh5ybZvKiO2So-4ORbEZj5zABc_vEXarY4DOhBitf34t_G6GoBpOM8aQjPWvabGqT_7seYS6OVFMId7_OrfvMMK-sReT1_93jHBOHZoHlQ8qWhKoSD4IrtGxOLI6nz7MisJk2LHCMrea5KVQ-SlzfdSUeK9tCoJlkp7XSH0K17dvf-eFqS3lL7hFnH4ABg5bBA)
- [Mermaid Themes](https://mermaid-js.github.io/mermaid/#/directives?id=directive-examples)
- [Mermaid on GitHub](https://github.com/mermaid-js/mermaid)

### Comparisions

- [Diagrams as Code: Plantuml or Mermaid](https://wyssmann.com/blog/2021/03/diagrams-as-code-plantuml-or-mermaid/) he likes PlantUML better since Mermaid slows rendering (vs. PlantUML generated image).
- [Generating documentation as code with mermaid and PlantUML](https://ruleoftech.com/2018/generating-documentation-as-code-with-mermaid-and-plantuml) doesn't have a strong opinion.
