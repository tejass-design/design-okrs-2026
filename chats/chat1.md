# Design OKRs 2026

_Started 2026-04-28 04:57 UTC_

---

## User

Help me create a compelling one pager for Design OKRs which can be socialised with the leadership. Ensure to keep an eye on the tokens used. I want the experience to be remembered

the content for the Design OKRs are as follow:
Product Design OKRs | 2026

Design North Star
Craft workflows that feel intuitive, predictable, and in control, so users can move through complex tasks without friction or second-guessing.


Objective 1: Drive Consistency in Interaction and behaviour
Intent: The product should behave predictably across all workflows.
Key Results:
Standardise 100% of core interaction patterns (selection, editing, feedback, states)
Reduce design-related inconsistencies identified in QA/usability reviews by 40%
Achieve 100% design system adoption in shipped features
Improve perceived product polish and consistency
Design Ownership:
Design system, interaction patterns, behavioral consistency, cross-flow alignment

Objective 2: Improve Discoverability Without Increasing Cognitive Load
Intent: Features should be easy to find when needed, invisible when not.
Key Results:
Increase discoverability of key features (measured via task completion)
Reduce instances of feature blindness by 40%
Maintain or reduce cognitive load while improving discoverability
Ensure all advanced features are accessible within 2–3 logical steps
Design Ownership:
Progressive disclosure, hierarchy, visual design, contextual surfacing

## Assistant

I'll create a memorable one-pager for your 2026 Product Design OKRs. Let me ask a few quick questions to make this land well with leadership.

_[tool: questions_v2]_

## User

Questions answered:
- format: Single scrollable web one-pager (interactive, memorable)
- tone: Warm & human — feels like a story
- memorable_device: Big numbers (KR targets) as the visual hero
- brand: Use a clean, neutral aesthetic (you decide)
- audience: Cross-functional partners (PM, Eng)
- include_owner: Omit — focus on Objectives + KRs
- north_star_treatment: Anchor — present but balanced with objectives

## Assistant

I've got what I need. Let me build this.

**Direction:** Single scrollable web one-pager, warm & human story, big-number KR heroes, clean neutral aesthetic, cross-functional audience, Objectives + KRs only (no ownership block), North Star as a balanced anchor.

**Aesthetic commitment** (declared, sticking to it):
- Type: "Fraunces" for editorial display moments + "Inter Tight" for UI/body — wait, both on the avoid-list. Switching to **"Newsreader"** (warm serif, story feel) + **"Geist"** (clean grotesque) + **"Geist Mono"** for numerical accents.
- Palette: warm off-white `oklch(0.97 0.008 80)` background, ink `oklch(0.18 0.01 60)`, muted `oklch(0.55 0.01 60)`, single accent terracotta `oklch(0.62 0.12 40)`.
- Big numbers as hero — set in Newsreader at extreme display sizes.
- No emoji, no SVG illustrations, no gradient slop, no left-border accent cards.

_[tool: update_todos]_

_[tool: set_project_title]_

_[tool: write_file]_

_[tool: done]_

_[tool: fork_verifier_agent]_

Built a warm, editorial one-pager that anchors on the North Star and lets the KR numbers carry the visual weight.

**The build:**
- **Type system** — Newsreader (warm serif, story tone) for headlines & big numbers, Geist for UI, Geist Mono for labels.
- **Palette** — warm off-white paper, deep ink, single terracotta accent. No gradients, no decoration.
- **Hero** — "A year of *quiet* confidence in the craft." The North Star sits right below as a balanced anchor block.
- **KR treatment** — each Key Result gets its own column with a giant Newsreader number (`100%`, `−40%`, `2–3`) as the hero. Where targets are qualitative, the number-slot becomes an italic word (*felt*, *held*, *found*) — keeps parallelism without faking metrics.
- **Memorable device** — numbers count up on scroll-reveal, gently staggered.

**Two notes for you:**
- I kept Objective 1's KR4 ("perceived polish") and Objective 2's KR1 ("discoverability") and KR3 ("cognitive load") as qualitative — your source didn't pin numbers on them. If you want hard targets there, send them and I'll swap them in.
- Per your direction, "Design Ownership" is omitted to keep leadership focused on Objectives + KRs.

## User

Apply 4 direct edits:
1. In Design OKRs 2026.html: change the text from "Standardise core interaction patterns — selection, editing, feedback and states — across the product." to "Standardise core interaction patterns — selection, editing, feedback and states across the product.".
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal › div.copy[3/3]
text:     "Standardise core interaction patterns — selection, editing,…"
children: strong, text
selector: [data-om-id="fc362fde:43"]
id:       cc-2
</mentioned-element>
2. In Design OKRs 2026.html: change the text from "Perceived polish improves — measured through internal craft reviews and user sentiment passes." to "Perceived polish improves measured through internal craft reviews and user sentiment passes.".
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal › div.copy[3/3]
text:     "Perceived polish improves — measured through internal craft…"
children: strong, text
selector: [data-om-id="fc362fde:62"]
id:       cc-3
</mentioned-element>
3. In Design OKRs 2026.html: change the text from "Perceived polish improves measured through internal craft reviews and user sentiment passes." to "Improve perceived product polish and consistency".
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal › div.copy[3/3]
text:     "Perceived polish improves measured through internal craft r…"
children: strong, text
selector: [data-om-id="fc362fde:62"]
id:       cc-3
</mentioned-element>
4. In Design OKRs 2026.html: set the inline style to `font-weight: 500`.
<mentioned-element>
dom:      body › main › … › div.copy › span#docs-internal-guid-18156502-7fff-2531-5102-7ffff2cddab7 › span
text:     "Improve perceived product polish and consistency"
children: text
selector: #docs-internal-guid-18156502-7fff-2531-5102-7ffff2cddab7 >:is(h1,h2,h3,h4,h5,h6,p,li,dt,dd,blockquo…
id:       cc-6
</mentioned-element>

## Assistant

_[tool: str_replace_edit]_

_[tool: snip]_

Edits applied — KR1.1 dashes tightened, and KR1.4's copy is now "Improve perceived product polish and consistency" with the full line in 500 weight.

## User

Save this design as a PDF: Design OKRs 2026.html

## Assistant

I'll create a print-ready version optimized for PDF export.

_[tool: read_file]_

Let me copy the file and add print styles + auto-print.

_[tool: copy_files]_

Now I'll add print styles. The page is a vertical scrolling one-pager — for PDF I'll use portrait A4 (one tall page if it fits, with smart page breaks between objectives if not), force backgrounds, disable reveal animations so everything is visible, and auto-print.

_[tool: str_replace_edit]_

_[tool: str_replace_edit]_

Let me verify the print file loads cleanly before triggering print.

_[tool: show_html]_

The auto-print would fire if I previewed it directly. Let me just open it for print.

_[tool: open_for_print]_

Print dialog should open automatically — choose **Save as PDF** as the destination. If popup was blocked, [open it manually here](https://019dd272-ea11-7377-a6d2-c7ac793f02f8.claudeusercontent.com/v1/design/projects/019dd272-ea11-7377-a6d2-c7ac793f02f8/serve/Design%20OKRs%202026-print.html?t=173c8db9c7bfbccc1f8cc0760e37e6e3d1cd960d25d24568d03430ef577a60a4.de438cf5-6b73-4029-b22a-e4c594b66083.77ceef93-8bf9-473f-8f10-8dd51f2a4d14.1777355840). I sized the page as A3 portrait so the editorial scale and big-number KRs hold their weight on a single sheet — switch to A4 in the dialog if you prefer that and need a tighter page.

## User

Save as standalone HTML: Design OKRs 2026.html

## Assistant

_[tool: snip]_

_[tool: copy_files]_

The source file only references resources via standard HTML attributes (the Google Fonts `<link href>`) — no JS-string-referenced assets. So I just need to add the thumbnail template and run the bundler.

_[tool: str_replace_edit]_

_[tool: super_inline_html]_

Bundled cleanly (860KB — fonts inlined). Let me verify it loads, then deliver.

_[tool: show_html]_

_[tool: get_webview_logs]_

Clean. Delivering.

_[tool: delete_file]_

_[tool: present_fs_item_for_download]_

_[tool: snip]_

_[tool: read_file]_

Now I'll apply all 9 edits. Note edit 4 effectively re-adds a trailing space, edits 1+3 replace already-applied content, and edits 2+7 only have one occurrence each (no script template literals contain "held" or "quiet"). Edit 5 adds a line break.

_[tool: str_replace_edit]_

_[tool: snip]_

All 9 edits applied: hero now reads "A year of confidence in the craft." (no italic accent, single line), KR 2.1 / 2.2 / 2.3 copy updated, and KR 2.3's hero word is now "Reduce".

## User

Save as standalone HTML: Design OKRs 2026.html

## Assistant

_[tool: snip]_

_[tool: copy_files]_

No JS-string-referenced assets — only the Google Fonts `<link>`. Adding the thumbnail and bundling.

_[tool: str_replace_edit]_

_[tool: super_inline_html]_

_[tool: snip]_

Bundled cleanly (860KB, fonts inlined).

_[tool: delete_file]_

_[tool: present_fs_item_for_download]_

Download is ready above — single self-contained HTML, works offline.

## User

Apply 17 direct edits:
1. In Design OKRs 2026.html: change the text from "— Product Design, 2026" to "Product Design, 2026".
<mentioned-element>
dom:      body › main › footer.footer › div.sig[2/3]
text:     "— Product Design, 2026"
children: text
selector: [data-om-id="c435af83:99"]
id:       cc-2
</mentioned-element>
2. In Design OKRs 2026.html: change the text from "Should be felt" to "Should be\nfelt".
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal › div.hero-num.text[2/3]
text:     "Should be felt"
children: text
selector: [data-om-id="c435af83:61"]
id:       cc-3
</mentioned-element>
3. In Design OKRs 2026.html: set the inline style to `padding: 43px 28px 0px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[4/4]
text:     "KR 1.4 Should be felt Improve perceived product polish and …"
children: div, div, div
selector: [data-om-id="c435af83:59"]
id:       cc-5
</mentioned-element>
4. In Design OKRs 2026.html: set the inline style to `padding: 43px 28px 36px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[4/4]
text:     "KR 1.4 Should be felt Improve perceived product polish and …"
children: div, div, div
selector: [data-om-id="c435af83:59"]
id:       cc-5
</mentioned-element>
5. In Design OKRs 2026.html: set the inline style to `padding: 43px 28px 40px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[4/4]
text:     "KR 1.4 Should be felt Improve perceived product polish and …"
children: div, div, div
selector: [data-om-id="c435af83:59"]
id:       cc-5
</mentioned-element>
6. In Design OKRs 2026.html: set the inline style to `padding: 43px 28px 52px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[4/4]
text:     "KR 1.4 Should be felt Improve perceived product polish and …"
children: div, div, div
selector: [data-om-id="c435af83:59"]
id:       cc-5
</mentioned-element>
7. In Design OKRs 2026.html: set the inline style to `padding: 43px 28px 63px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[4/4]
text:     "KR 1.4 Should be felt Improve perceived product polish and …"
children: div, div, div
selector: [data-om-id="c435af83:59"]
id:       cc-5
</mentioned-element>
8. In Design OKRs 2026.html: set the inline style to `padding: 43px 28px 64px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[4/4]
text:     "KR 1.4 Should be felt Improve perceived product polish and …"
children: div, div, div
selector: [data-om-id="c435af83:59"]
id:       cc-5
</mentioned-element>
9. In Design OKRs 2026.html: set the inline style to `padding: 43px 28px 62px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[4/4]
text:     "KR 1.4 Should be felt Improve perceived product polish and …"
children: div, div, div
selector: [data-om-id="c435af83:59"]
id:       cc-5
</mentioned-element>
10. In Design OKRs 2026.html: set the inline style to `padding: 43px 28px 61px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[4/4]
text:     "KR 1.4 Should be felt Improve perceived product polish and …"
children: div, div, div
selector: [data-om-id="c435af83:59"]
id:       cc-5
</mentioned-element>
11. In Design OKRs 2026.html: set the inline style to `padding: 43px 28px 60px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[4/4]
text:     "KR 1.4 Should be felt Improve perceived product polish and …"
children: div, div, div
selector: [data-om-id="c435af83:59"]
id:       cc-5
</mentioned-element>
12. In Design OKRs 2026.html: set the inline style to `padding: 43px 28px 58px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[4/4]
text:     "KR 1.4 Should be felt Improve perceived product polish and …"
children: div, div, div
selector: [data-om-id="c435af83:59"]
id:       cc-5
</mentioned-element>
13. In Design OKRs 2026.html: set the inline style to `padding: 44px 28px 35px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[2/4]
text:     "KR 2.2 − 40 % Less feature blindness — users notice and use…"
children: div, div, div
selector: [data-om-id="c435af83:78"]
id:       cc-9
</mentioned-element>
14. In Design OKRs 2026.html: set the inline style to `padding: 44px 28px 33px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[2/4]
text:     "KR 2.2 − 40 % Less feature blindness — users notice and use…"
children: div, div, div
selector: [data-om-id="c435af83:78"]
id:       cc-9
</mentioned-element>
15. In Design OKRs 2026.html: set the inline style to `padding: 44px 28px 57px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[2/4]
text:     "KR 2.2 − 40 % Less feature blindness — users notice and use…"
children: div, div, div
selector: [data-om-id="c435af83:78"]
id:       cc-9
</mentioned-element>
16. In Design OKRs 2026.html: set the inline style to `padding: 44px 28px 55px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[2/4]
text:     "KR 2.2 − 40 % Less feature blindness — users notice and use…"
children: div, div, div
selector: [data-om-id="c435af83:78"]
id:       cc-9
</mentioned-element>
17. In Design OKRs 2026.html: set the inline style to `padding: 44px 28px 56px`.
<mentioned-element>
dom:      body › main › section › div.krs › div.kr.reveal[2/4]
text:     "KR 2.2 − 40 % Less feature blindness — users notice and use…"
children: div, div, div
selector: [data-om-id="c435af83:78"]
id:       cc-9
</mentioned-element>

## User

Apply comment

## Assistant

The user wants all KR card content to share the same vertical starting point — currently `.kr .copy` has `margin-top: auto` which pushes the copy to the bottom, so the body text is at different heights depending on number-block size. Let me read the relevant section and fix it.

_[tool: snip]_

_[tool: grep]_

_[tool: grep]_

_[tool: str_replace_edit]_

_[tool: snip]_

_[tool: done]_

Done — KR cards now use a 3-row grid (label / number / copy) so the copy text starts at the same vertical position across all four cards in each row, regardless of number-block size. Removed the manual padding overrides on KR 1.4 and KR 2.2 since they're no longer needed.

