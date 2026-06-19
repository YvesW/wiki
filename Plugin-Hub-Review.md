# Plugin Hub

The [Plugin Hub](https://runelite.net/plugin-hub) contains plugins developed by third parties not affiliated with RuneLite. You can install plugins from the Plugin Hub via the side panel in the client.

Third party plugins commonly cause bugs and client instability, and is the primary source of support issues raised to the RuneLite developers. We recommend being conservative in which plugins you install, and try to limit it to the more well known and tested plugins if possible. If you begin to experience issues after installing a new plugin, consider that new the plugin might be at fault, even if the issue seems like it should be unrelated.

## Plugin Hub Review

Plugin Hub plugins are reviewed both during initial submission, and also any subsequent update, by human reviewers affiliated with RuneLite, as well as AI agents.

RuneLite's review process focuses on two aspects: security and game rule compliance.

We verify that plugins aren't malicious, such as stealing account credentials or installing malware. This is achieved primarily by having rules on the code we accept, such as restricting reflection and native code, limiting dependencies, and by utilizing automatic code scanning.

We review plugin submissions for rule breaking behavior. This is done best-effort as the rules communicated to us by Jagex can often be subjective or can change due to emerging gameplay or new content.

RuneLite's review processes additionally has several *non-goals*:

We do not check that plugins function, or are useful for a particular purpose. If a plugin destabilizes the wider plugin ecosystem or client we may proactively disable it in order to stabilize the client or its surrounding infrastructure.

We do not check that plugins have good performance, or that they don't cause lag during certain actions.

We do not check that plugins don't break functionality of other plugins.

We do not check that information displayed by plugins is factually accurate or correct.

### Reviewers

Beginning in April 2026, RuneLite operates an automated review bot that can automatically approve plugin updates. Most simple plugins can be approved by the bot automatically.

The automated review bot was made as a result of recent technological advancements in code generation with AI. Since late 2025/early 2026, the majority of new plugin code is no longer written by humans or submitted by humans. RuneLite does not have the funding to have humans review all of the code submitted at the scale which we operate (and even if it did, allocating resources to have humans review machine generated code is not wise).

All other review is done by humans; either directly reviewing the submitted code, or by configuring the review bot with the specific permissions and restrictions that the plugin is allowed to have.