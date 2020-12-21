---
layout: post
title: Recurrent misuse of API-first pattern/strategy, Stefan Tilkov
permalink: /tla_insights/api-first-misuse_tilkov
categories: [Socio-Technical]
tla_area: [tla, tla_sociotech]
id: api-first-misuse_tilkov
digest: 1
date: 2020-09-02
summary: | 
  Very interesting Twitter thread on the misuse of API-first strategy and how to re-focus it on the important elements (especially be outside-in strategy, with customer as central designing force, instead of inside-out).
insightweet: |
  APIs provide "encapsulation" and a way to expose capabilities of a business. However, they should (must) be built based on the customer(s) that will use them, in true "product development" style.
---

#### [[Tweet thread](https://twitter.com/stilkov/status/1250355396864176132?s=20%20)]

> ![light](/assets/light-bulb.png) **My Insights:** This is a really good thread to freshen up strategies, patterns and best practices to drive the building of API-based products. Although APIs provide "encapsulation" and a way to expose capabilities of a business, they should (I would say must) be built based on the customer(s) that will use them, in true "product development" style. They are not "just a technical artifact for integration", even though this can also be a consequence. However, we should not be the sole driving factor, even if the goal is to enable integration.

### Analysis & Summary

This Twitter thread by [Stefan Tilkov](https://twitter.com/stilkov) raised a very interesting discussion on the rather common misuse of the “API-first“ strategy. In classic Stefan style, he comprehensively shows several interesting points and patterns where such misuse happens. Most prominently the overuse of this technique for "encapsulation" of technical capabilities within the "enterprise". This tends to be part of the mission of many Enterprise Architects, as a way to have a good governance model over the different "parts of the enterprise". However, if APIs are purely built "inside-out" (just as a way to encapsulate and expose business capabilities) and are not built as a product, i.e.: based on the needs of the customers/clients using it (and what they are looking for), it tends to lead to a mismatch of expectations.

At a given moment of the thread Simon Wardley shared a nice visualization of "types of developments" where APIs are strategic and how to start such initiatives using [his famous Wardley maps](https://twitter.com/swardley/status/1251479895479386114?s=19).

<br>

<form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/tla_insights"
  method="post" target="popupwindow"
  onsubmit="window.open('https://tinyletter.com/tla_insights', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
  <p><label for="tlemail">Enter your email to be notified of future TLA_insights</label></p>
  <p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1"
    name="embed" /><input type="submit" value="Subscribe" />
</form>
