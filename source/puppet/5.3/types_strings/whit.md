---
layout: default
built_from_commit: efc61e00b8b0683ac74815af8e978cd8de6e53ed
title: 'Resource Type: whit'
canonical: "/puppet/latest/types/whit.html"
---

> **NOTE:** This page was generated from the Puppet source code on 2018-02-05 12:35:27 -0800

whit
-----

* [Attributes](#whit-attributes)

<h3 id="whit-description">Description</h3>

Whits are internal artifacts of Puppet's current implementation, and
Puppet suppresses their appearance in all logs. We make no guarantee of
the whit's continued existence, and it should never be used in an actual
manifest. Use the `anchor` type from the puppetlabs-stdlib module if you
need arbitrary whit-like no-op resources.

<h3 id="whit-attributes">Attributes</h3>

<pre><code>whit { 'resource title':
  <a href="#whit-attribute-name">name</a> =&gt; <em># <strong>(namevar)</strong> The name of the whit, because it must have...</em>
  # ...plus any applicable <a href="{{puppet}}/metaparameter.html">metaparameters</a>.
}</code></pre>

<h4 id="whit-attribute-name">name</h4>

_(**Namevar:** If omitted, this attribute's value defaults to the resource's title.)_

The name of the whit, because it must have one.

([↑ Back to whit attributes](#whit-attributes))





> **NOTE:** This page was generated from the Puppet source code on 2018-02-05 12:35:27 -0800