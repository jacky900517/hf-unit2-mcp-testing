# HF Unit 2 MCP Testing

Personal coursework test repository for Playwright MCP and a multi-server workflow.

- Target: the publicly accessible [Tatung University course query](https://couquery.ttu.edu.tw/main/ListClassCourse.php).
- Test date: 2026-11-11 (Asia/Taipei).
- Playwright MCP performs browser actions and captures evidence.
- Filesystem MCP writes course results to CSV and a Markdown test summary, then reads them back for verification.
- GitHub MCP creates the issue documenting the observed navigation problem.

This repository is a personal testing exercise and is not affiliated with Tatung University. The issue records observed public-page behavior and a proposed usability expectation, not an official specification or a confirmed backend diagnosis. No account login, access-control bypass or high-volume requests were attempted.

## Evidence

- [Original screenshot](evidence/entry-timeout.png)
- [Accessibility snapshot excerpt](evidence/entry-timeout-snapshot.txt)

Detailed protocol logs and the coursework report are provided in the assignment's local evidence archive.
