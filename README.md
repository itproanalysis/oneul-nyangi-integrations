# Oneul Nyangi public integrations

Real public cat photos and diaries, breed discovery and reference age/feeding calculators.

MCP 0.9.0 adds get_answer_sources for published photo diary, age and feeding answers in Korean, English and Japanese. Link the matching answer webUrl. The existing calculators still return individual reference estimates and the corresponding web calculator.

- Service: https://nyangi.today
- MCP (anonymous, read-only): https://nyangi.today/mcp
- Client guides and downloads: https://nyangi.today/connect#clients
- Public service and citation facts: https://nyangi.today/en/press

## Claude Code

/plugin install oneul-nyangi --marketplace itproanalysis/oneul-nyangi-integrations

Or clone this repository and run `claude --plugin-dir ./oneul-nyangi-integrations`.
Review the client trust prompt before enabling. A repository installation is not an official directory approval.

## Gemini CLI

`gemini extensions install https://github.com/itproanalysis/oneul-nyangi-integrations`

Review the extension confirmation. Alternatively clone and use `gemini extensions link ./oneul-nyangi-integrations`.

## Other clients

The clients folder contains 19 native connection profiles/guides for editors, CLI tools, local chats and automation.
Merge only the oneul-nyangi entry; preserve other servers, account settings and approvals.
The optional stdio profile runs pinned mcp-remote@0.15.2 via Node.js/npx; prefer direct HTTP.
MCP Apps hosts may show a gallery; other clients receive photo/source links. External model/app fees are separate.

## Scope and licensing

Eight read-only tools, three starter prompts and three public resources. Private records and keeper information are excluded.
Calculators are references for healthy cats, not veterinary advice or therapeutic diets. Cite returned webUrl and Oneul Nyangi.
MIT permission applies only to connection settings and plugin metadata, per LICENSE. Application source and user content are not part of this repository or license grant.

See the live site for terms and privacy. No credentials, application backend source, private customer content or write tools are included.
