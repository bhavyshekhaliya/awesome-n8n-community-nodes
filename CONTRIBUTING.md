# Contributing to Awesome n8n Community Nodes

Thanks for helping people discover useful, maintainable n8n community nodes. This repository is a curated directory, so every entry should make package discovery easier without implying that the package has been security-audited.

## Inclusion criteria

A submission should:

- Be installable as an n8n community node package from the public npm registry.
- Have a clear public package page and, preferably, a public source repository.
- If no public GitHub repository can be verified, use `-` in the Source column.
- Provide a meaningful integration, trigger, AI capability, data service, or workflow utility.
- Include enough documentation for users to understand its purpose and basic setup.
- Add value beyond an existing entry; avoid duplicate packages for the same integration unless they have materially different capabilities.
- Be described accurately, with links that work without an account or paid subscription.

Do not submit:

- Built-in n8n nodes or packages that only repackage n8n's core nodes.
- Private, abandoned, unmaintained, or uninstallable packages.
- Malware, credential-stealing behavior, unexplained telemetry, or packages with a serious unresolved security concern.
- Unofficial API wrappers presented as provider-maintained integrations.
- Affiliate, referral, tracking, or URL-shortener links.
- A package solely because it is popular; popularity is not a quality or safety guarantee.

## Adding an entry

1. Choose the closest existing category.
2. Add one row in alphabetical order by integration or package name.
3. Link the exact npm package page and the public source repository.
4. Write a concise, factual description based on the package documentation.
5. Use `official` only when the package is published by the integrated service or a clearly verified organization. Use `community` for independent maintainers.
6. Add a small number of useful tags that describe the primary use case.
7. Check that the Markdown table renders correctly and that every changed link works.

Use this row format:

```markdown
| [`package-name`](https://www.npmjs.com/package/package-name) | Short, factual description. | [GitHub](https://github.com/owner/repository) | `community` `category` |
```

## Pull requests

Keep each pull request focused. In the description, include:

- The package name and the exact npm URL.
- The source repository and evidence that it is the correct project.
- The integration's official website, when applicable.
- The package version and date you checked the links.
- Any compatibility caveat, known limitation, or security consideration a user should see before installing.

For corrections or removals, explain what changed: a broken link, ownership change, package withdrawal, security issue, duplicate entry, or inaccurate description. Include a replacement source when one exists.

By contributing, you agree that your changes to this directory are dedicated under [CC0 1.0 Universal](LICENSE). The linked packages, source repositories, trademarks, and documentation remain subject to their respective owners' terms.
