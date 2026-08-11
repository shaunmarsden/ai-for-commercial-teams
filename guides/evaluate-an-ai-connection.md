# Evaluate An AI Connection

Use this when someone wants to connect an AI tool to a CRM, document store, calendar, API, plugin, MCP server or another system.

The connection is not the capability. The useful, checked workflow is.

## Start With The Job

Do not begin with a directory of connectors. Begin with one ordinary job:

- prepare a call card from approved account information;
- organise approved notes into a handover summary;
- find a current public company fact for research; or
- turn a transcript into a draft list of actions.

Write down what a person does today, what would be easier and what must remain with the person responsible for the decision.

If the job is not clear, stop. A connection will only make an unclear process faster or more widely available.

## Map The Boundary

Before choosing a connection, record:

- what information it can read;
- what information it can write or send;
- whose account or credentials it uses;
- what data leaves the current system;
- where logs, prompts and outputs are retained;
- what happens when a permission or service is unavailable; and
- which actions require a human approval.

Use the [AI Connection Evaluation Card](../templates/ai-connection-evaluation.md) and run the [AI Connection Check](../checks/ai-connection-check.md).

## Choose The Smallest Useful Connection

Prefer the least powerful option that can test the job:

1. a local or manual export before a live connection;
2. read-only access before write access;
3. one narrow data source before a whole workspace;
4. one known workflow before general-purpose access; and
5. a human-reviewed draft before an automated action.

An MCP server is one way to expose tools and data to an AI client. A listing in a marketplace or registry tells you that a server has been published. It does not, on its own, prove that the server is safe, suitable or well maintained. Check the source, maintainer, permissions and current documentation yourself.

## Run A Fictional Test First

Use a fictional account, document or sales conversation before using normal work information. Ask the connection to do one bounded job and record:

- what it retrieved correctly;
- what it could not access;
- what it misunderstood;
- what it tried to change or send;
- what a person had to correct; and
- whether the result was easier to check than the current method.

Do not use customer, employer, personal or confidential information simply to make the test feel realistic.

## Decide What Happens Next

| Decision | Meaning | Next step |
| --- | --- | --- |
| Use carefully | The job is clear, the boundary is acceptable and the human check is practical | Document the method and name an owner |
| Test further | The idea is promising but evidence or permissions are incomplete | Run one more narrow test |
| Restrict | The connection is useful only with tighter data or action limits | Reduce scope and retest |
| Reject | The risk, friction or weak result outweighs the benefit | Record the reason and choose another route |

Do not turn a promising demonstration into a team standard after one successful run. Use the same experiment and review habits as any other AI method.

## Keep It Current

Connections change. Record the source, version or access date, owner and review date. Recheck the method when permissions, data sources, vendors or the underlying workflow change.
