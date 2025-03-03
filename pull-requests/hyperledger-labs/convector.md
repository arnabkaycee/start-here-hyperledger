---
layout: default
title: convector
parent: Hyperledger Labs
grand_parent: Pull Requests
has_children: false
permalink: /pull-requests/hyperledger-labs/convector
---

# convector <span class="fs-3 right-align">[GitHub](https://github.com/hyperledger-labs/convector){: .btn .mr-4 }</span>


<div>
    <table>
        <tr>
            <td>
                PR <a href="https://github.com/hyperledger-labs/convector/pull/150" class=".btn">#150</a>
            </td>
            <td>
                <b>
                    build(deps-dev): bump grpc from 1.12.2 to 1.24.9
                </b>
            </td>
        </tr>
        <tr>
            <td>
                <span class="chip">dependencies</span>
            </td>
            <td>
                Bumps [grpc](https://github.com/grpc/grpc-node) from 1.12.2 to 1.24.9.
<details>
<summary>Release notes</summary>
<p><em>Sourced from <a href="https://github.com/grpc/grpc-node/releases">grpc's releases</a>.</em></p>
<blockquote>
<h2>Node gRPC v1.24.7</h2>
<ul>
<li>Log just serialization and deserialization errors on the server, instead of logging all errors with the code <code>INTERNAL</code> (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1750">#1750</a>)</li>
<li>Replace the <code>instanceof Function</code> check to make it work properly in certain environments (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1759">#1759</a> contributed by <a href="https://github.com/zereraz"><code>@​zereraz</code></a>)</li>
</ul>
<h2>Node gRPC v1.24.6</h2>
<ul>
<li>Fix prototype pollution possibility in loadPackageDefinition (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1701">#1701</a>)</li>
</ul>
<h2>Node gRPC v1.24.5</h2>
<ul>
<li>Add support for Electron 11 and newer versions of Electron 10 (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1684">#1684</a>)</li>
</ul>
<h2>Node gRPC v1.24.4</h2>
<ul>
<li>Add support for Electron 10 and newer minor versions of Electron 8 and 9 (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1615">#1615</a>)</li>
<li>Add a note in the README stating the latest supported versions of Node and Electron (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1615">#1615</a>)</li>
<li>Prevent prototype pollution in <code>loadPackageDefinition</code> (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1606">#1606</a>)</li>
<li>Add <code>ResponseType</code> to <code>ServerWritableStream</code> type definition for compatibility with <code>@grpc/grpc-js</code> (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1590">#1590</a> contributed by <a href="https://github.com/badsyntax"><code>@​badsyntax</code></a>)</li>
<li>Add <code>methodTypes</code> enum to type definition (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1496">#1496</a> contributed by <a href="https://github.com/jncr"><code>@​jncr</code></a>)</li>
</ul>
<h2>grpc 1.24.3</h2>
<ul>
<li>Add support for S390x (originally <a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1230">#1230</a> contributed by <a href="https://github.com/shahidhs-ibm"><code>@​shahidhs-ibm</code></a>)</li>
<li>Add support for Node 14, and Electron 7, 8, and 9</li>
<li>Unbundle the dependency on <code>node-pre-gyp</code> (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1371">#1371</a> contributed by <a href="https://github.com/Naktibalda"><code>@​Naktibalda</code></a>)</li>
</ul>
<p><strong>Known Issues</strong>:</p>
<ul>
<li><a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1407">#1407</a> may cause errors when running on Node 14</li>
</ul>
<h2>Node gRPC v1.24.2</h2>
<ul>
<li>Publish some missing files to fix building from source (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1060">#1060</a>)</li>
<li>Add support for Node 13 and Electron 7 (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/1097">#1097</a>)</li>
</ul>
<p><a href="https://github.com/grpc/grpc/releases/tag/v1.24.0">C core release notes</a></p>
<h2>Node gRPC v1.23.4</h2>
<p><a href="https://github.com/grpc/grpc/releases/tag/v1.23.1">C core release notes</a></p>
<h2>Node gRPC v1.23.3</h2>
<h2>Node gRPC v1.23.0</h2>
<ul>
<li>Fix Channel argument validation error messages (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/932">#932</a> contributed by <a href="https://github.com/clehene"><code>@​clehene</code></a>)</li>
<li>Add support for Electron 4.2 and 6.0 (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/939">#939</a> contributed by <a href="https://github.com/CapOM"><code>@​CapOM</code></a>, <a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/990">#990</a>)</li>
<li>Fix typos in TypeScript types file (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/972">#972</a>, <a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/983">#983</a> contributed by <a href="https://github.com/esilkensen"><code>@​esilkensen</code></a>)</li>
</ul>
<p><a href="https://github.com/grpc/grpc/releases/tag/v1.23.0">C core release notes</a></p>
<h2>Node gRPC v1.23.1</h2>
<ul>
<li>Remove dependency on <code>@types/protobufjs</code> (<a href="https://github-redirect.dependabot.com/grpc/grpc-node/issues/999">#999</a>)</li>
</ul>
<h2>Node gRPC v1.23.2</h2>
<!-- raw HTML omitted -->
</blockquote>
<p>... (truncated)</p>
</details>
<details>
<summary>Commits</summary>
<ul>
<li>See full diff in <a href="https://github.com/grpc/grpc-node/commits">compare view</a></li>
</ul>
</details>
<br />


[![Dependabot compatibility score](https://dependabot-badges.githubapp.com/badges/compatibility_score?dependency-name=grpc&package-manager=npm_and_yarn&previous-version=1.12.2&new-version=1.24.9)](https://docs.github.com/en/github/managing-security-vulnerabilities/about-dependabot-security-updates#about-compatibility-scores)

Dependabot will resolve any conflicts with this PR as long as you don't alter it yourself. You can also trigger a rebase manually by commenting `@dependabot rebase`.

[//]: # (dependabot-automerge-start)
[//]: # (dependabot-automerge-end)

---

<details>
<summary>Dependabot commands and options</summary>
<br />

You can trigger Dependabot actions by commenting on this PR:
- `@dependabot rebase` will rebase this PR
- `@dependabot recreate` will recreate this PR, overwriting any edits that have been made to it
- `@dependabot merge` will merge this PR after your CI passes on it
- `@dependabot squash and merge` will squash and merge this PR after your CI passes on it
- `@dependabot cancel merge` will cancel a previously requested merge and block automerging
- `@dependabot reopen` will reopen this PR if it is closed
- `@dependabot close` will close this PR and stop Dependabot recreating it. You can achieve the same result by closing it manually
- `@dependabot ignore this major version` will close this PR and stop Dependabot creating any more for this major version (unless you reopen the PR or upgrade to it yourself)
- `@dependabot ignore this minor version` will close this PR and stop Dependabot creating any more for this minor version (unless you reopen the PR or upgrade to it yourself)
- `@dependabot ignore this dependency` will close this PR and stop Dependabot creating any more for this dependency (unless you reopen the PR or upgrade to it yourself)
- `@dependabot use these labels` will set the current labels as the default for future PRs for this repo and language
- `@dependabot use these reviewers` will set the current reviewers as the default for future PRs for this repo and language
- `@dependabot use these assignees` will set the current assignees as the default for future PRs for this repo and language
- `@dependabot use this milestone` will set the current milestone as the default for future PRs for this repo and language

You can disable automated security fix PRs for this repo from the [Security Alerts page](https://github.com/hyperledger-labs/convector/network/alerts).

</details>
            </td>
        </tr>
    </table>
    <div class="right-align">
        Created At 2021-05-12 00:42:46 +0000 UTC
    </div>
</div>

