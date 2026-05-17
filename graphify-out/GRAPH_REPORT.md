# Graph Report - Claude-Usage-Extension  (2026-05-17)

## Corpus Check
- 16 files · ~33,457 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 263 nodes · 551 edges · 15 communities detected
- Extraction: 76% EXTRACTED · 24% INFERRED · 0% AMBIGUOUS · INFERRED: 130 edges (avg confidence: 0.8)
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
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]

## God Nodes (most connected - your core abstractions)
1. `LengthUI` - 23 edges
2. `Log()` - 21 edges
3. `Log()` - 20 edges
4. `UsageUI` - 20 edges
5. `ClaudeAPI` - 15 edges
6. `UsageData` - 14 edges
7. `sendBackgroundMessage()` - 10 edges
8. `ConversationData` - 10 edges
9. `updateAllTabsWithUsage()` - 9 edges
10. `Log()` - 9 edges

## Surprising Connections (you probably didn't know these)
- `ClaudeAPI` --conceptually_related_to--> `Token counting (Anthropic API vs gpt-tokenizer)`  [INFERRED]
  bg-components/claude-api.js → README.md
- `LengthUI` --conceptually_related_to--> `Usage sources: files, projects, prefs, history, tools, MCPs`  [INFERRED]
  content-components/length_ui.js → README.md
- `LengthUI` --conceptually_related_to--> `Claude.ai chat with injected length/cost/cache/quota UI`  [INFERRED]
  content-components/length_ui.js → ui_screenshot.png
- `LengthUI` --conceptually_related_to--> `Patch notes: Firefox containers, peak hours TZ`  [INFERRED]
  content-components/length_ui.js → update_patchnotes.txt
- `checkResetNotifications()` --calls--> `createNotification()`  [INFERRED]
  background.js → bg-components/electron-compat.js

## Hyperedges (group relationships)
- **End-user install path (README + manifests + icons)** — readme_claude_usage_tracker, icon128_manifest_asset, icon512_manifest_asset, readme_manifest_v3_stack [INFERRED 0.78]

## Communities

### Community 0 - "Community 0"
Cohesion: 0.08
Nodes (20): addContainerFetchListener(), getStorageValue(), Log(), MessageHandlerRegistry, RawLog(), redirectCookie(), setStorageValue(), StoredMap (+12 more)

### Community 1 - "Community 1"
Cohesion: 0.09
Nodes (13): UsageSection, setupRequestInterception(), initElectronReceiver(), setupRequestInterception(), Ko-fi donation button asset, ButtonNotificationCard, DonationNotificationCard, FloatingCard (+5 more)

### Community 2 - "Community 2"
Cohesion: 0.11
Nodes (11): getConversationId(), getCurrentModel(), getCurrentModelVersion(), isCodePage(), Log(), waitForElement(), LengthUI, Patch notes: Firefox containers, peak hours TZ (+3 more)

### Community 3 - "Community 3"
Cohesion: 0.12
Nodes (6): containerFetch(), ClaudeAPI, ConversationAPI, Log(), MessageAPI, Token counting (Anthropic API vs gpt-tokenizer)

### Community 4 - "Community 4"
Cohesion: 0.2
Nodes (22): sendTabMessage(), checkResetNotifications(), debugLogMessageCost(), electronUsagePoll(), handleAlarm(), interceptedRequest(), interceptedResponse(), Log() (+14 more)

### Community 5 - "Community 5"
Cohesion: 0.11
Nodes (14): getActiveOrgId(), getChatLengthCostAnchor(), getChatLengthCostStatLineFallbackAnchor(), getChatTitleBeforeMenuAnchor(), getChatTitleBeforeShareAnchor(), initExtension(), injectStyles(), logError() (+6 more)

### Community 6 - "Community 6"
Cohesion: 0.16
Nodes (4): UsageUI, getResetTimeHTML(), isMobileView(), mountToAnchor()

### Community 7 - "Community 7"
Cohesion: 0.19
Nodes (1): UsageData

### Community 9 - "Community 9"
Cohesion: 1.0
Nodes (2): Interactive force-directed graph HTML export, GRAPH_REPORT god nodes and surprising connections

### Community 10 - "Community 10"
Cohesion: 1.0
Nodes (2): Claude QoL cross-promotion badge, Claude Usage Tracker Extension

### Community 14 - "Community 14"
Cohesion: 1.0
Nodes (1): Manifest V3 + webRequest + polyfill stack

### Community 15 - "Community 15"
Cohesion: 1.0
Nodes (1): Popup: help text for reload / authorize on claude.ai

### Community 16 - "Community 16"
Cohesion: 1.0
Nodes (1): Debug logs page (toolbar / context menu)

### Community 17 - "Community 17"
Cohesion: 1.0
Nodes (1): Extension icon 128px

### Community 18 - "Community 18"
Cohesion: 1.0
Nodes (1): Extension icon 512px

## Knowledge Gaps
- **16 isolated node(s):** `Claude Usage Tracker Extension`, `Token counting (Anthropic API vs gpt-tokenizer)`, `Usage sources: files, projects, prefs, history, tools, MCPs`, `Manifest V3 + webRequest + polyfill stack`, `Privacy: tokens, messages, reset time, org ID only` (+11 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Community 7`** (14 nodes): `UsageData`, `.constructor()`, `.fromAPIResponse()`, `.fromJSON()`, `.getActiveLimits()`, `.getBindingWeeklyLimit()`, `.getEstimatedTokensRemaining()`, `.getExtraUsageEffectiveTotal()`, `.getExtraUsageRemaining()`, `.getLimitingFactor()`, `.getMaxedLimits()`, `.getSessionResetInfo()`, `.hasExtraUsage()`, `.toJSON()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 9`** (2 nodes): `Interactive force-directed graph HTML export`, `GRAPH_REPORT god nodes and surprising connections`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 10`** (2 nodes): `Claude QoL cross-promotion badge`, `Claude Usage Tracker Extension`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 14`** (1 nodes): `Manifest V3 + webRequest + polyfill stack`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 15`** (1 nodes): `Popup: help text for reload / authorize on claude.ai`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 16`** (1 nodes): `Debug logs page (toolbar / context menu)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 17`** (1 nodes): `Extension icon 128px`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 18`** (1 nodes): `Extension icon 512px`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Log()` connect `Community 2` to `Community 0`, `Community 1`, `Community 5`, `Community 6`?**
  _High betweenness centrality (0.318) - this node is a cross-community bridge._
- **Why does `getStorageValue()` connect `Community 0` to `Community 4`?**
  _High betweenness centrality (0.089) - this node is a cross-community bridge._
- **Why does `LengthUI` connect `Community 2` to `Community 5`, `Community 6`?**
  _High betweenness centrality (0.077) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `LengthUI` (e.g. with `Usage sources: files, projects, prefs, history, tools, MCPs` and `Claude.ai chat with injected length/cost/cache/quota UI`) actually correct?**
  _`LengthUI` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 15 inferred relationships involving `Log()` (e.g. with `initElectronReceiver()` and `.init()`) actually correct?**
  _`Log()` has 15 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Claude Usage Tracker Extension`, `Token counting (Anthropic API vs gpt-tokenizer)`, `Usage sources: files, projects, prefs, history, tools, MCPs` to the rest of the system?**
  _16 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.08 - nodes in this community are weakly interconnected._