---
layout: page
title: "Field Records | Minqi Geng"
permalink: /research
---

<div class="cyber-border p-8 md:p-16">
    <div class="flex items-center justify-between mb-8">
        <div class="flex items-center gap-2">
            <span class="status-dot"></span>
            <span class="mono text-xs uppercase tracking-[0.3em] text-cyan-500/70">Field Records</span>
        </div>
        <a href="/" class="nav-btn px-4 py-2 mono text-xs border-gray-500 text-gray-500 hover:bg-gray-500 hover:text-black">
            <span>[ BACK_TO_HOME ]</span>
        </a>
    </div>

    <div class="prose prose-invert prose-cyan max-w-none mono text-gray-300">
        {% capture exp %}{% include experiences.md %}{% endcapture %}
        {{ exp | markdownify }}
    </div>
</div>
