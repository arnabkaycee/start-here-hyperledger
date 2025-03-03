---
layout: default
title: indy-sdk
parent: Hyperledger
grand_parent: Pull Requests
has_children: false
permalink: /pull-requests/hyperledger/indy-sdk
---

# indy-sdk <span class="fs-3 right-align">[GitHub](https://github.com/hyperledger/indy-sdk){: .btn .mr-4 }</span>


<div>
    <table>
        <tr>
            <td>
                PR <a href="https://github.com/hyperledger/indy-sdk/pull/2402" class=".btn">#2402</a>
            </td>
            <td>
                <b>
                    Update Rusqlite to version 0.25.3
                </b>
            </td>
        </tr>
        <tr>
            <td>
                
            </td>
            <td>
                The current version of `rusqlite` (0.20.0) is transitively dependent on `linked-hash-map v0.5.3`, which contains a bug ([fixed](https://github.com/contain-rs/linked-hash-map/pull/106) in version `0.5.4`). This bug causes runtime panics due to uninitialized reference on wallet access since rust `1.48.0`. See [here](https://github.com/mehcode/config-rs/issues/158), [here](https://github.com/hyperledger/aries-vcx/pull/126), and [here](https://github.com/hyperledger/indy-sdk/pull/2311).

This PR updates version of rusqlite which fixes the bug (replicating the changes in #2311 with green DCO), as the latest version of rusqlite removes dependency on `linked-hash-map`.

Signed-off-by: Miroslav Kovar <miroslavkovar@protonmail.com>
            </td>
        </tr>
    </table>
    <div class="right-align">
        Created At 2021-06-22 14:32:50 +0000 UTC
    </div>
</div>

