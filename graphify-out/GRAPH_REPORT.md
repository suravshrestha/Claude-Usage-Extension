# Graph Report - Claude-Usage-Extension  (2026-05-14)

## Corpus Check
- 16 files · ~33,302 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 261 nodes · 573 edges · 16 communities detected
- Extraction: 72% EXTRACTED · 28% INFERRED · 0% AMBIGUOUS · INFERRED: 161 edges (avg confidence: 0.8)
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
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]

## God Nodes (most connected - your core abstractions)
1. `LengthUI` - 23 edges
2. `Log()` - 21 edges
3. `UsageUI` - 20 edges
4. `Log()` - 18 edges
5. `processResponse()` - 16 edges
6. `ClaudeAPI` - 15 edges
7. `UsageData` - 14 edges
8. `requestData()` - 13 edges
9. `sendBackgroundMessage()` - 10 edges
10. `ConversationData` - 10 edges

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
Nodes (19): handleMessageFromContent(), addContainerFetchListener(), getStorageValue(), Log(), MessageHandlerRegistry, RawLog(), redirectCookie(), setStorageValue() (+11 more)

### Community 1 - "Community 1"
Cohesion: 0.11
Nodes (10): getConversationId(), getCurrentModel(), getCurrentModelVersion(), isCodePage(), waitForElement(), LengthUI, Patch notes: Firefox containers, peak hours TZ, Usage sources: files, projects, prefs, history, tools, MCPs (+2 more)

### Community 2 - "Community 2"
Cohesion: 0.11
Nodes (9): UsageSection, Ko-fi donation button asset, ButtonNotificationCard, DonationNotificationCard, FloatingCard, makeDraggable(), openDebugOverlay(), RateNotificationCard (+1 more)

### Community 3 - "Community 3"
Cohesion: 0.13
Nodes (6): containerFetch(), ClaudeAPI, ConversationAPI, Log(), MessageAPI, Token counting (Anthropic API vs gpt-tokenizer)

### Community 4 - "Community 4"
Cohesion: 0.12
Nodes (6): UsageUI, getResetTimeHTML(), isMobileView(), mountToAnchor(), ProgressBar, setupTooltip()

### Community 5 - "Community 5"
Cohesion: 0.2
Nodes (20): checkResetNotifications(), debugLogMessageCost(), electronUsagePoll(), handleAlarm(), interceptedRequest(), interceptedResponse(), Log(), logError() (+12 more)

### Community 6 - "Community 6"
Cohesion: 0.16
Nodes (14): getActiveOrgId(), getChatLengthCostAnchor(), getChatLengthCostStatLineFallbackAnchor(), getChatTitleBeforeMenuAnchor(), getChatTitleBeforeShareAnchor(), initExtension(), injectStyles(), Log() (+6 more)

### Community 7 - "Community 7"
Cohesion: 0.23
Nodes (4): initElectronReceiver(), setupRequestInterception(), FloatingCardsUI, SettingsCard

### Community 8 - "Community 8"
Cohesion: 0.19
Nodes (1): UsageData

### Community 10 - "Community 10"
Cohesion: 1.0
Nodes (2): Interactive force-directed graph HTML export, GRAPH_REPORT god nodes and surprising connections

### Community 11 - "Community 11"
Cohesion: 1.0
Nodes (2): Claude QoL cross-promotion badge, Claude Usage Tracker Extension

### Community 15 - "Community 15"
Cohesion: 1.0
Nodes (1): Manifest V3 + webRequest + polyfill stack

### Community 16 - "Community 16"
Cohesion: 1.0
Nodes (1): Popup: help text for reload / authorize on claude.ai

### Community 17 - "Community 17"
Cohesion: 1.0
Nodes (1): Debug logs page (toolbar / context menu)

### Community 18 - "Community 18"
Cohesion: 1.0
Nodes (1): Extension icon 128px

### Community 19 - "Community 19"
Cohesion: 1.0
Nodes (1): Extension icon 512px

## Knowledge Gaps
- **16 isolated node(s):** `Claude Usage Tracker Extension`, `Token counting (Anthropic API vs gpt-tokenizer)`, `Usage sources: files, projects, prefs, history, tools, MCPs`, `Manifest V3 + webRequest + polyfill stack`, `Privacy: tokens, messages, reset time, org ID only` (+11 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Community 8`** (14 nodes): `UsageData`, `.constructor()`, `.fromAPIResponse()`, `.fromJSON()`, `.getActiveLimits()`, `.getBindingWeeklyLimit()`, `.getEstimatedTokensRemaining()`, `.getExtraUsageEffectiveTotal()`, `.getExtraUsageRemaining()`, `.getLimitingFactor()`, `.getMaxedLimits()`, `.getSessionResetInfo()`, `.hasExtraUsage()`, `.toJSON()`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 10`** (2 nodes): `Interactive force-directed graph HTML export`, `GRAPH_REPORT god nodes and surprising connections`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 11`** (2 nodes): `Claude QoL cross-promotion badge`, `Claude Usage Tracker Extension`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 15`** (1 nodes): `Manifest V3 + webRequest + polyfill stack`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 16`** (1 nodes): `Popup: help text for reload / authorize on claude.ai`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 17`** (1 nodes): `Debug logs page (toolbar / context menu)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 18`** (1 nodes): `Extension icon 128px`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Community 19`** (1 nodes): `Extension icon 512px`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Log()` connect `Community 6` to `Community 0`, `Community 1`, `Community 4`, `Community 7`?**
  _High betweenness centrality (0.257) - this node is a cross-community bridge._
- **Why does `processResponse()` connect `Community 5` to `Community 0`, `Community 1`, `Community 3`, `Community 7`?**
  _High betweenness centrality (0.076) - this node is a cross-community bridge._
- **Why does `LengthUI` connect `Community 1` to `Community 4`?**
  _High betweenness centrality (0.075) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `LengthUI` (e.g. with `Usage sources: files, projects, prefs, history, tools, MCPs` and `Claude.ai chat with injected length/cost/cache/quota UI`) actually correct?**
  _`LengthUI` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 15 inferred relationships involving `Log()` (e.g. with `initElectronReceiver()` and `.init()`) actually correct?**
  _`Log()` has 15 INFERRED edges - model-reasoned connections that need verification._
- **Are the 9 inferred relationships involving `processResponse()` (e.g. with `.get()` and `.getUsageData()`) actually correct?**
  _`processResponse()` has 9 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Claude Usage Tracker Extension`, `Token counting (Anthropic API vs gpt-tokenizer)`, `Usage sources: files, projects, prefs, history, tools, MCPs` to the rest of the system?**
  _16 weakly-connected nodes found - possible documentation gaps or missing edges._