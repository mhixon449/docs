---
---

<div class="section" id="module-pulumi_kubernetes.authentication.v1beta1">
<span id="v1beta1"></span><h1>v1beta1<a class="headerlink" href="#module-pulumi_kubernetes.authentication.v1beta1" title="Permalink to this headline">¶</a></h1>
<dl class="class">
<dt id="pulumi_kubernetes.authentication.v1beta1.TokenReview">
<em class="property">class </em><code class="descclassname">pulumi_kubernetes.authentication.v1beta1.</code><code class="descname">TokenReview</code><span class="sig-paren">(</span><em>resource_name</em>, <em>opts=None</em>, <em>metadata=None</em>, <em>spec=None</em>, <em>status=None</em>, <em>__name__=None</em>, <em>__opts__=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_kubernetes.authentication.v1beta1.TokenReview" title="Permalink to this definition">¶</a></dt>
<dd><p>TokenReview attempts to authenticate a token to a known user. Note: TokenReview requests may be
cached by the webhook token authenticator plugin in the kube-apiserver.</p>
<dl class="method">
<dt id="pulumi_kubernetes.authentication.v1beta1.TokenReview.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop: str</em><span class="sig-paren">)</span> &#x2192; str<a class="headerlink" href="#pulumi_kubernetes.authentication.v1beta1.TokenReview.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_kubernetes.authentication.v1beta1.TokenReview.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop: str</em><span class="sig-paren">)</span> &#x2192; str<a class="headerlink" href="#pulumi_kubernetes.authentication.v1beta1.TokenReview.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

</div>
