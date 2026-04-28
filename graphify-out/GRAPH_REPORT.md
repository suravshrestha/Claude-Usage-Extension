# Graph Report - Claude-Usage-Extension  (2026-04-28)

## Corpus Check
- 16 files · ~33,247 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 262 nodes · 609 edges · 14 communities detected
- Extraction: 68% EXTRACTED · 32% INFERRED · 0% AMBIGUOUS · INFERRED: 193 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]

## God Nodes (most connected - your core abstractions)
1. `LengthUI` - 23 edges
2. `UsageUI` - 22 edges
3. `Log()` - 20 edges
4. `Log()` - 18 edges
5. `processResponse()` - 16 edges
6. `ClaudeAPI` - 15 edges
7. `UsageData` - 14 edges
8. `requestData()` - 13 edges
9. `ConversationData` - 10 edges
10. `checkResetNotifications()` - 9 edges

## Surprising Connections (you probably didn't know these)
- `UsageUI` --conceptually_related_to--> `Claude.ai chat with injected length/cost/cache/quota UI`  [INFERRED]
  content-components/usage_ui.js → ui_screenshot.png
- `ClaudeAPI` --conceptually_related_to--> `Token counting (Anthropic API vs gpt-tokenizer)`  [INFERRED]
  bg-components/claude-api.js → README.md
- `LengthUI` --conceptually_related_to--> `Usage sources: files, projects, prefs, history, tools, MCPs`  [INFERRED]
  content-components/length_ui.js → README.md
- `LengthUI` --conceptually_related_to--> `Claude.ai chat with injected length/cost/cache/quota UI`  [INFERRED]
  content-components/length_ui.js → ui_screenshot.png
- `LengthUI` --conceptually_related_to--> `Patch notes: Firefox containers, peak hours TZ`  [INFERRED]
  content-components/length_ui.js → update_patchnotes.txt

## Hyperedges (group relationships)
- **End-user install path (README + manifests + icons)** — readme_claude_usage_tracker, icon128_manifest_asset, icon512_manifest_asset, readme_manifest_v3_stack [INFERRED 0.78]

## Communities

### Community 0 - "Community 0"
Cohesion: 0.08
Nodes (10): getResetTimeHTML(), isMobileView(), mountToAnchor(), ProgressBar, setupTooltip(), isPeakHours(), UsageData, Claude QoL cross-promotion badge (+2 more)

### Community 1 - "Community 1"
Cohesion: 0.09
Nodes (15): handleMessageFromContent(), clearAlarm(), createNotification(), getAlarm(), Log(), UsageSection, addContainerFetchListener(), getStorageValue() (+7 more)

### Community 2 - "Community 2"
Cohesion: 0.13
Nodes (10): getConversationId(), getCurrentModel(), getCurrentModelVersion(), Log(), waitForElement(), ConversationData, LengthUI, Patch notes: Firefox containers, peak hours TZ (+2 more)

### Community 3 - "Community 3"
Cohesion: 0.13
Nodes (6): ClaudeAPI, ConversationAPI, Log(), MessageAPI, Token counting (Anthropic API vs gpt-tokenizer), containerFetch()

### Community 4 - "Community 4"
Cohesion: 0.13
Nodes (9): Ko-fi donation button asset, ButtonNotificationCard, DonationNotificationCard, FloatingCard, makeDraggable(), openDebugOverlay(), RateNotificationCard, SettingsCard (+1 more)

### Community 5 - "Community 5"
Cohesion: 0.2
Nodes (20): checkResetNotifications(), debugLogMessageCost(), electronUsagePoll(), handleAlarm(), interceptedRequest(), interceptedResponse(), Log(), logError() (+12 more)

### Community 6 - "Community 6"
Cohesion: 0.12
Nodes (17): getActiveOrgId(), getChatLengthCostAnchor(), getChatLengthCostStatLineFallbackAnchor(), getChatTitleBeforeMenuAnchor(), getChatTitleBeforeShareAnchor(), initExtension(), injectStyles(), isCodePage() (+9 more)

### Community 7 - "Community 7"
Cohesion: 0.17
Nodes (6): clearLogs(), enablePermanentDebug(), showLogs(), toggleDebugMode(), updateDebugStatus(), FloatingCardsUI

### Community 9 - "Community 9"
Cohesion: 1.0
Nodes (2): Interactive force-directed graph HTML export, GRAPH_REPORT god nodes and surprising connections

### Community 13 - "Community 13"
Cohesion: 1.0
Nodes (1): Manifest V3 + webRequest + polyfill stack

### Community 14 - "Community 14"
Cohesion: 1.0
Nodes (1): Popup: help text for reload / authorize on claude.ai

### Community 15 - "Community 15"
Cohesion: 1.0
Nodes (1): Debug logs page (toolbar / context menu)

### Community 16 - "Community 16"
Cohesion: 1.0
Nodes (1): Extension icon 128px

### Community 17 - "Community 17"
Cohesion: 1.0
Nodes (1): Extension icon 512px

## Knowledge Gaps
- **14 isolated node(s):** `Token counting (Anthropic API vs gpt-tokenizer)`, `Usage sources: files, projects, prefs, history, tools, MCPs`, `Manifest V3 + webRequest + polyfill stack`, `Privacy: tokens, messages, reset time, org ID only`, `Firebase sync for cross-device usage` (+9 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Community 9`** (2 nodes): `Interactive force-directed graph HTML export`, `GRAPH_REPORT god nodes and surprising connections`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 13`** (1 nodes): `Manifest V3 + webRequest + polyfill stack`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 14`** (1 nodes): `Popup: help text for reload / authorize on claude.ai`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 15`** (1 nodes): `Debug logs page (toolbar / context menu)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 16`** (1 nodes): `Extension icon 128px`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 17`** (1 nodes): `Extension icon 512px`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Log()` connect `Community 2` to `Community 0`, `Community 1`, `Community 6`, `Community 7`?**
  _High betweenness centrality (0.159) - this node is a cross-community bridge._
- **Why does `processResponse()` connect `Community 5` to `Community 1`, `Community 2`, `Community 3`, `Community 7`?**
  _High betweenness centrality (0.079) - this node is a cross-community bridge._
- **Why does `LengthUI` connect `Community 2` to `Community 0`, `Community 6`?**
  _High betweenness centrality (0.063) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `LengthUI` (e.g. with `Usage sources: files, projects, prefs, history, tools, MCPs` and `Claude.ai chat with injected length/cost/cache/quota UI`) actually correct?**
  _`LengthUI` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `UsageUI` (e.g. with `Claude Usage Tracker Extension` and `Claude.ai chat with injected length/cost/cache/quota UI`) actually correct?**
  _`UsageUI` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Are the 14 inferred relationships involving `Log()` (e.g. with `initElectronReceiver()` and `.init()`) actually correct?**
  _`Log()` has 14 INFERRED edges - model-reasoned connections that need verification._
- **Are the 9 inferred relationships involving `processResponse()` (e.g. with `.get()` and `.getUsageData()`) actually correct?**
  _`processResponse()` has 9 INFERRED edges - model-reasoned connections that need verification._