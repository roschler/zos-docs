---
id: version-0.0.4-upgradeability_Proxy
title: Proxy
original_id: upgradeability_Proxy
---

<div class="contract-doc"><div class="contract"><h2 class="contract-header"><span class="contract-kind">contract</span> Proxy</h2><p class="description">Returned by the abstract _implementation() internal function.</p><div class="source">Source: <a href="git+https://github.com/zeppelinos/zos-lib/blob/v0.1.12/contracts/upgradeability/Proxy.sol" target="_blank">upgradeability/Proxy.sol</a></div></div><div class="index"><h2>Index</h2><ul><li><a href="upgradeability_Proxy.html#_delegate">_delegate</a></li><li><a href="upgradeability_Proxy.html#_fallback">_fallback</a></li><li><a href="upgradeability_Proxy.html#_implementation">_implementation</a></li><li><a href="upgradeability_Proxy.html#_willFallback">_willFallback</a></li><li><a href="upgradeability_Proxy.html#">fallback</a></li></ul></div><div class="reference"><h2>Reference</h2><div class="functions"><h3>Functions</h3><ul><li><div class="item function"><span id="_delegate" class="anchor-marker"></span><h4 class="name">_delegate</h4><div class="body"><code class="signature">function <strong>_delegate</strong><span>(address implementation) </span><span>internal </span></code><hr/><div class="description"><p>It will return to the external caller whatever the implementation returns. * @param implementation address to which we delegate.</p></div><dl><dt><span class="label-parameters">Parameters:</span></dt><dd><div><code>implementation</code> - address</div></dd></dl></div></div></li><li><div class="item function"><span id="_fallback" class="anchor-marker"></span><h4 class="name">_fallback</h4><div class="body"><code class="signature">function <strong>_fallback</strong><span>() </span><span>internal </span></code><hr/><div class="description"><p>Extracted fallback function to enable manual triggering.</p></div></div></div></li><li><div class="item function"><span id="_implementation" class="anchor-marker"></span><h4 class="name">_implementation</h4><div class="body"><code class="signature"><span>abstract </span>function <strong>_implementation</strong><span>() </span><span>internal </span><span>view </span><span>returns  (address) </span></code><hr/><dl><dt><span class="label-return">Returns:</span></dt><dd>address of the implementation to which the fallback delegates all calls</dd></dl></div></div></li><li><div class="item function"><span id="_willFallback" class="anchor-marker"></span><h4 class="name">_willFallback</h4><div class="body"><code class="signature">function <strong>_willFallback</strong><span>() </span><span>internal </span></code><hr/><div class="description"><p>Redefinitions must call super._willFallback().</p></div></div></div></li><li><div class="item function"><span id="fallback" class="anchor-marker"></span><h4 class="name">fallback</h4><div class="body"><code class="signature">function <strong></strong><span>() </span><span>external </span><span>payable </span></code><hr/><div class="description"><p>Implemented entirely in _fallback.</p></div></div></div></li></ul></div></div></div>