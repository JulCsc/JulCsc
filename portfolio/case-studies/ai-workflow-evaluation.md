# Case study: AI workflow evaluation and user acceptance testing

I helped evaluate AI tools and workflows for documentation teams, bringing the perspective of someone who would actually use them while managing a busy content portfolio.

My work ranged from co-leading user acceptance testing (UAT) for PR Autoreview in GitHub to piloting AI-assisted review and content-quality tools in Power BI and Fabric docs. I organized testing, built supporting automation, tested scenarios myself, and used real repository conditions to help identify where an approach was useful and where it needed more work.

The common thread was making experimentation practical: give people a clear way to test, capture what happened, and turn the findings into something other teams could use.

## Co-leading PR Autoreview UAT

PR Autoreview introduced automated and AI-assisted checks into the documentation pull request (PR) review process. I served as the **content UAT co-lead**, as well as a tester, helping organize the work from setup through execution.

I proposed the Azure DevOps work-item structure, and I scripted the creation of test-case work items. This gave testers a consistent way to find their assignments and track progress, with clear responsibilities across the testing effort. And it made work item creation a breeze for me.

My contributions included:

- Supporting a team testing **163 scenarios across 10 test repositories**.
- Personally completing **31 scenarios across my two assigned repositories**.
- Automating test-case work-item creation to reduce manual setup.
- Contributing to the automation of **17 new PR Reviewer rules**.
- Helping testers understand their assignments and keeping the work organized through execution.

The structure mattered as much as the testing itself. A distributed group could spend its time evaluating the tool instead of figuring out how to participate.

> “You ensured work items were created, tracked, and that everyone clearly understood their roles and responsibilities.”
>
> — Kym P., Senior Technical Program Manager

## Tooling that carried forward

I adapted a shared PowerShell script to create Azure DevOps test-case work items for our UAT. Another team later reused my adapted version to generate 200 test scenarios in a few minutes.

That was a meaningful outcome for me: the work made one UAT easier to run and gave another team a faster starting point.

> “The testers commented how organized the project was and how productive they could be without fuss.”
>
> — Jason H.

## Piloting AI-assisted PR review

I also piloted AI-assisted PR review workflows in the Power BI documentation repository.

Introducing the workflow required more than showing that AI could produce review comments. There was skepticism about its usefulness, and adoption depended on showing how it helped with actual publishing work.

I piloted the workflows and shared review-speed findings with stakeholders. The work demonstrated faster reviews and reduced manual effort, helping build confidence in using AI within the review process.

This reinforced a practical lesson: adoption gets easier when people can see how a tool improves their own work.

## Creating prompts and skills

I created reusable prompts for recurring documentation tasks, including freshness reviews, document analysis, orphan detection, automated fixes, and monthly what’s-new (ie, feature release) updates. I later converted the what’s-new prompt into a reusable Copilot skill. These gave me a consistent starting point for repeat work while keeping review and editorial judgment with me.

## Evaluating content-quality workflows

My evaluation work also covered tools intended to improve documentation quality, reduce duplication, and support AI consumption. Here is a selection of the many initiatives I contributed to.

| Initiative | My involvement |
| --- | --- |
| **Duplicate and conflicting content detection** | Co-led a Learn Hackathon project and tested an AI agent to identify duplicate or conflicting content across Learn documentation. Later contributed to AI-assisted similarity-detection pilots using real repository conditions. |
| **MOSAIC** | Participated in an AI- and quality-focused pilot, contributing findings to broader content hygiene and validation work. |
| **AI Response Quality** | Participated in evaluation work alongside other AI and content-quality pilots. Focused on retrieval-augmented generation (RAG) and semantic chunking, as well as efficient Markdown formatting. |
| **CURATIOR** | Participated in a content-quality pilot, contributing to the development of repeatable hygiene and validation practices. |
| **CFIT UAT sessions** | Participated in cross-team UAT of emerging content tools and workflows. |
| **Stale UI image detection** | Led testing for a Hackathon project that progressed an AI tool for identifying outdated or incorrect UI images and descriptions in docs, then updating the docs as needed. |
| **CDA Cortex** | Participated in the UAT and pilot, tested shared skills in my day-to-day workflow, and submitted feature requests. Using the tools against actual documentation work helped surface practical needs beyond a demonstration or isolated test scenario. |

Across these efforts, I brought experience with a large, active documentation portfolio: overlapping articles, maintenance demands, contributor workflows, and the practical limits of manual review. I documented findings and helped turn useful approaches into workflows that vendors and peer writers could participate in.

## What this work demonstrates

I connected hands-on testing with the operational work needed to make evaluation productive:

- **UAT coordination:** organizing scenarios, assignments, and tracking across multiple repositories.
- **Practical automation:** reducing test setup effort and creating tooling another team could reuse.
- **Workflow evaluation:** testing AI in the context of real documentation and publishing work.
- **Adoption support:** sharing findings that helped stakeholders assess the value of a new approach.
- **Iteration:** recognizing when false positives and manual effort justified changing direction.

I enjoy this part of the work: trying something new, finding where it breaks down, and helping turn the useful parts into a process people can keep using.

# Responsible AI

I gave AI assistants explicit boundaries: verify source material before making changes, leave unrelated sections alone, and stop when required evidence was unavailable. I reviewed generated changes and questioned unsupported claims, treating the assistant’s output as something to check rather than an authoritative source.

## Manager feedback

> “My new team (post reorg) borrowed your ADO creation script and leveraged it for their current project, creating 200 test scenarios in a few minutes.”
>
> — Jason H. · April 2025

> “When duplicate content remediation stalled due to false positives, she pivoted quickly, joining a Hackathon to co-develop an AI agent for automated similarity detection, laying the groundwork for scalable solutions.”
>
> — Kate F. · October 2025
___
*AI helped draft and refine this page. I reviewed and edited the final content and am responsible for its accuracy. The experiences and contributions described are my own.*
