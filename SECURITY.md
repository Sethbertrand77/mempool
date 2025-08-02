# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
Navigation Menu

/
mempool




Code
Issues274









Releases
 
v3.2.0
v3.2.0


Compare
 mononaut released this Apr 7
· 305 commits to master since this release
 v3.2.0 
 74dde85 
The Mempool Open Source Project® v3.2.0
  Highlights
Support for v3 transactions
Support for anchor outputs
New UTXO bubble chart on the address page
DATUM miner tags
Tags to identify runestone messages and inscriptions
Package broadcast
Stratum job data visualizations
Taproot multisig labels
Transaction & PSBT preview feature
Address poisoning detection
And more!
Changelog
Bump tslib from 2.6.2 to 2.7.0 in /frontend by @dependabot in #5475
Bump axios from 1.7.2 to 1.7.4 in /backend by @dependabot in #5467
[docs] update READMEs to newer node version by @mononaut in #5477
Bump elliptic from 6.5.4 to 6.5.7 in /frontend by @dependabot in #5468
v1 audit improvements by @mononaut in #5460
Persist mempool block visualization between pages by @mononaut in #5445
Bump cypress from 13.13.0 to 13.14.0 in /frontend by @dependabot in #5484
Make v3 transactions standard by @mononaut in #5489
Add support for anchor output type by @mononaut in #5493
Allow OP_0 in multisig scripts by @vostrnad in #5494
Update about page enterprise sponsors by @orangesurf in #5487
[faucet] add missing error message for suspicious twitter accounts by @nymkappa in #5497
hotfix option 1 for axios breaking change to unix sockets by @mononaut in #5502
Revert "hotfix option 1 for axios breaking change to unix sockets" by @wiz in #5504
hotfix option 2 for axios breaking change to unix sockets by @mononaut in #5503
Ineligible transaction link to accelerator FAQ by @natsoni in #5478
respect json Accept header in API error responses by @mononaut in #5472
Add amount mode selector to footer by @natsoni in #5464
Bump micromatch from 4.0.4 to 4.0.8 in /frontend by @dependabot in #5476
RBF tracking fixes by @mononaut in #5479
Handle paginated acceleration results by @mononaut in #5485
Reset acceleration flow state when leaving transaction by @natsoni in #5481
Hide accelerator panel if tx gets accelerated on another session by @natsoni in #5482
Avoid brief display of accelerator checkout on already accelerated txs by @natsoni in #5471
Fix accelerator logo in trademark policy on mobile by @natsoni in #5531
Show http error in pizza tracker by @natsoni in #5528
Fix off-by-one error in multi-pool eta calculation by @mononaut in #5530
Fix mobile routing to tx push and test pages by @natsoni in #5526
[accelerator] avoid duplicated accel request with double click by @nymkappa in #5513
Pizza tracker: don't show ETA on replaced tx by @natsoni in #5527
Fix ETA calculation error by @natsoni in #5535
Wrap pool logos in timeline tooltip by @natsoni in #5536
Only fetch 1m mining stats by @natsoni in #5534
Add utxo chart to address page by @mononaut in #5525
Fix critical calculator inputmode by @softsimon in #5524
"Be your own explorer" on non official mempool instance by @natsoni in #5529
Add logos to blocks and test transactions pages by @natsoni in #5533
Fix accelerations list page navigation on first load by @natsoni in #5532
Remove difficulty adjustment block offset by @natsoni in #5486
Bump body-parser and express in /frontend by @dependabot in #5522
Bump serve-static and express in /backend by @dependabot in #5521
Fix race condition between accelerations and block audit api calls by @natsoni in #5538
optimize processNewBlocks by @mononaut in #5451
[accelerator] make bid boost graph bar min height taller by @nymkappa in #5491
only use sats, not sat by @softsimon in #5437
Update accelerating pie chart in real time by @mononaut in #5541
Bump esbuild from 0.23.0 to 0.24.0 in /frontend by @dependabot in #5542
Don't show negative timespans on timeline by @natsoni in #5545
utxo chart optimization by @mononaut in #5548
address utxo chart color by
