# KittySuite IDE

**The only true Integrated Development Environment.**

Most "IDEs" today are actually just platforms around fancy text editors. They are loose collections of plugins, system dependencies, and cloud-tethered extensions. They lack **Integration** because they require you to assemble the toolchain yourself. They lack **Integrity** because they prioritize telemetry and cloud-syncing over the safety of your source code.

**KittySuite is different.** 

We built this for the front lines: the research vessel, the airgapped lab, and the engineer who needs their tools to work 100% of the time, regardless of internet connectivity or system configuration.

### Integration
A development environment is only "Integrated" if it actually contains the tools. 
*   **The Toolchain is Inside:** KittySuite comes pre-packaged with **`uv`**, **`Go`**, and **`Zig`**. You don't "set up" an environment; you install the IDE and start coding.
*   **The Version Control is Inside:** We don't rely on your "system git." We built native version control directly into the engine. It works the second you open it.
*   **The Intelligence is Inside:** Our AI archetecture is powered by the bundled **`llama.cpp`**. Drag in a GGUF (and vision encoder if you have any) and you have a local LLM that works in airgapped environments.

### Integrity
Because we build all the integrations ourselves:
*   **You don't have to wonder which team to contact when something breaks. It is always support@rocklab.in.
*   **All tools share a similar mental model and UI. Every action is generally one keyboard shortcut (or one mouse click) away.
*   **Every integration is guaranteed to be compatible with every other integration.

### Built for Builders
KittySuite is a spartan instrument. It is for people who build things, not people who fill Jira tickets. It lets you leverage the compute inside your own computer instead of forcing you to rent it. 

That said, KittySuite is fully compatible with online LLM providers. If you have connectivity and prefer to use Google, Anthropic, or OpenAI compatible APIs, simply plug in your API key and get started. The keys (and your GitHub tokens, if plugged in) are stored securely in your system's vault. If a secure vault is not available they are not stored at all.

**If it isn’t Integrated, it isn't an IDE.**

---

### Verifying Authenticity
Integrity starts at the download. Verify your installer using our public key:
`minisign -Vm <filename> -P RWTI79HUgL+C3MLnP0T77TZDmMEz20YFa5lQPHQ0SR3+5ip0kRuGiAUA`
