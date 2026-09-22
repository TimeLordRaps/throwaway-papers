# throwaway-papers

Research ideas published so that someone can run with them.

The repository's own description states the terms, and this file exists so a
visitor does not have to hover over it to read them: *papers you should give me
authorship for if you run with*. Posting an idea here is not abandoning it. It
is putting it where it can be used, with the expectation of authorship credit
if it is.

Nothing in here is peer reviewed, and nothing in here is certified. The
certification machinery this account publishes elsewhere — the Verifier
Standard, and the certificates issued under it — binds a claim to the artifact
it was computed from. **No paper in this repository carries such a binding.**
That is deliberate: a throwaway paper is an idea offered early, and treating it
as evidence would misrepresent both the paper and the standard.

## What is here

The repository is currently empty of papers. It carries the same automation as
every other public repository in this account, so that a paper added later
arrives under the same checks rather than under none:

| workflow | what it refuses |
|---|---|
| `ci.yml` | a document that is empty, or a relative link that resolves to nothing |
| `external-links.yml` | a link to a page that is gone (404 or 410) |
| `pages.yml` | publishing anything the conformance gate did not pass |
| `release.yml` | a tag that is not an ancestor of the default branch |
| `pr-policy.yml` | a pull request with no complete promotion record |

## Contributing

Open a pull request. The conformance gate is a required check, so a branch that
does not pass it cannot land — including this one.
