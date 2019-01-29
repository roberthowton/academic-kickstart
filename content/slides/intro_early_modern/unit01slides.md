+++
title = "Unit 0.1"

[slides]
# Choose a theme from https://github.com/hakimel/reveal.js#theming
theme = "sky"
+++

# Introducing Modern Philosophy

<aside class="notes">
  Why devote a course in the history of Western European philosophy to the \nth{17} and \nth{18} centuries? The reason may not be obvious. For one thing, philosophy in Europe is far \emph{older} than the \nth{17} century; it stretches at least as far back as the ancient Greeks in the \nth{6} century CE, perhaps even further, finding its ultimate roots in the speculations of ancient Egyptians and Babylonians centuries before. For another thing, the Western European philosophical tradition has \emph{continued} far beyond the \nth{18} century, and still persists in our \nth{21} century. But while the \nth{17} and \nth{18} centuries occupy only a small portion of the vast history of philosophy in the West, the thinkers who worked during this period have exerted an outsized influence on the Western philosophical tradition. Together, these thinkers introduced into the Western tradition a new way of doing philosophy, and introduced a new set of philosophical questions and problems. And they did so self-consciously: they saw themselves as breaking with the older tradition inherited from the middle ages, and as practicing an explicitly new form of philosophical inquiry. For these reasons these thinkers have been given the honorific title of \emph{modern philosophers}, and the centuries in which they worked has come to be known as the \emph{modern}, or \emph{early modern}, period.

  <p>Our goal this week is to get an idea of the intellectual background in which this break with philosophical tradition occurred. To do that, however, we must first get a grip on the intellectual scene in Western Europe before the early modern period.

  (I should note at the outset that I'll be painting with extremely broad strokes. I'm doing so to give you a serviceable grip on the intellectual milieu of Western Europe in the early modern period. Just keep in mind that many of the portraits I paint of pre-modern thought, especially that of Aristotle, are more like caricatures.)
</aside>

---

<section>
<!-- <h2>Features</h2> -->
- Efficiently write slides in Markdown
- 3-in-1: Create, Present, and Publish your slides
- Supports speaker notes
- Mobile friendly slides
</section>

<section>
<h3>Title of first vertical slide</h3>
 The body of the first slide
</section>
<section>
<h3>Title of second vertical slide</h3>
 The body of the second vertical slide
</section>

---

## Controls

- Next: `Right Arrow` or `Space`
- Previous: `Left Arrow`
- Start: `Home`
- Finish: `End`
- Overview: `Esc`
- Speaker notes: `S`
- Fullscreen: `F`
- Zoom: `Alt + Click`
- [PDF Export](https://github.com/hakimel/reveal.js#pdf-export): `E`

---

# This is a new section?

---

## Code Highlighting

Inline code: `variable`

Code block:
```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

---

## Math

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

---

## Fragments

Make content appear incrementally

```
{{%/* fragment */%}} One {{%/* /fragment */%}}
{{%/* fragment */%}} **Two** {{%/* /fragment */%}}
{{%/* fragment */%}} Three {{%/* /fragment */%}}
```

Press `Space` to play!

{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}
- Only the speaker can read these notes
- Press `S` key to view
{{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}
- Only the speaker can read these notes
- Press `S` key to view
{{< /speaker_note >}}

---

## Themes

- black: Black background, white text, blue links (default)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

{{< slide background-image="/img/univ.jpg" class="stretch" >}}
{{< slide theme ="white" >}}

## Custom Slide


Customize the slide style and background

```markdown
{{</* slide background-image="/img/boards.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

---

# Questions?

[Ask](https://discourse.gohugo.io)

[Documentation](https://sourcethemes.com/academic/docs/)
