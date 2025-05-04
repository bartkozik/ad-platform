# AI-Driven Ad Creative Platform – Template Development Module (NDA Project)

**Note:** This is an ongoing project under NDA. This README is provided for portfolio purposes only – no source code is included.

## 📣 Project Overview

This platform enables users to generate and personalize marketing creatives based on a system of pre-built design templates. Leveraging AI, the system adapts these templates to target audiences, channels, and messaging strategies. The tool is used internally and externally to streamline scalable ad content creation.

## 👨‍💻 My Role

I joined the team at an advanced stage of development and took over ownership of the **template creation system** — a core component of the personalization engine.

Although I joined the project at a late stage, I quickly integrated into the team's Agile flow in Jira and began working closely with backend developers, designers, and QA. Template development required detailed coordination with the design team (Sketch), BE engineers, and testers, particularly around rendering logic and layout constraints. I also participated in planning sessions to prioritize template work and ensure compatibility across the personalization engine. My time management and clear communication helped streamline this highly collaborative workflow.

Key responsibilities:

- Creating and maintaining **customizable ad templates** used in the rendering and AI-personalization pipeline
- Implementing logic to define and position elements like text, images, and shapes in a **template-driven canvas**
- Working with constraints such as character limits, multi-line rendering, dynamic positioning, and responsive scaling
- Validating templates against business and layout rules using custom test harnesses and Vitest-based tools
- Collaborating with backend and AI teams to ensure the correct integration between templates and personalization logic

## 🛠️ Tech Stack

### Core Technologies
- **React 19** + **TypeScript**
- **Vite** as the build and dev server
- **React Hook Form** + **Zod** – form configuration and validation
- **@dnd-kit** – drag & drop interface for positioning elements
- **uuid**, **qs**, **clsx**, **dayjs**

### Specialized Tools
- **opentype.js** – font rendering and character measurement
- **pixelmatch** – visual regression testing of rendered templates
- **morphdom** – DOM diffing for efficient canvas updates
- **i18next** + **ICU formatting** – multilingual content support

### Testing & Validation
- **Vitest** – unit and visual snapshot tests
- **Playwright** – E2E testing (including canvas rendering and interactions)
- **Custom CLI tools** – for validating color usage and template definitions

## 🎨 Design & Integration Context

- Templates are built in close collaboration with designers and AI engineers
- Each template must support dynamic content injection and transformation
- The design system must handle a variety of formats, locales, and content densities

## 🚀 Status

Development is ongoing, with weekly iterations and cross-team collaboration. My contributions ensure the consistency and reliability of the creative foundation used throughout the platform.

---

_Want to dive deeper into how dynamic ad templates are structured and validated in a React-based system? Let’s talk!_
