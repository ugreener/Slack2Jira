# Slack2Jira
MCP Hackathon - Slack -> Jira
This repo aims to create an integration layer between the existing Slack MCP and Jira MCP, enabling seamless ticket creation in Jira directly from Slack discussions. The solution will enhance team efficiency by allowing users to open Jira tickets without leaving Slack, while preserving discussion context within the tickets.

Define Use Case & Requirements: We will outline the business use case for integrating the Slack and Jira MCPs, focusing on automated ticket creation and context retention. Acceptance criteria and a clear Definition of Done (DoD) will be established. Comprehensive documentation, including workflows and data mapping, will be provided in Jira and the project’s README file.
Design Agent Solutions: Using LlamaStack, we will design agents to bridge the Slack and Jira MCPs. These agents will handle Slack message parsing, trigger detection (e.g., specific commands), and ticket creation in Jira by mapping Slack discussion data to Jira ticket fields(summary and description), ensuring efficient and accurate integration.
Fields to be filled in by the agent:
          - Summary

           - Description

           - Actual result

           - Expected result

          Fields to be filled in by QE person (or developer)

          - How reproducible

          - Steps to reproduce

In the future the agent will also

         - attach pictures/logs etc from the discussion to the Jira

         - check if a Jira is open for similar problem and provide this info in slack discussion

Deliver Functional Integration Layer: We will deliver a fully operational integration layer that connects the existing Slack MCP and Jira MCP. This layer will include all necessary tooling, API integrations, and database support to enable ticket creation, status syncing, and seamless data flow between Slack and Jira, preserving context like messages, users, and attachments.
