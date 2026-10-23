# NLP Internship Agent

NLP Internship Agent is a Codex and AI Agent–based project for finding and managing
internship opportunities in France in NLP, large language models (LLMs), and
generative AI. It organizes job discovery and application preparation in a private
workspace, with the agent helping you review roles and maintain a record of your search.

## What it supports

- Discover roles across configured job boards, employer career pages, and other observed sources.
- Run targeted, incremental searches and resume eligible work from saved checkpoints.
- Detect exact and possible duplicates across sources, with uncertain matches left for review.
- Keep job records and discovery history in persistent local files and databases.
- Save and review job descriptions (JDs), and track application progress in a local dashboard.
- Export job data in CSV format for further review.
- Run a daily search cycle through a supported local agent scheduler, when configured.

Source coverage and results depend on configured sources, access rules, and the behavior
of each platform. Blocked or incomplete searches are recorded for review. The project
does not promise unrestricted access to job sites.

## How it works

The project is packaged as a Codex Skill that guides the agent through search, review,
and record keeping. The Skill and code live in the repository; personal information,
job records, and application materials belong in a separate private workspace on your
machine. The Skill does not include that personal workspace.

Scheduling is optional and depends on the agent platform and local environment. This
project helps manage the search workflow; it does not claim fully autonomous
job applications.

## Acknowledgements

Built upon [Useless-LinkedIn](https://github.com/ziyuan-404/Useless-LinkedIn), whose
author and upstream project provided the foundation for this work. This repository
adapts and extends that project; its original work is not claimed as an independent
implementation.

The upstream project and additional third-party components retain their respective
credits and licenses. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for details,
and [LICENSE](LICENSE) for this repository's license.
